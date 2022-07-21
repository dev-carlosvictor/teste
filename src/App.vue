<template>
<div id="principal">
  <Header/>
 <News/>
 <Articles/>
 <Footer/>
 </div>
</template>

<script>
import Header from './components/Header.vue'
import News from './components/News.vue'
import Articles from './components/Articles.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    Header,
    News,
    Articles,
    Footer,
    
  }
}
</script>


<style>
 * {
     margin: 0 auto;
     padding: 0 0 0 0;
 }
</style>

