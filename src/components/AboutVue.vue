<template>
    <section class="container" id="about">
            <h1>About Me</h1>
            <div class="container">
                <div class="row">
                    <div class="col-md-8">

                        <figure id="about-container">
                            <img class="image-about img-fluid rounded-4" src="https://i.postimg.cc/rsDxpqXC/Gift-Mahlangu.jpg6" alt="profile">
                        </figure>

                    </div>
                    <div class="col">
                        
                        <div id="about-text" class="container">
                            <h2>HELLO THERE!</h2>
                            <p>My name is Gift Mahlangu, I am an aspiring software developer.
                                I am currently enrolled in a 1 year program at Life Choices 
                                Academy. I am passionate about tech and coding and I enjoy playing
                                soccer and video games and I am a kind and respectful person.  
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {
    name: 'AboutVue'
}
</script>

<style scoped>
/* About inline */
#home,#about,
#contact,#skills,
#testimonial,#project,#resume{
    scroll-margin-block-start: 80px;
}
#about figure{
    display: flex;
    justify-content: center;
}
/* About image */
#about-container img{
    width: 22em;
    box-shadow: 0 0 25px white;
}
h1{
    color: black;
}
#about h2{
    color: blueviolet;
    text-shadow: 2px 1px white;
}
#about-container .image-about{
    width: 20rem
}

#about-text{
    border-radius: 4px;
    box-shadow: 0 0 10px #c1c1c1;
    margin-top: 25%;
    /* background-color: azure; */
    background-color: #fff;
}

#about-text p{
    color: white;
    font-size: large;
    color: black;
}
#about-text h3{
    color: blueviolet;
}
#about{
    margin-bottom: 4%;
}

</style>