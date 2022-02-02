<template>
    <div id="man_form">
        
          <Top_btn />

            <div id="deposit_form">
              <p id="text_stake">STAKE LOOKS, EARN UPTO</p>
              <p id="ARP">782.27 % ARP</p>
              <Main_form />
          <Bottom_btn/>
            </div>


  </div>
  
</template>

<script>
import Bottom_btn from '../components/Bottom_btn.vue'
import Top_btn from '../components/Top_btn.vue'
import Main_form from'../components/Main_form.vue'
export default {
    name: "Main",
    components :{
        Bottom_btn,
        Top_btn,
        Main_form
    }
}
</script>
<style scoped>
#man_form{
    position:relative;
    display: flex;
    justify-content: center;
    padding: 10px;
    height: 600px;
    margin:70px 0 0 0;
    top: 69.5px;
}


#deposit_form{
    padding: 25px;
    position:relative;
    width: 468px;
    height: 527px;
    top: 69.5px;
    background: #F5F3FF;
    border-radius: 16px;
}
#text_stake{
    width: 191px;
    height: 20px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 20px;
    text-transform: uppercase;
    color: #9CA3AF;
    flex-grow: 0;
    margin: 10px 0px;
}

#ARP{
    width: 233px;
    height: 30px;
    font-family: Inter;
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 30px;
    letter-spacing: 0.01em;
    color: #1F2937;
    margin: 10px 0px;
}

</style>
