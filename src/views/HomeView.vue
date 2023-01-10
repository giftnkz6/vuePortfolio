<template>
    <div class="container mt-5">
        <div class="row">
            <div class="col" id="home-text">
                <h1>WELCOME TO MY PORTFOLIO</h1><br>
                <h1>I BUILD COOL AND AWESOME WEBSITES</h1>
                <h5>I am a software developer Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse fugiat sunt cupiditate illo odio rerum nulla unde, ullam ipsam. Consectetur atque nemo fuga commodi, soluta voluptatum! Ullam similique aperiam laboriosam.</h5>
            </div>
            <div class="col">
                <img src="https://i.postimg.cc/rsDxpqXC/Gift-Mahlangu.jpg" alt="Gift Profile">
            </div>
        </div>
    </div>
</template>

<script>
    export default{
        name: 'HomeView',
    }
</script>
<style scoped>
*,::after,::before{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
    img{
        width: 20rem;
        border-radius: 50%;
        height: 20rem;
        margin-top: 2rem;
    }
    #home-text{
        margin-top: 8rem;
    }
    /* h1,h5{
    
    } */
    /* .container{
        width: 100vw;
        height: 32rem;
        overflow: hidden;
        background-color: #3b64c9;
        margin: auto;
        margin-bottom: 4rem;
    } */
</style>
