<script>

export default {
  name: 'AppHero',
  data() {
    return {

    image : 'https://picsum.photos/200/300'

    };
  },
};

</script>

<template>

<img :src="image">


</template>

<style scoped>

</style>
