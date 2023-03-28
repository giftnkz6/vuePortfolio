<template>
    <h1>Testimonials</h1>
    <div class="testimonial-container">
        <div v-for="testimonial in testimonials" key="testimonial">
            <div class="card" style="width: 18rem;">
                <img :src="testimonial.image" class="card-img-top" alt="..." loading="lazy">
                <div class="card-body">
                    <h5 class="card-title">{{testimonial.name}}</h5>
                    <p class="card-text">{{testimonial.message}}</p>
                </div>
            </div>
        </div>
        
    </div>
</template>

<script>
    export default{
        name: 'TestimonialVue',
        data(){
            return {
                testimonials:[
                    {
                    name: "Joel Mukanya - Lecturer",
                    message: "Gift is a very creative and well-behaved student. He is always there to assist others when they are struggling. Most importantly, he works well in a team as well as on his own. I believe he will make an excellent developer and would recommend him.",
                    image: "https://i.postimg.cc/TwpP1GY0/Joel-Mukanya.jpg" 
                },
                {
                    name: "Candice Amon - LIFE CHOICES ACADEMY FACILITATOR",
                    message: "Gift has a very likable spirit amongst his peers and lecturers. Has a very positive outlook on life. He does not allow his circumstances to bring him down and uses his stumbling blocks as stepping stones.",
                    image: "https://i.postimg.cc/WzwSM2fR/candice-2022.jpg" 
                },
                {
                    name: "Asandile Langeni - Peer",
                    message: "I view Gift as a very observant,  smart guy that is a very skilled web developer. He always gives 100%  towards his tasks and projects. He is a capable worker , a good team player and is always there to offer assistance and help. He would definitely be a valuable asset to any company.",
                    image: "https://i.postimg.cc/JhhXNfzD/Asandile.jpg" 
                },
                {
                    name: "Mkhuseli Mkeyiya - Peer",
                    message: "Gift is devoted into his work, he works well with others, he thirsts for creativity as his work will speak for itself.",
                    image: "https://i.postimg.cc/1tQfWb9r/Mkhuseli.jpg" 
                },
                {
                    name: "Athenkosi Freddie - Peer",
                    message: "Gift is very enthusiatic and confident person, who doesn't seem to fear anyone in his path. He is open to challenges and doesn't back down when the task needs to be complete. He would make an amazing teammate and you won't regret it.",
                    image: "https://i.postimg.cc/qqYrFCsH/Athenkosi-Freddie.jpg" 
                },
                {
                    name: "Given Mahlangu - Peer",
                    message: "Gift is a determined and disciplined person, who is always focused on the task at hand.He gives 100% in everything he does and is always to willing to assist his peers.His hard work and great communication skills makes him stand out.",
                    image: "https://i.postimg.cc/kMWk3z7t/Given.jpg" 
                }
            ]
            }
        }
    }
</script>

<style scoped>
    .testimonial-container{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        margin: auto;
    } 
    .card{
        margin: auto;
        margin-top: 2rem;
        margin-bottom: 1rem;
        height: 545px;
        box-shadow: 0 0 25px purple;
    }
    
    img{
        height: 30vh;
        object-fit: cover;
        object-position: top;
    }
    @media screen and (max-width: 900px) {
        .testimonial-container{
        display: grid;
        grid-template-columns: 2fr 2fr;
    }
    }
    @media screen and (max-width: 600px) {
        .testimonial-container{
        display: grid;
        grid-template-columns: 1fr;
    }
    }
</style>