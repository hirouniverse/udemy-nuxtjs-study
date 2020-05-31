<template>
  <div>Single User's page / User ID : {{ $route.params['id'] }}</div>
</template>

<script>
export default {
  // this validate method takes 'context' object
  // https://nuxtjs.org/api/context
  validate ({ params }) {
    return /^\d+$/.test(params.id)
  }
}
</script>