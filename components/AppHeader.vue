<template>
  <header class="header">
    <h1 class="tittle">Jennifer</h1>
    <ul>
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><nuxt-link to="/jobs">Jobs</nuxt-link></li>
      <li><nuxt-link to="/about">About</nuxt-link></li>
    </ul>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
};
</script>

<style>
.header{
  display:flex;
}
.header ul{
  display: flex;
}
.header a{
  display: inline-block;
}
</style>
