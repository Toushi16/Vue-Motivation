<template>

  <div id="app">
    
    <div>

      <Header/>
      <MainSection1/>
      <MainSection2/>
      <MainSection3/>
      <ClientSection/>
      <Carousel/>
      <BlogsUpdate/>
      <Footer/>
      
    </div>

  </div>

</template>

<script>

import Header from './components/MainHeader.vue'
import MainSection1 from './components/MainSection1.vue'
import MainSection2 from './components/MainSection2.vue'
import MainSection3 from './components/MainSection3.vue'
import ClientSection from './components/ClientCard.vue'
import Carousel from './components/MainCarousel.vue'
import BlogsUpdate from './components/MainBlogs.vue'
import Footer from './components/MainFooter.vue'

export default {

  name: 'App',

  components: {
    Header,
    MainSection1,
    MainSection2,
    MainSection3,
    ClientSection,
    Carousel,
    BlogsUpdate,
    Footer,
  }
}

</script>

<style lang="scss">

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}



#app {
  
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

ul {
  list-style: none;
  color: currentColor;
}

</style>
