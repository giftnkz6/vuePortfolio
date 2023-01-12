<template>
    <AboutVue/>
</template>

<script>
import AboutVue from '@/components/AboutVue.vue'
export default {
    name: 'AboutView',
    components:{
        AboutVue
    }
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
#about h2{
    color: blueviolet;
}
#about-container .image-about{
    width: 20rem
}

#about-text{
    border-radius: 4px;
    box-shadow: 0 0 10px #c1c1c1;
    margin-top: 25%;
    /* background-color: azure; */
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