<template>
  <header>
     <div class="wrap"> 
      <nav>
        <h4>j<span>.</span>z<span>.</span></h4>
        <ul>
          <li><nuxt-link class="navi" to="/">
            About
          </nuxt-link></li>
          <li><nuxt-link class="navi" to="/work">
            Work
          </nuxt-link></li>
          <li><nuxt-link class="navi" to="/contact">
            Contact
          </nuxt-link></li>
        </ul>
      </nav>
      </div>
  </header>
</template>
<style>
.navi{
  font-size: 1.7em;
  font-weight: 300;
  
  position: relative;
  
}
.navi:after {
  content: '';
  position: absolute;
  bottom: -3px;
  left: 0;
  height: 2px;
  width: 0%;
 background-image:linear-gradient(to top, #cfd9df 0%, #ccc 100%);
  -webkit-transition: all 0.2s linear;
  -moz-transition: all 0.2s linear;
  -ms-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  transition: all 0.2s linear;
}

.navi:hover:after {
  width: 100%;
}


h4 {
    font-weight: 800;
    font-size: 3em;
    color: rgba(96, 125, 139, 0.42);
}
h4 span {
  color: rgba(33, 150, 243, 0.86);
  
}
nav {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  height: 70px;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
}
nav ul {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  list-style: none;
}
nav ul li {
  margin-left: 10px;
  margin: 20px;
      
}
.wrap{
      padding-left: 30px;
    padding-right: 25px;
  max-width: 1400px;
  margin: 35px auto 0px auto;
}
@media (max-width: 500px) {
    .navi {
      font-size: 1.2em;
      font-weight: 500;
    }
}
@media (max-width: 500px) {
    .wrap {
      margin: 15px auto 0px auto;
    }
}
@media (max-width: 500px) {
    nav ul li {
    margin-left: 6px;
    margin-top: 32px;
}
}
@media (max-width: 500px) {
    h4 {
    font-size: 2.5em;
}
}
</style>

