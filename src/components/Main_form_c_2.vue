<template>
    <div class="grid grid-cols-6 gap-1" id="col_2">
                    <div class="col-span-1" id="ethprice">ETH price</div>
                    <div class="col-span-5" id="num">0</div>

    </div>
</template>
<script>
export default {
     name:"Main_dorm_c_2"
}
</script>
<style scoped>
#col_2{
    flex-direction: column;
    align-items: flex-start;
    padding: 10px 20px 10px 15px;
    margin: 5px 0px 15px 0px;
    /* position: absolute; */
    width: 378px;
    height: 50px;
    left: 0px;
    top: 100px;
    background: #F7F7F9;
    border-radius: 10px;
}
#ethprice{
    width: 77px;
    height: 30px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 30px;
    letter-spacing: 0.01em;
    color: #9CA3AF;
    margin: 0px 0px;
}
#num{
  position: static;
    width: 77px;
    height: 30px;
    left: 0px;
    top: 0px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 30px;
    letter-spacing: 0.01em;
    color: #9CA3AF;
    margin: 0px 0px 0 266px;
}
</style>