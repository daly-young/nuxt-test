<template>
  <p>{{ routerVal }}</p>
</template>
<script>
export default {
  computed: {
    routerVal() {
      return this.$route.params.id
    }
  }
}
</script>
