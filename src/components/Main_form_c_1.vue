<template>
           <div id="col_1">
                <div class="grid grid-cols-12 gap-1">
                    <div class="col-span-11" id="youPay">You pay</div>
                    <div class="col-span-1" id="max">Max</div>

                </div>
                

            <div class="grid grid-cols-6 gap-1">
                    <div class="col-span-1" id="eth">ETH</div>
                    <div class="col-span-5" id="num">0.0</div>

                </div>

            </div>
</template>
<script>
export default {
    name:"Main_dorm_c_1"
}
</script>
<style scoped>
#col_1{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 15px 20px 15px 15px;
    margin: 5px 0px;
    width: 378px;
    height: 90px;
    left: 0px;
    top: 0px;
    background: #F7F7F9;
    border-radius: 10px;
}

#eth{
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 10px;
    width: 101px;
    height: 40px;
    background: #FFFFFF;
    border-radius: 10px;
}
#youPay{
    width: 303px;
    height: 10px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 12px;
    line-height: 10px;
    letter-spacing: 0.01em;
    color: #9CA3AF;
    margin: 0px 10px;
}
#max{
    position:relative;
    width: 30px;
    left: calc(50% - 30px/2);
    top: 0%;
    bottom: 0%;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 30px;
    display: flex;
    align-items: center;
    color: #9CA3AF;
    flex: none;
    order: 0;
    flex-grow: 1;
    margin: -10px 0px 0px 0px;
}
#num{
    margin: -10px 0px 0px 0px;
    height: 40px;

    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 26px;
    line-height: 40px;
    text-align: right;
    letter-spacing: 0.01em;
    color: #D1D5DB;
    flex: none;
    order: 1;
    flex-grow: 1;
    margin: 0px -5px 0 0;
}
</style>