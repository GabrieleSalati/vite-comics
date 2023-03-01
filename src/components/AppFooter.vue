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

.bigLogo {
    width: 25rem;
}
</style>