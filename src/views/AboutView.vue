<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<style scoped lang="less">
@color-red: red;
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
  h1 {
    background-color: @color-red;
  }
}
</style>
