<template>
  <nav>
    <navbar/>
    
    
  </nav>

  <router-view/>
 <footer-comp/>

  

</template>

<style>
*{
    margin: 3.5px;
    padding: 0;
    box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  font-size: large;
}

nav a.router-link-exact-active {
  color: #424eb9;
}

body {
    background-image: url('https://i.postimg.cc/9QCch4Fj/stars-galaxy.gif');
}
.ml1 {
    
    font-weight: 900;
    /* font-size: 3.5em; */
  }
  
  .ml1 .letter {
    display: inline-block;
    line-height: 1em;
  }
  
  .ml1 .text-wrapper {
    position: relative;
    display: inline-block;
    padding-top: 0.1em;
    padding-right: 0.05em;
    padding-bottom: 0.15em;
  }

  .text-wrapper{
    animation: shrink-grow 3s infinite;
  }

  @keyframes shrink-grow {
    0%{
        font-size: small;
    }
    100% {
        font-size: 32px;
    }
  }
  
  .ml1 .line {
    opacity: 10;
    position: absolute;
    left: 0;
    height: 3px;
    width: 100%;
    background-color: #fff;
    transform-origin: 0 0;
  }
  
  .ml1 .line1 { top: 0; }
  .ml1 .line2 { bottom: 0; }
  
</style>
<script>
import HelloWorld from '@/components/navbar.vue';
import navbar from '@/components/navbar.vue';
import footerComp from '@/components/footer.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld, navbar, footerComp
  }
}

</script>