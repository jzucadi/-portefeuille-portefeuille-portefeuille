
<template>
  <div>
    <my-header/>
    <nuxt/>
    
    
    <my-footer/>
  </div>
</template>

<script>
import MyFooter from '~components/Footer.vue'
import MyHeader from '~components/Header.vue'

export default {
  components: {
    MyFooter,
    MyHeader
  }
}
</script>

<style>


.container
{
  max-width: 1440px;
  margin: 0 auto;
  padding: 100px 50px 100px 50px;
  text-align: left;
  flex: 1;
  min-height: calc(80vh - 2.1em - 3em);
  box-sizing: border-box;
}
@media (max-width: 500px) {
    .container {
      padding: 20px;
      margin-left: 10px;
    }
}




.button, .button:visited
{
  display: inline-block;
  color: white;
  letter-spacing: 1.5px;
  background-image: linear-gradient(120deg, #89f7fe 0%, #66a6ff 100%);
  text-decoration: none;
  padding: 15px 45px;
  letter-spacing: 1.5px;
  border-radius:30px;
  transition: all 0.5s ease 0s;
  box-shadow: 0 20px 40px 0 rgba(33, 150, 243, 0.25);
}

.button:hover, .button:focus
{
  color: #fff;
  background-color: #ccc;
  transform: translateY(-5px);
  transition: all 0.5s ease 0s;
  
  
}

.button:hover {
  box-shadow: 0 20px 40px 0 rgba(54, 151, 228, 0.55);
  background-image: linear-gradient(120deg, #49eaf4 0%, #4291ff 100%);
}


.title
{
  color:rgba(96, 125, 139, 0.79);
  font-weight: 300;
  font-size: 3.3em;
  margin: 0;
}
@media (max-width: 500px) {
    .title {
      font-size: 2.2em;
      margin: 20px 0;
    }
}
</style>
