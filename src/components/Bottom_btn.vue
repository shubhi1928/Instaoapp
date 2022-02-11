<template>
    <div>

        <button v-on:click="initWeb3" id="transfer">Transfer</button>
    </div>
</template>
<script>
import Web3 from 'web3'
export default {
    name: "Bottom_btn",
    data()
    {
        return {ether:{
         networkId: null,
         coinbase:null,
         balance:null

        }}
    },
    methods:{
        
async initWeb3 () {
      // Check for web3 provider
      if (typeof window.ethereum !== 'undefined') {
        try {
          // Ask to connect
          await window.ethereum.send('eth_requestAccounts');
          const instance = new Web3(window.ethereum)
          // Get necessary info on your node
          this.ether.networkId = await instance.eth.net.getId();
         this.ether.coinbase = await instance.eth.getCoinbase();
          this.ether.balance= await instance.eth.getBalance(this.ether.coinbase)
          console.log(this.ether)
          console.log(this.ether.networkId)
          
        } catch (error) {
          // User denied account access
          console.error('User denied web3 access', error);
          return;
        }        
      }
      // No web3 provider
      else {
        console.error('No web3 provider detected');
        return;
      }
    }


    }
}
</script>
<style scoped>
#transfer{
  display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 10px 15px;
 color: white;
position: static;
width: 418px;
height: 40px;
left: 0px;
top: 347px;

/* Violet/400 */

background: #A78BFA;
border-radius: 12px;

/* Inside auto layout */

flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
margin: 20px 0px;
}
</style>
