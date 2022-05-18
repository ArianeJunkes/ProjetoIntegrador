<script>
import { RouterLink } from "vue-router";

export default {
  components: { RouterLink}
}
</script>
<template>
  <aside id="sidenav">
    <ul>
      <li><RouterLink to="/">Home</RouterLink></li>
      <li><RouterLink to="/sobre">Sobre</RouterLink></li>
    </ul>
  </aside>
</template>
<style>

li{
  color: #737373
}
</style>
