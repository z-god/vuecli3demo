<template>
  <div class="home">
      <mark-down/>
  </div>
</template>

<script>
// @ is an alias to /src
import MarkDown from 'vue-meditor'
export default {
  name: 'home',
  components: {
    MarkDown
  }
}
</script>
<style lang="less" scoped>
.home{
    .v-note-wrapper{
      height: 100vh;
    }
}
</style>

