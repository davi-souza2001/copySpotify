<template>
  <div class="bar">
    <div class="score">
      <h2>...</h2>
    </div>
    <div class="profile">
      <h2>Davi Souza</h2>
      <img src="https://davi-souza2001.github.io/CV/memoji/WhatsApp%20Image%202021-03-17%20at%2015.10.03%20(1).jpeg" alt="foto de perfil">
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeadBar',
}
</script>


<style scoped>
  .bar{
    display: flex;
    justify-content: space-between;
    height: 8vh;
    background-color: black;
  }
  
  .score{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-left: 10px;
    height: 8vh;
    color: white;
  }
  .profile{
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 80%;
    color: white;
  }

  .profile h2{
    margin-right: 10px;
  }
  .profile img{
    height: 7vh;
    width: 4vw;
    border-radius: 9999px;
  }
</style>
