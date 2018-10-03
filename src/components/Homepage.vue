<template>
  <div class="hello">
    
    <h1>{{ msg }}</h1>
    <div class="wave-container">
      <img class="anchor" src="../assets/images/anchor-jesus.svg">
      <img src="../assets/images/sea-waves.svg">
    </div>
  </div>
</template>

<script>
export default {
  name: "Homepage",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .wave-container {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 400px;
  }

  .wave-container img {
    width: 40%;
  }

  .wave-container .anchor {
    width: 10%;
    position: absolute;
    top: 15%;
  }

</style>
