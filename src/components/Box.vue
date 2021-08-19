<template>
  <div class="contentbox">
      <img src="" alt="Foto da capa">
      <div class="music">
          <h3>Slow dance</h3>
          <h4>John Mayer</h4>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Box',
}
</script>

<style>
.contentbox{
    display: flex;
    align-content: center;
    justify-content: center;
    flex-direction: column;
    height: 42vh;
    width: 34vh;
    border-radius: 10px;
    background-color: rgb(47, 47, 47);
}
h3{
    margin-left: 1vw;
    color: rgb(221, 221, 221);
}
h4{
    margin-left: 1vw;
    color: rgb(141, 141, 141);
}

</style>