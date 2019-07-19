<template>
  <div class="hello">
    <h2>{{count}}</h2>
    <div>
      <button @click="count++">点我+</button>
      <button @click="count--">点我-</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Counter",
  data(){
    return {
      count: 0
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
