<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Collapse/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Collapse from '/home/e/app/flask_vue/from_ui/src/components/Collapse'
export default {
  name: 'Home',
  components: {
    HelloWorld,
    Collapse
  }
}
</script>
