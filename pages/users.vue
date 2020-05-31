<template>
  <!-- when you create a same name vue file with folder you can create nested route -->
  <div>
    <div>This is User Page</div>
    <nuxt-child />
  </div>
</template>

<script>
export default {
  // user another layout
  layout: 'users'  
}
</script>
