<template>
  <div>
      <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
  </div>
</template>

<script>
export default {
    name:'Hero',
}
</script>

<style scoped lang="scss">

div {
    height: 450px;
    img {
        height: 100%;
        width: 100%;
        object-fit: cover;
        
    }
}
</style>