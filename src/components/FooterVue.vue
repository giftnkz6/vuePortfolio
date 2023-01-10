<template>
    <div class="wrapper">
        <div class="row">
            <div class="col">
                <p>Copyright &copy; 2023</p>
            </div>
            <div class="col">
                <p>314 Imam Haron Road,</p>
                <p>Lansdowne</p>
            </div>
            <div class="col">
                <p>Social Media</p>
                <ul>
                    <li><a id="linkedin" href="https://www.linkedin.com/in/gift-mahlangu-223262180/" target="_blank"><i class="fa-brands fa-linkedin fa-bounce"></i></a></li>
                    <li><a id="facebook" href="https://www.facebook.com/gift.mahlangu.923" target="_blank"><i class="fa-brands fa-facebook fa-bounce"></i></a></li>
                    <li><a id="instagram" href="https://www.instagram.com/gift_nkz/" target="_blank"><i class="fa-brands fa-instagram fa-bounce"></i></a></li>
                    <li><a id="twitter" href="https://twitter.com/GiftGiftnkz6" target="_blank"><i class="fa-brands fa-twitter fa-bounce"></i></a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterVue'
}
</script>

<style>
    .wrapper .row .col ul li{
        margin: 1rem;
        font-size: larger;
        margin-left: 4rem;
    }
    ul li #instagram{
    color: orangered;
    }
    ul li #twitter{
    color:aqua;
    }
</style>