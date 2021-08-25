<template>
  <div class="contentbox">
      <img src="../assets/johnmayer.jpeg" alt="">
      <div class="music">
          <h3>{{musicName}}</h3>
          <h4>{{singlerName}}</h4>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Box',
    props:{
        musicName:{
            type: String,
            default: ""
        },
        singlerName:{
            type: String,
            default: ""
        }
    }
}
</script>

<style>
.contentbox{
    display: flex;
    align-content: center;
    justify-content: center;
    flex-direction: column;
    height: 38vh;
    width: 29vh;
    margin: 0 2vw;
    border-radius: 5px;
    background-color: rgb(47, 47, 47);
    cursor: pointer;
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