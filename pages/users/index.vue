<template>
  <div>
    <div>This is users page.</div>

    <input type="text" v-model="id">
    <button @click="load">Load</button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      id: ''
    }
  },
  methods: {
    load () {
      this.$router.push('users/' + this.id)
    }
  }
}
</script>