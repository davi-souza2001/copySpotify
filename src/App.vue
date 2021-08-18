<template>
  <div>
    <HeadBar/>
  </div>
</template>

<script>

import HeadBar from "./components/HeadBar.vue";

export default {
  name: 'App',
  components: {
    HeadBar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700&display=swap');
*{
  font-family: 'poppins', sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>


