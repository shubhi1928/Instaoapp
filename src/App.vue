<template>

<div id="page">
     <Top />
     <Main/>
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
#page{
position: relative;
width:1590px;
height: 1000px;

background: #EDE9FE;
border-radius: 20px;
}

</style>
