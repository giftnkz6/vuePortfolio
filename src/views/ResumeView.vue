<template>
    <div>
        <h1>RESUME</h1>
        <div class="resume-wrapper">
            <p>On 16 April 2022 I got a Responsive Web Design certificate from FreeCodeCamp.<br>
                Which covers HTML, CSS, Web design and Responsive Web.<br>
            </p>
        </div>
        <div class="resume-wrapper">
            <p>
                In 2017 I was enrolled <br>for a Bsc in Computer Sciences at 
                University Of Pretoria. I partially completed the degree due to some<br>
                unforseen circurmstances and financial challenges.
            </p>
        </div>
        
        <div class="resume-wrapper">
            <div>
                <p>In 2015 I obtained my <br>matric certificate at Kwandebele Science<br> Combined School.
                    I achieved a bachelors pass, with Pure Mathematics and Sciences beign one of the passed subjects.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
    export default{
        name: 'ResumeView'
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