<template>
    <div>
        <button id="transfer">Transfer</button>
    </div>
</template>
<script>
export default {
    name: "Bottom_btn"
}
</script>
<style scoped>
#transfer{
  display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 10px 15px;

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