<template>
  <div>
    <el-button type="info" @click="quit">退出</el-button>
  </div>
</template>
<script>
export default {
  name: 'home',
  data () {
    return {

    }
  },
  methods: {
    quit () {
      window.sessionStorage.clear()
      this.$router.push('/login')
    }
  }
}
</script>
<style scoped>

</style>
