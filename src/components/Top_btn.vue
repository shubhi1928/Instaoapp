<template>
      <div class="grid grid-cols-2"  id="top_button"> 
             <div id="box_1">Deposit</div>
             <div id="box_2">My orders</div>
        </div>
</template>
<script>
export default {
    name:"Top_btn"
}
</script>
<style scoped>
#top_button{
    position: absolute; 
    display: flex;
    justify-content: center;
    width: 468px;
    height: 56px;
    top: 0px;

    background: #F5F3FF;
    border-radius: 16px;
    margin: 10px 0px;
}

#box_1{
    display: flex;
    justify-content: center;
    width: 222px;
    height: 40px;
    align-items: center;
    margin: 8px;
    background: #FFFFFF;
    border-radius: 12px;
}
#box_2{
    display: flex;
    justify-content: center;
    width: 222px;
    height: 40px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    margin: 8px;
    align-items: center;
    letter-spacing: 0.01em;
    color: #1F2937;
}
</style>
