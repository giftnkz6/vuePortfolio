<template>
   <ResumeVue/>
</template>

<script>
import ResumeVue from '@/components/ResumeVue.vue';
    export default{
        name: 'ResumeView',
        components:{
            ResumeVue
        }
    }
</script>

<style scoped>
    .resume-wrapper{
    text-align: center;
    border-style: dashed;
    border-radius: 10%;
    border-color: black;
    width: 235px;
    height: 215px;
    border-radius: 100px / 50px;
    box-sizing: border-box;
    padding-top: 20px;
    margin:auto;
    margin-bottom: 3%;
    color: black;
    animation-name: color-anim;
    animation-duration: 4s;
    animation-iteration-count: infinite;
    background-color: white;
}
</style>