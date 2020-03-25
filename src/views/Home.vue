<template>
  <div class="home">
    <h1>{{title}}</h1>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  data () {
    return {
      title: '学到新知识'
    }
  },
  components: {
    HelloWorld
  }
}
</script>
