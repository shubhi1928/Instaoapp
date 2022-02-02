<template>
<div id="header">
   <img id="logo" src="../assets/Logo.png">
    <div id="text"><p >Logoooo</p></div>
</div>
    
</template>
    
<script>

    export default {
      name: "Top",
      components: {

      }
    }
</script>
    
<style lang="css" scoped>
#header {
  
  width: 1440px;
  height: 80px;
  left: 0px;
  top: 0px;
  background: rgba(255, 255, 255, 0.0001);
  border-radius: 20px 20px 0px 0px;

}

#logo{
  float: left;
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
      padding: 0px 1px 1px 0px;
      margin:20px 7.5px 20px 60px;

      position: static;
      width: 40px;
      height: 40px;
      left: 0px;
      top: 0px;

      background: #A78BFA;
      border-radius: 30px;

  
}

#text{
  float: left;
  position: static;
width: 96px;
height: 30px;
left: 55px;
top: 5px;

font-family: Inter;
font-style: normal;
font-weight: bold;
font-size: 22px;
line-height: 30px;
/* identical to box height, or 136% */

letter-spacing: 0.01em;

/* Gray/800 */

color: #1F2937;


/* Inside auto layout */

flex: none;
order: 1;
flex-grow: 0;
margin: 25px 7.5px;
}

</style> 