<template>
  <div>
    <el-button type="success" @click="jumpHome()">点击进入主题</el-button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
        
    }
  },
  methods:{
    jumpHome(){
      this.$router.push({name:"localstroge"})
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
