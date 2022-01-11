<template>
  <div class="entry-container mb-3 pointer p-2">
    <!-- title -->
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">15</span>
      <span class="mx-1 fs-5">Julio</span>
      <span class="mx-2 fw-light">2021, jueves</span>
    </div>

    <div class="entry-description">
      Duis labore pariatur ex voluptate. Aliquip deserunt ipsum laborum et id
      dolore minim nisi nostrud in excepteur dolore in aute. Ex ad reprehenderit
      irure amet. Commodo tempor pariatur nisi in enim excepteur quis laborum
      irure cupidatat ullamco aliqua qui. Cupidatat enim dolor dolore anim non
      aliqua quis consequat do minim sint dolore magna non.
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2 all ease-in;
  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2 all ease-in;
  }
  .entry-description {
    font-size: 12px;
  }
}
</style>