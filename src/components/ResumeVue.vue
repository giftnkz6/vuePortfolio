<template>
    <div>
        <h1>RESUME</h1>
        <div v-for="info in resume" key="info">
            <div class="resume-wrapper">
                <p>{{ info.information }}</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default{
        name: 'ResumeVue',
        data(){
            return {
                resume:[
                    {
                    id:1,
                    information: "On 16 April 2022 I got a Responsive Web Design certificate from FreeCodeCamp Which covers HTML, CSS, Web design and Responsive Web."
                },
                {
                    id:2,
                    information: "In 2017 I was enrolled for a Bsc in Computer Sciences at University Of Pretoria. I partially completed the degree due to some unforseen circurmstances and financial challenges."
                },
                {
                    id:3,
                    information: "In 2015 I obtained my matric certificate at Kwandebele Science Combined School. I achieved a bachelors pass, with Pure Mathematics and Sciences beign one of the passed subjects."
                }
                
            ]
            }
        }
    }
</script>

<style scoped>
    .resume-wrapper{
    text-align: center;
    border-style: dashed;
    border-radius: 10%;
    /* border-color: black; */
    width: 245px;
    height: 215px;
    border-radius: 100px / 50px;
    box-sizing: border-box;
    padding-top: 20px;
    padding-left: 15px;
    padding-right: 15px;
    margin:auto;
    margin-bottom: 3%;
    /* color: black; */
    color: white;
    animation-name: color-anim;
    animation-duration: 4s;
    animation-iteration-count: infinite;
    /* background-color: white; */
}
</style>