<script>
export default {
    props: {
        comics: Array,
    },
};
</script>
<template>
    <main>
        <ul>
            <li v-for="comic in comics">
                <img class="thumb" :src="comic.thumb" alt="thumb">
                <h3>{{ comic.series }}</h3>
            </li>
        </ul>
    </main>
</template>
<style lang="scss" scoped>
@use '../assets/scss/dedicated/mixins.scss' as *;

main {
    background-color: black;
}

ul {
    @include flex-around();
    flex-wrap: wrap;
}

h3 {
    color: white;
}

.thumb {
    width: 100px;
    height: 100px;
}
</style>