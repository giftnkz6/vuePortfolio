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
  font-weight: bold;
  color: blueviolet;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: blue;
}

.wrapper{
  background-color: white;
  width: 100vw;
  margin-top: 1.7rem;
}

li{
  list-style: none;
}
/* ul{
  display: flex;
} */

</style>
