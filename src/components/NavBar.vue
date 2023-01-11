<template>
    <header>
        <nav class="navbar navbar-expand-lg w-100">
            <div class="container-fluid">
                <a href="#home"><img class="logo" src="https://i.postimg.cc/W49jGVRq/Gift-Logo.png" alt="logo"></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li><a href="#home"><i class="fa-solid fa-house-user fa-flip" style="--fa-animation-duration: 3s;"></i></a><router-link to="/">Home</router-link></li>
                        <li><a href="#about"><i class="fa-solid fa-address-card fa-flip" style="--fa-animation-duration: 3s;"></i></a><router-link to="/about">About</router-link></li>
                        <li><a href="#resume"><i class="fa-solid fa-file fa-flip" style="--fa-animation-duration: 3s;"></i></a><router-link to="/resume">Resume</router-link></li>
                        <li><a href="#project"><i class="fa-solid fa-diagram-project fa-flip" style="--fa-animation-duration: 3s;"></i></a><router-link to="/project">Project</router-link></li>
                        <li><a href="#skills"><i class="fa-solid fa-screwdriver-wrench fa-flip" style="--fa-animation-duration: 3s;"></i> Skills</a></li>
                        <li><a href="#testimonial"><i class="fa-sharp fa-solid fa-people-group fa-flip" style="--fa-animation-duration: 3s;"></i></a><router-link to="/testimonial">Testimonial</router-link></li>
                        <li><a href="#contact"><i class="fa-solid fa-phone fa-flip" style="--fa-animation-duration: 3s;"></i></a><router-link to="/contact">Contact</router-link></li>
                    </ul>
            
                </div>
            </div>
        </nav>
    </header>
</template>

<script>
    export default{
        name: 'NavBar'
    }
    
</script>
<style scoped>
    nav{
        background-color: whitesmoke;
    }
    a{
        color: blueviolet;
        font-size: larger;
    }
    li{
        margin: 1.5rem;
    }
    /* .navbar{
        height: 5rem;
    } */
    .logo{
        width: 4rem; 
    }
    .navbar-nav li{
    margin: 0 0.8rem;
}
.navbar {
    z-index: 3;
    background-color: white;
}

.navbar ul{
    font-size: 18px;
}
header{
    z-index: +3;
}
</style>