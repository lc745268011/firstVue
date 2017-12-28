<template>
  <div id="firstcomponent">
    <!--<h1>I am a title.</h1>
    <a> written by {{ author }} </a>-->
    <ul v-for="(l,index) in lists" :key="index">
      <!--<li>{{l.name}}<router-link :to="{name:'detail',query:{id:index}}">查看</router-link></li>-->
      <li>{{l.name}}<router-link :to="{name:'detail',params:{id:index}}">查看</router-link></li>
    </ul>

  </div>
</template>

<script type="text/javascript">
  export default {
    data () {
    return {
      author: "微信公众号 jinkey-love",
      lists:[{
        name:'李晨1'
      },{
        name:'李晨2'
      }]
    }
  }
  }
</script>

<style>
</style>
