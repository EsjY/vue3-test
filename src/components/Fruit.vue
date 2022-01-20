<template>
  <li>{{ name }}?!</li>  
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      defualt: ''
    }
  }
}

</script>

<style scoped lang="scss">
  h1 {
    color: red !important;
  }
</style>