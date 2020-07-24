<template>
  <div id="home">
<!--    <nav-bar><div slot="center">购物车</div></nav-bar>-->
    <nav-bar><template v-slot:center><div>购物车</div></template></nav-bar>
  </div>
</template>

<script>
  import NavBar from "components/common/navbar/NavBar";
  export default {
    name: "Home",
    components:{
      NavBar
    }
  }
</script>

<style scoped>

</style>
