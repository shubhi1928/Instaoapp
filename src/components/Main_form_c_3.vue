<template>
       <div id="col_3">
                <div class="grid grid-cols-12 gap-1">
                    <div class="col-span-6" id="youRecieve">You Recieve</div>
                    <div class="col-span-6" id="conversion">1 USDC = 0.00038 ETH</div>

                </div>
                <div class="grid grid-cols-6 gap-1">
                    <div class="col-span-1" id="usdc">USDC</div>
                    <div class="col-span-5" id="numusdc">0.0</div>

                </div>
        </div>
</template>
<script>
export default {
    name:"Main_dorm_c_3"
}
</script>
<style scoped>
#usdc{
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 10px;
    width: 101px;
    height: 40px;
    background: #FFFFFF;
    border-radius: 10px;
    margin: 0px 0px;
}
#numusdc{
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
    margin: 0px -5px 0 0;
}

#youRecieve{
    width: 196px;
    height: 10px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 12px;
    line-height: 10px;
    letter-spacing: 0.01em;
    color: #9CA3AF;
    margin: 0px 10px 10px 0;
}
#conversion{
    width: 137px;
    height: 10px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 12px;
    line-height: 10px;
    text-align: right;
    letter-spacing: 0.01em;
    color: #9CA3AF;
    margin: 0px 0px 0 40px;
}
</style>