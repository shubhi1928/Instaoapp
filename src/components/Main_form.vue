<template>
        <div id="fill">
            <div class="grid grid-cols-12 gap-2" id="upper_text">
                <div class="col-span-10" id="limit">Limit Order Swap</div>
                <div class="col-span-2 "> <a href=""><img id="reload" src="../assets/Component 1.png"></a> </div>
            </div>
            
            <Main_form_c_1/>
            <Main_form_c_2/>
            <img id="image" src="../assets/Frame 427320255.png">
            <Main_form_c_3/>

         

              </div>
</template>
<script>
import Main_form_c_1 from "../components/Main_form_c_1.vue"
import Main_form_c_2 from "../components/Main_form_c_2.vue"
import Main_form_c_3 from "../components/Main_form_c_3.vue"
export default {
    name:"Main_form",
    components: {
           Main_form_c_1,
           Main_form_c_2,
           Main_form_c_3,
    }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
#fill{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 12px 20px 0px 20px;

    width: 418px;
    height: 327px;
    background: #FFFFFF;
    border-radius: 14px;
    margin: 20px 0px;
}

#upper_text{
  margin:10px 0px 0px 0px;
}
#limit{
    width: 318px;
    height: 30px;
    font-family: Inter;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 30px;
    letter-spacing: 0.01em;
    color: #1F2937;
    margin: 0px 10px;
}

#reload{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 0px;
    width: 50px;
    height: 30px;
    background: #F7F7F9;
    border-radius: 8px;
    margin: 0px 10px;
}


#col_3{
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 15px 20px 15px 15px;

/* position: absolute; */
width: 378px;
height: 90px;
left: 0px;
top: 170px;

/* Gray/100 */

background: #F7F7F9;
border-radius: 10px;
}
#image{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 0px;

position: absolute;
width: 36px;
height: 36px;
left: 191px;
top: 320.5px;

/* Gray/100 */

background: #F7F7F9;
/* White/0 */

border: 4px solid #FFFFFF;
border-radius: 20px;

/* Inside auto layout */

flex: none;
order: 0;
flex-grow: 0;
margin: 0px 10px;
}


</style>
