<template>
  <section class="container">
  


    <div class="separator"></div>
    <h1 class="title">
     Hello. I'm <span><a target="_blank" href="https://www.linkedin.com/in/james-zaccardo-69772527/" class="name about">James Zaccardo</a></span>, a full stack web developer based in Los Angeles.

    </h1>
    <br />
    <h1 class="title">
     I've been making modern, elegant websites and apps for 6+ years. Check out some of my <span><nuxt-link class="link about" to="/work">past work</nuxt-link></span>.
     
    </h1>
    <br />
    <h1 class="title">
     Have a project? <span><nuxt-link class="link about" to="/contact">Let's talk</nuxt-link></span>.
    </h1>
  
 
  </section>
 
</template>

<style scoped>
.about {
position: relative;
}
.about:after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  height: 4.3px;
  width: 0%;
background-image:linear-gradient(to top, #cfd9df 0%, #e2ebf0 100%);
  -webkit-transition: all 0.2s linear;
  -moz-transition: all 0.2s linear;
  -ms-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  transition: all 0.2s linear;
}

.about:hover:after {
  width: 100%;
}


.title
{
  margin: 25px 0;
  font-weight: 200;
  letter-spacing: 1px;
}
@media (max-width: 500px) {
    .title {
      font-size: 1.5em;
      letter-spacing: 1.2px;
      font-weight: 300;
      margin-top:20px 0;
      
    }
}

.title span {
  font-weight: 500;
  color: #2196F3;
}


</style>
