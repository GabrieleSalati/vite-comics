<script>
export default {
  data() {
    return {
      links: ['characters', 'comics', 'movies', 'tv', 'games', 'collectibles', 'videos', 'fans', 'news', 'shop']
    };
  },
};
</script>
<template>
  <header>
    <img src="/vue-dc-comics-1/img/dc-logo.png" alt="logo">
    <ul>
      <li v-for="link of links"><a href="#">{{ link }}</a></li>
    </ul>
  </header>
</template>
<style lang="scss" scoped>
@use '../assets/scss/dedicated/mixins.scss' as *;

header {
  @include flex-around();
  padding: 2rem 0;
}

li {
  display: inline-block;
  margin: 0 1rem;

  a {
    text-decoration: none;
  }
}
</style>