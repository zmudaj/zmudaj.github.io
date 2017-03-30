<template>

  <div class="about">
      <h3>jasonZmuda.about = {</h3>
      <div class="row">
        <div class="col s12 m3">
          <img class="portfolio-pic" :src="images.portfolio">
        </div>
        <div class="col s12 m9">
          <p class="about-text">After three years of intensive education and hands on experience, I am very excited to start my career as a professional software developer.  
            </p>
            <p class="about-text">My journey began when I enrolled in a technical writing program to expand my skill set. This exposed me to base level development tools and techniques, which led to independent research and study through online tutorials. With this foundation in place I returned to school to pursue a computer science degree. After a year and a half of intensive academic study I had a solid foundation of software engineering principles and concepts. I next attended Boise Codework’s Full Stack Development program to give me daily, hands on experience in a real-world setting.   
            </p>
            <p class="about-text">The combination of university classes, independent research and an immersive code camp have shaped me into a very well rounded and flexible developer. My previous career as a contract specialist sharpened my customer and user experience focus as well as honing my critical thinking and communication skills. At this point I cannot wait to put all these skills to use in a professional setting and launch my official career.
              </p>
              <p class="about-text">If I’m not programming, you’ll probably find me at the zoo with my family or playing restaurant with my two and four year old. I love to play strategy board, card and video games when I can and have a lifelong passion for designing board games. 
            </p>
            <h3>};</h3>
          </div>
      </div>
      

  </div>
</template>

<script>
  import headshot from "../assets/headshot.jpg"
  export default {
    name: 'about',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App',
        images: {
          portfolio: headshot
        }
      }
      // },
      // mounted(){
      //   $('.parallax').parallax();
      // }
    }
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  /*body {
  background:url("https://s-media-cache-ak0.pinimg.com/originals/a7/5f/dc/a75fdcab110ae11f155ed96f428a86ae.png")
}*/

body {
  color: white;
}
  
  .portfolio-pic {
    max-width: 175px;
    border-radius: 10%;
    margin-top: 10%;
  }

  .about-text {
    margin-left: 15px;
  }
  
  h1,
  h2 {
    font-weight: normal;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  li {
    display: inline-block;
    margin: 0 10px;
  }
  
  a {
    color: #42b983;
  }
</style>