<template>
  <div>
    <h1>{{ title }}</h1>
    <p>{{ greeting() }}</p>
  </div>
</template>

<script>
export default {
data(){
  return {
    title: "yeeah bwooy"
  }
},
methods:{
  greeting:function(){
    return 'sahoooo!!!'
  }
}
}
</script>

<style>

</style>
