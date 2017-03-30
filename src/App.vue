<template>
  <div id="app">

    <nav>
      <div class="nav-wrapper #424242 grey darken-3">
        <a href="#" class="brand-logo">Jason Zmuda</a>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
          <li><a href="#about">About</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>

    <div class="parallax-container">
      <h2 class="top-parallax">let jasonZmuda = { };</h2>
      <div class="parallax"><img :src="images.Stars">
      </div>
    </div>
    <div class="section #424242 grey darken-3">
      <div class="row container">
        <a name="about"></a>
        <About></About>
      </div>
    </div>
    <div class="parallax-container">
      <a name="portfolio"></a>
      <Portfolio></Portfolio>
      <!--<h2>jason.Zmuda.portfolio = {</h2>-->
      <h2> }</h2>
      <div class="parallax"><img :src="images.forest">
      </div>
    </div>
    <div class="section #424242 grey darken-3">
      <div class="row container">
        <a name="contact"></a>
        <Contact></Contact>
      </div>
    </div>
  </div>
</template>

<script>
  import Contact from './components/Contact'
  import About from './components/About'
  import Portfolio from './components/Portfolio'
  import forestImage from "./assets/treebranch.jpg"
  import mountain from "./assets/mountain.jpg"
  import NightSky from "./assets/nightsky.jpg"
  import Stars from "./assets/stars.jpg"

  export default {
    name: 'app',
    components: {
      About,
      Portfolio,
      Contact
    },
    data() {
      return {
        msg: 'Welcome to Your Vue.js App',
        images: {
          forest: forestImage,
          mountain: mountain,
          NightSky: NightSky,
          Stars: Stars
        }
      }
    },
    mounted() {
      $('.parallax').parallax();
    }
  }

</script>

<style>
  #app {
    /*color: white;*/
    /*font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;*/
  }
  
  .top-parallax {
    margin-top: 10%;
    margin-left: 10%;
    color: white;
  }
</style>