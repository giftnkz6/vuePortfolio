<template>
    <div>
        <h1 class="display-1">RESUME</h1>
        <div v-for="info in resume" key="info">
            <div class="resume-wrapper">
                <p>{{ info.information }}</p>
            </div>
        </div>
    </div>
    <section id="skills" class="container-fluid rounded-4">
            <h2 class="scroll display-2">Skills</h2>
            <div id="contain" class="container ">
                <p>HTML</p>
                <div class="progress">
                    <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-label="Default striped example" style="width: 95%" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100">95%</div>
                  </div><br>
                  <p>CSS</p>
    
                  <div class="progress">
                    <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" role="progressbar" aria-label="Success striped example" style="width: 75%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">75%</div>
                  </div><br>
                  <p>Javascript</p>
                  <div class="progress">
                    <div class="progress-bar progress-bar-striped progress-bar-animated bg-info" role="progressbar" aria-label="Info striped example" style="width: 70%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">70%</div>
                  </div><br>
                  <p>Bootstrap</p>
                  <div class="progress">
                    <div class="progress-bar progress-bar-striped progress-bar-animated bg-warning" role="progressbar" aria-label="Warning striped example" style="width: 68%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">63%</div>
                  </div><br>
                  <p>C++</p>
                  <div class="progress">
                    <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" role="progressbar" aria-label="Danger striped example" style="width: 65%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100">65%</div>
                  </div><br>


            </div>
        </section>
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
    color: blueviolet;
    animation-name: color-anim;
    animation-duration: 4s;
    animation-iteration-count: infinite;
    /* background-color: white; */
}
p{
    color: purple;
}
#skills{
    margin-top: 5%;
    margin-bottom: bottom;
}
#skills .container {
    width: 40%;
    background-color: white;
}
@media screen and (max-width: 680px){
    #skills .container{
        min-width: 15em;
    }
    

}
</style>