<script>
export default {
    data() {
        return {
        };
    },
};
</script>
<template>
    <footer>
        <div class="services">
            <img class="service" src="/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="">
            <h3>DIGITAL COMICS</h3>
            <img class="service" src="/vue-dc-comics-1/img/buy-comics-merchandise.png" alt="">
            <h3>DC MERCHANDISE</h3>
            <img class="service" src="/vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="">
            <h3>SUBSCRIPTION</h3>
            <img class="service" src="/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="">
            <h3>COMIC SHOP LOCATOR</h3>
            <img class="service" src="/vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="">
            <h3>DC POWER VISA</h3>
        </div>
        <div class="bot-links">
            <div class="links">
                <ul>
                    <h4>title</h4>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <h4>title</h4>
                    <li>link</li>
                    <li>link</li>
                </ul>
                <ul>
                    <h4>title</h4>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                </ul>
                <ul>
                    <h4>title</h4>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                </ul>
            </div>
            <div><img class="bigLogo" src="/vue-dc-comics-1/img/dc-logo-bg.png" alt="bigLogo"></div>
        </div>
        <div class="contacts">
            <div class="button"><button>SIGN UP NOW!</button></div>
            <div class="social">
                <h3>FOLLOW US!</h3>
                <img src="/vue-dc-comics-1/img/footer-facebook.png" alt="">
                <img src="/vue-dc-comics-1/img/footer-periscope.png" alt="">
                <img src="/vue-dc-comics-1/img/footer-pinterest.png" alt="">
                <img src="/vue-dc-comics-1/img/footer-twitter.png" alt="">
                <img src="/vue-dc-comics-1/img/footer-youtube.png" alt="">
            </div>
        </div>
    </footer>
</template>
<style lang="scss" scoped>
@use '../assets/scss/dedicated/mixins.scss' as *;

footer {
    height: 700px;
}

.services {
    @include flex-around();
    background-color: blue;
    height: 200px;
}

.service {
    width: 3rem;
}

.bot-links {
    @include flex-around();
    background-image: url(/vue-dc-comics-1/img/footer-bg.jpg);
    height: 400px;
}

.links {
    @include flex-around();
}

ul {
    margin: 0 2rem;
}

.bigLogo {
    width: 25rem;
}

.contacts {
    background-color: darkgray;
    height: 100px;
    @include flex-around();
}
</style>