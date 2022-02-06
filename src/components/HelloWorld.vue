<template>
  Test 3
  <aa-hello-world />
</template>

<script>
import AaHelloWorld from 'aa-vue-hello-world-simple'
export default {
  components: {
    // OtherComponent
    AaHelloWorld
  },
  data () {
    return {
      greeting: 'Hello'
    }
  }
}
</script>

<style scoped>

</style>