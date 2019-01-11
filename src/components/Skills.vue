<template>
  <div class="hello">
    {{ name }}

    <h1 v-if="verifyTrue">True</h1>
    <h1 v-if="!verifyFalse">False</h1>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      name: 'Antonio Apps',
      verifyTrue: true,
      verifyFalse: false
    }
  }
}
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
