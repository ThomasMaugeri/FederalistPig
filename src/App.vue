<script>
 import Header from './components/header.vue'
 import mainimg from './components/mainimg.vue'
 import news from './components/news.vue'
 import shortcut from './components/shortcut.vue'
 import Appfooter from './components/Appfooter.vue'

 export default{
  components:{Header,mainimg,news,shortcut,Appfooter}
  }
</Script>

<template>
 <div>
  <Header/>
  <mainimg/>
  <news/>
  <shortcut/>
  <Appfooter />


 </div>
</template>  

<style scoped>



</style>