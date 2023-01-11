<template>
  <NavBar/>
  <router-view/>
  <FooterVue/>
 
  
</template>

<script>
  import NavBar from '@/components/NavBar.vue'
  import FooterVue from '@/components/FooterVue.vue'
  export default{
    name: 'App',
    components:{
      NavBar,
      FooterVue
    }
  }
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  overflow: hidden;
  /* background-image: url("https://i.postimg.cc/GtbPbhZS/Background-image.jpg"); */
  background-repeat: no-repeat;
  background-size: cover;
  background-color: black;
}
*,::after,::before{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

nav {
  padding: 0;
} 

nav a {
  /* font-weight: bold; */
  color: blueviolet;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: purple;
}

.wrapper{
  background-color: whitesmoke;
  width: 100vw;
  height:fit-content;
  overflow: hidden;
  margin-top: 1.7rem;
}
</style>
