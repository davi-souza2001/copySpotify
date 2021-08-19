<template>
  <div class="bg">
    <h2>Sua músicas estão com saudade</h2>
    <div class="boxes">
      <Box/>
    </div>
  </div>
</template>s

<script>

import Box from './Box.vue';

export default {
  name: "Content",
  components: {
    Box
  }
};
</script>

<style>
.bg {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  height: 92vh;
  width: 100vw;
  background-color: rgb(29, 29, 29);
}
h2 {
  color: white;
}
.boxes{
    display: flex;
}
</style>