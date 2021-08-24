<template>
  <div class="bg">
    <h2>Sua músicas estão com saudade</h2>
    <div class="boxes">
      <Box singlerName="John Mayer" musicName="Slow Dance"/>
      <Box singlerName="Goo Goo Dolls" musicName="Let Love In"/>
      <Box singlerName="Goo Goo Dolls" musicName="Name"/>
      <Box singlerName="Nx zero" musicName="Onde estiver"/>
    </div>
    <h2>Tocados recentemente</h2>
    <div class="boxes">
      <Box singlerName="Nx zero" musicName="Só rezo"/>
      <Box singlerName="Justin Bieber" musicName="Hold On"/>
      <Box singlerName="Goo Goo Dolls" musicName="Better Days"/>
      <Box singlerName="Lil Nas X" musicName="Panini"/>
    </div>
  </div>
</template>s

<script>

import Box from './Box.vue';

export default {
  name: "Content",
  components: {
    Box
  },
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
  margin-top: 10px;
  color: white;
}
.boxes{
    display: flex;
}
</style>