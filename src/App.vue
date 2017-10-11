<template lang="pug">
  #app
    navbar
    sidebar
    router-view
</template>

<script>
import Navbar from '@/components/layout/Navbar'
import Sidebar from '@/components/layout/Sidebar'
export default {
  name: 'app',
  components: {
    Navbar,
    Sidebar
  }
}
</script>

<style lang="sass">
@import '~bulma/bulma.sass'
</style>
