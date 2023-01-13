<template>
    <ContactVue/>
</template>

<script>
    import ContactVue from '@/components/ContactVue.vue';
    export default{
        name: 'ContactView',
        components:{
            ContactVue
        }
    }
</script>

<!-- <style scoped>
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
        box-shadow: 0 0 25px purple;
        margin-top: 2rem;
        margin-bottom: 2rem;
        /* background-color: black; */
        background-color: white;
    }

    @media screen and (max-width: 750px) {
    #form{
        min-width: 25rem;
    }
}
@media screen and (max-width: 560px) {
    #form{
        min-width: 22rem;
    }
}
@media screen and (max-width: 300px) {
    box-shadow{
       display: none;
}
@media screen and (max-width: 530px) {
    #form{
        min-width: 18rem;
    }
}

@media screen and (max-width: 420px) {
    #form{
        min-width: 16rem;
    }
}
@media screen and (max-width: 340px) {
    #form{
        min-width: 14rem;
    }
}
@media screen and (max-width: 300px) {
    #form{
        min-width: 14rem;
    }
}
}
</style> -->