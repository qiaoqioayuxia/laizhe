<template>
 <div>{{msg}} {{age}}</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      age:18
    }
  }
}
</script>
<style>
div{background:red}

</style>
