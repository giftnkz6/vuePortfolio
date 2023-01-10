<template>
    <h1 class="scroll display-2">Contact</h1>
    <div class="container w-50">
        <div class="row">
            <div id="form" class="container justify-content-center">
                <form class="form container mt-3" action="https://formspree.io/f/mrgdkjgy" method="POST">
                    <div class="form-floating mb-4">
                        <input type="text" class="form-control" name="name" placeholder="Enter your name" id="floatingInput" required>
                        <label for="floatingInput">Enter your name</label>
                    </div>
                    <div class="form-floating mb-4">
                        <input type="text" class="form-control" name="surname" placeholder="Enter your surname" id="floatingInput" required>
                        <label for="floatingInput">Enter your surname</label>

                    </div>
                    <div class="form-floating mb-4">
                        <input type="text" class="form-control" placeholder="Enter your email" id="floatingInput" required>
                        <label for="floatingInput">Enter your email</label>
                    </div>
                    <div class="form-floating mb-4">
                        <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
                        <label for="floatingTextarea">Leave us a message</label>
                    </div>
                    <div class="mb-4">
                        <button class="btn btn-outline-info">Submit</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
        
    <address>
            
        Written by Gift Mahlangu<br>
        Visit me at:
        Life Choices<br>
        314 Imam Haron Road,<br> Lansdowne
        South Africa
        <br>
    </address>
        
</template>

<script>
    export default{
        name: 'ContactView'
    }
</script>

<style scoped>
    address{
        color: white;
    }
    .form-floating #floatingTextarea{
        height: 12rem
    }
    h1{
        margin-top: 2rem;
        margin-bottom: 2rem;
        text-shadow: 2px 1px white;
    }
    #form{
        width: 35rem;
        box-shadow: 0 0 25px #c1c1c1;
        margin-top: 2rem;
        margin-bottom: 2rem;
    }
</style>