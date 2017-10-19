<template lang="pug">
  div
    h1 {{ msg }}
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Home'
    }
  }
}
</script>
