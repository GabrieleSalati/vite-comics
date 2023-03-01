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
    height: 500px;
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