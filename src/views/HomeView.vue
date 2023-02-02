<template>
    <HomeVue/>
</template>

<script>
import HomeVue from '@/components/HomeVue.vue';
    export default{
        name: 'HomeView',
        components:{
            HomeVue
        }
    }
</script>
<style>
*,::after,::before{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
    /* img{
        width: 20rem;
        border-radius: 50%;
        height: 20rem;
        margin-top: 6rem;
    }
    #home-text{
        margin-top: 8rem;
    } */
    /* h1,h5{
    
    } */
    .container1{
        width: 100vw;
        height: 32rem;
        overflow: hidden;
        /* background-color: #3b64c9; */
        box-shadow: 0 0 25px #c1c1c1;
        margin: auto;
        margin-bottom: 4rem;
    }
    #home{
    margin-top: 5%;
    margin-bottom: 4%;
    scroll-margin-block-start: 100px;
}
.portfolio-h2{
    color: blueviolet;
    text-shadow: 2px 1px white;
}
/* Home image */
#home-image{
    box-shadow: 0 0 25px #c1c1c1;
    width: 28rem;
    animation-name: anim;
    animation-duration: 4s;
    animation-delay: -1;
    animation-iteration-count: 1;
}

/* Home animation */
#home-text{
    position: relative;
    width: 80vw;
    border-radius: 4px;
    box-shadow: 0 0 10px #c1c1c1;
    margin: auto;
    margin-top: 8em;
    animation-name: animations;
    animation-duration: 4s;
    /* animation-delay: 2s; */
    animation-iteration-count: 1;
    background-color: #fff;
    /* background-color: yellow; */
}
#home #home-text p{
    color: black;
    font-size: large;
    text-align: left;
}
/* #home-text{
    width: 40vw;
    margin-top: 12%;
} */
#home-heading{
    margin-bottom: 5%;
}
.home-container{
    display: grid;
    width: 80vw;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(4,2fr);
    justify-content: center;
    margin-top: 5em;
    
}
.home-img{
    position: relative;
    opacity: 0;
    animation-name: img-animation;
    animation-duration: 6s;
    animation-delay: 3s;
    animation-iteration-count: 1;
    animation-fill-mode: forwards;
    
}

@media screen and (width <= 767px) {
    img{
        margin-top: 2rem;
    }
    
}

@keyframes animations {
    0%   {top:-600px;}
    100% {top:0px;}
  }
  
  @keyframes color-anim {
    0%   {border:2px solid blueviolet; left:0px; top:0px;}
    25%  {border:2px solid yellow; left:0px; top:0px;}
    /* 50%  {border:2px solid blue; left:200px; top:200px; background-color: white;} */
    75%  {border:2px solid green; left:0px; top:200px;}
    100% {border:2px solid orange; left:0px; top:0px;}
  }
  
  @keyframes img-animation{
    0%   {right: -100%; opacity:0;}
    100% {right:0%; opacity:1;}
}

@keyframes appearing-animation{
    0%   {opacity:0;}
    100% {opacity:1;}
}
</style>
