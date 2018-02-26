<template>
  <div id="app">
    <lcHead></lcHead>
    <div class="container main-container">
      <div class="view welcome-view">
        <lcMain></lcMain>
        <lcAside></lcAside>
      </div>
    </div>

  </div>
</template>

<script>
  import lcHead from './component/head.vue'
  import lcAside from './component/aside.vue'
  import lcMain from './component/main.vue'
export default {
  name: 'app',
  data () {
    return {

    }
  },
  components: {lcHead,lcAside,lcMain}
}
</script>

<style>
  #app{
    background: #f4f5f5;
  }
</style>
