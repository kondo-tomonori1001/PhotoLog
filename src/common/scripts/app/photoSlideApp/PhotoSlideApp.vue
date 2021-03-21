<template>
  <p>photoSlide</p>
</template>

<script>


export default {
  data() {
    return {
      items: [],
    };
  },
  created() {
    // async function test() {
    //   const res = await fetch("http://wpdemo.local/wp-json/acf/v3/photo");
    //   const post = await res.json();
    //   return post;
    // };
    this.items = [0,1];
  },
};
</script>

<style>
</style>