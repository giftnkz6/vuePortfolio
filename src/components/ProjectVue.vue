<template>
    <h1>My Projects</h1>
    <div class="container">
      <div id="carouselExampleControls" class="carousel slide" data-interval="false">
        <div class="carousel-inner">
          <div class="carousel-item active" v-for="project in firstProject" key="project">
            <div class="card" style="width: 18rem;">
                <img :src="project.image" class="d-block w-100" alt="..." loading="lazy">
                <div class="card-body">
                    <h5 class="card-title">{{ project.description }}</h5>
                    <a :href="project.github" class="btn btn-primary">Github</a><br><br>
                    <a :href="project.netlify" class="btn btn-primary">Netlify</a>
                </div>
            </div>
          </div>
          <div class="carousel-item" v-for="project in projects" key="project">
            <div class="card" style="width: 18rem;">
                <img :src="project.image" class="d-block w-100" alt="..." loading="lazy">
                <div class="card-body">
                    <h5 class="card-title">{{ project.description }}</h5>
                    <a :href="project.github" class="btn btn-primary">Github</a><br><br>
                    <a :href="project.netlify" class="btn btn-primary">Netlify</a>
                </div>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
      </div>
</div>
</template>

<script>
export default {
    name: 'ProjectVue',
    data(){
        return{
            firstProject:[{
                id:1,
                description:"E-commerce",
                image:"https://i.postimg.cc/G3NksBKn/Screenshot-20230112-101713.png",
                github: "https://github.com/giftnkz6/E-Commerce.git",
                netlify: "https://giftsneakerhub.netlify.app"

            }],
            projects:[
            {
                id:2,
                description:"Calculator",
                image:"https://i.postimg.cc/MGm0LR4f/Screenshot-20230112-112156.png",
                github: "https://github.com/giftnkz6/JavaScript-Calculator-.git",
                netlify: "https://calculator-by-gift-mahlangu.netlify.app"
            },
            {
                id:3,
                description:"Bootstrap-Portfolio",
                image:"https://i.postimg.cc/xCHJXbDT/Screenshot-20230112-112412.png",
                github: "https://github.com/giftnkz6/portfolio.git",
                netlify: "https://gift-portfolio.netlify.app"
            },
            {
                id:4,
                description:"Counting Characters",
                image:"https://i.postimg.cc/7LqY2jbW/Screenshot-20230113-105901.png",
                github: "https://github.com/giftnkz6/Second-Group-App.git",
                netlify: "https://second-group-app.netlify.app"
            },
            {
                id:5,
                description:"E-commerce-Exercise",
                image:"https://i.postimg.cc/SRKjB3cP/Screenshot-20230113-111903.png",
                github: "https://github.com/giftnkz6/E-commerce-Exercise.git",
                netlify: "https://giftecommerce.netlify.app"
            },
            {
                id:6,
                description:"Flip Card",
                image:"https://i.postimg.cc/MG6pgg08/Screenshot-20230113-113432.png",
                github: "https://github.com/giftnkz6/Week4flipcard.git",
                netlify: "https://flip-card-4.netlify.app"
            }
        ]
        }
    }
}
</script>

<style scoped>
    img{
        height: 20rem;
        object-fit: cover;
        object-position: top;
        width: 5rem;
    }
    .container{
        /* display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        margin: auto; */
        margin: auto;
    }
    .card{
        margin: auto;
        margin-top: 2rem;
        margin-bottom: 5rem;
        gap: 1rem;
        box-shadow: 0 0 25px purple;
    }
    /* Carousel */
    .carousel-control-next-icon {
        background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='white' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");
    }

    .carousel-control-prev-icon {
        background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='white' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");
    }
</style>