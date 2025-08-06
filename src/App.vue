<template>
<h2 v-if="num === 0">The number is zero</h2>
<h2 v-else-if="num < 0">The number is negative</h2>
<h2 v-else-if="num > 0">The number is postive</h2>
<h2 v-else>Not a number</h2>


<template v-if="display">
<h2>Vishwas</h2>
<h2>Code</h2>
<h2>Vue</h2>
</template>

<h2 v-show="showElement">Using V-show</h2>
<h2 v-if="showElement">Using V-if</h2>
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
        num:"a",
        display: true,
        showElement: false,
    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
