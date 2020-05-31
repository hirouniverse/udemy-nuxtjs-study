<template>
  <div class="container">

    <!--
    <div class="container">
      <div>a tag link (send new request is sent to server)</div>
      <a href="/users">Users</a>
    </div>
    -->

    <nuxt-link to="/users">Users</nuxt-link>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

// you can access to all of default vue properties
export default {
  components: {
    Logo
  }
}
</script>

