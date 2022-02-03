<template>
<div id="page">
  <div class="sticky top-0">
     <Top />
</div>
<div id="main_body">
   <Main/>
</div>

</div>

</template>

<script>
import Top from './components/Top.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Top,
    Main,
  },
}
</script>

<style>
::-webkit-scrollbar {
  display: none;
}

body{
 background: #EDE9FE; ;
}
#page{
position: relative;
height: 900px;
width:1500px;
background: #EDE9FE;
border-radius: 20px;
}
#main_body{
    display: flex;
    justify-content: center;
}

</style>
