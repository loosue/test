<template>
  <div class="header">
      <ul>
        <li v-on:click = "navclick"><a href="#">Javascript</a></li>
        <li ><a href="#">React</a></li>
        <li ><a href="#">Java</a></li>
        <li ><a href="#">vue</a></li>
        <li ><a href="#">angular js</a></li>
      </ul>
    </div>
</template>

<script>
export default {
  name: 'header',
  data: {
    count: 0
  },
  methods: {
    navclick: function(){
      console.log(this);
      data.count+=1
      console.log(data.count);
    }
  }

}
</script>

<style media="screen">
  .header ul li{margin: 10px}
</style>
