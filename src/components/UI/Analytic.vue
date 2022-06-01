<template>
  <div class="wrapper">
    <div class="card">
      <div class="block">
        <div class="d-block">
          <b>98 Profile Views</b>
          <p>Discover who's viewed your profile</p>
        </div>
        <div class="d-block">
          <b>98 Profile Views</b>
          <p>Discover who's viewed your profile</p>
        </div>
        <div class="d-block">
          <b>98 Profile Views</b>
          <p>Discover who's viewed your profile</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card"
};
</script>

<style lang="scss" scoped>
.wrapper{
  display: block;
  width: 860px;
  margin: 0 auto;
}
.card {
  padding: 16px;
  text-align: left;
  margin-top: 24px;
  box-shadow: 0 3px 6px #bbb;
  &__image {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    img {
      width: 100%;
      border-radius: 50%;
      height: 100%;
      object-fit: cover;
    }
  }
  .block {
    display: flex;
    margin: 16px 0;
    justify-content: space-between;
  }
}
</style>