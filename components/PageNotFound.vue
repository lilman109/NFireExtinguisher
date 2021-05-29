<template>
  <div class="container">
    <h1>Page Not Found</h1>
    <img :src="require('@/assets/images/fe25.jpg')" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 50rem;
}
h1 {
  font-size: 7.5rem;
}
img {
  width: 15rem;
  margin: 0 auto;
}
</style>
