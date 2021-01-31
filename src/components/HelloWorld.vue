<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <el-button
      plain
      @click="open">
      Click Me
    </el-button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    open: function() {
      this.$notify({
        title: 'Message',
        message: 'Hello, Element UI.',
        type: 'success'
      });
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
