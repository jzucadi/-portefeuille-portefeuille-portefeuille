<template>
  <section class="container">
    <h1 class="title">Recent Work</h1>
    <section class="demo">
      <div class="grid__col grid__col--2-of-5">
        <div class="ava">
          <h2 class="work">Avalara</h2>
          <p class="blurb">Developed US, UK, and Indian website portals. Redesigned development workflow to handle legacy refractoring and unit testing. Created node, jquery, and PHP plugins.</p>
          <br /><div class="separator"></div>
          <p class="blurb">Javascript, ES6, Composer, Vue, PHP, Wordpress API, Laravel, SCSS, PostCSS, Python</p>
          <br /><a target="_blank" href="https://www.avalara.com/" class="button btn">
            Visit Site
          </a>
        </div>
      </div>
      <div class="grid__col grid__col--3-of-5">
         <img src="../assets/img/dd.png" alt="avalara" class="cat" />
        
      </div>
    </section>
     <section class="demo enu">
      <div class="grid__col grid__col--2-of-5">
        <div class="ava">
          <h2 class="work">Georgetown University</h2>
          <p class="blurb">Developed graduate school website and custom CMS for faculty use. Created REST APIs solutions for online course portals.</p>
          <br /><div class="separator"></div>
          <p class="blurb">Javascript, PHP, Django, MySQL, CSS, LESS, Python</p>
          <br /><a target="_blank" href="https://scs.georgetown.edu/" class="button btn">
            Visit Site
          </a>
        </div>
      </div>
      <div class="grid__col grid__col--3-of-5">
         <img src="../assets/img/gu.png" alt="scs" class="cat" />
        
      </div>
    </section>
    <section class="demo enu">
      <div class="grid__col grid__col--2-of-5">
        <div class="ava">
          <h2 class="work">Joyable</h2>
          <p class="blurb">Developed custom React components and GraphQL integration for website redesign.</p>
          <br /><div class="separator"></div>
          <p class="blurb">Javascript, ES6, React, SCSS, Pug, MongoDB, GraphQL</p>
          <br /><a target="_blank" href="https://www.joyable.com/" class="button btn">
            Visit Site
          </a>
        </div>
      </div>
      <div class="grid__col grid__col--3-of-5">
         <img src="../assets/img/joy.png" alt="joyable" class="cat" />
        
      </div>
    </section>
    <section class="demo enu">
      <div class="grid__col grid__col--2-of-5">
        <div class="ava">
          <h2 class="work">Plastiq</h2>
          <p class="blurb">Developed custom Angular components for customer login and administrative dashboard. Designed prototypes and created interactive digital styleguide.</p>
          <br /><div class="separator"></div>
          <p class="blurb">Javascript, ES6, Angular, MongoDB, PostCSS, Python</p>
          <br /><a target="_blank" href="https://www.plastiq.com/" class="button btn">
            Visit Site
          </a>
        </div>
      </div>
      <div class="grid__col grid__col--3-of-5">
         <img src="../assets/img/pl.png" alt="plastiq" class="cat" />
        
      </div>
    </section>
    <section class="demo enu">
      <div class="grid__col grid__col--2-of-5">
        <div class="ava">
          <h2 class="work">Promundo</h2>
          <p class="blurb">Developed website redesign and custom REST APIs. Created node, jquery, and PHP plugins.</p>
          <br /><div class="separator"></div>
          <p class="blurb">Javascript, PHP, Drupal, SCSS</p>
          <br /><a target="_blank" href="http://promundoglobal.org/" class="button btn">
            Visit Site
          </a>
        </div>
      </div>
      <div class="grid__col grid__col--3-of-5">
         <img src="../assets/img/pr.png" alt="promundo" class="cat" />
        
      </div>
    </section>
     <section class="demo enu">
      <div class="grid__col grid__col--2-of-5">
        <div class="ava">
          <h2 class="work">German Marshall Fund</h2>
          <p class="blurb">Developed website redesign and created online digital style guide. Created node, jquery, and PHP plugins.</p>
          <br /><div class="separator"></div>
          <p class="blurb">Javascript, CSS, PHP, Drupal, Python</p>
          <br /><a target="_blank" href="http://gmfus.org" class="button btn">
            Visit Site
          </a>
        </div>
      </div>
      <div class="grid__col grid__col--3-of-5">
         <img src="../assets/img/gmf.png" alt="gmf" class="cat" />
        
      </div>
    </section>
  </section>
</template>

<style scoped>

.ava {
  margin: 0px auto;
}
.blurb {
  font-size: 1.5em;
  color: #bbb;
  font-weight: 200;
  letter-spacing: 1px
}
@media (max-width: 500px) {
    .blurb {
      font-size: 1.2em;
    }
}
.work {
  font-weight: 700;
  letter-spacing: 2px;
  font-size: 2.4em;
  margin: 0;
  color: #2196F3;
}
@media (max-width: 500px) {
    .work {
      font-size: 2em;
    }
}
.cat {
  max-width:90%;
  background: #FFFFFF;
  box-shadow: 0 20px 40px 0 rgba(33, 135, 243, 0.23);
  border-radius: 6px;
  float: right;
}
@media (max-width: 500px) {
    .cat {
      float:none;
      margin-top: 60px;
      max-width: 95%;
      

    }
}
@media (max-width: 1000px) {
    .cat {
      margin-top: 50px;
    }
}
@media (max-width: 700px) {
    .cat {
      float:none;
    }
}
.enu {
  padding-top: 70px;
}

.demo {
  min-height: 100%;
  width: 100%;
  margin: 60px auto;
  padding-bottom: 100px;
}

@media (max-width: 500px) {
    .demo {
      padding-bottom: 15px;
      margin: 10px auto;
    }
}

.title
{
  margin: 50px 0;
}


</style>
