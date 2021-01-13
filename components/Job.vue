<template>
<nuxt-link :to="'jobs/'+id">
  <div class="job">
    <h1>{{job}}</h1>
  </div>
  </nuxt-link>
</template>

<script lang="ts">
export default {
  name:'Job',
  props:['job','id']
}
</script>

<style>

</style>
