<script>
 import Header from './components/header.vue'
 import mainimg from './components/mainimg.vue'
 import news from './components/news.vue'
 import shortcut from './components/shortcut.vue'
 import footer from './components/footer.vue'

 export default{
  components:{Header,mainimg,news,shortcut,footer}
  }
</Script>

<template>
 <div>
  <Header/>
  <mainimg/>
  <news/>
  <shortcut/>
  <footer />


 </div>
</template>  

<style scoped>



</style>