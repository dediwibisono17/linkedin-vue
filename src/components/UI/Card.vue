<template>
  <div class="wrapper">
    <div class="card">
      <div class="card__image">
        <img src="https://awsimages.detik.net.id/community/media/visual/2017/06/22/c5f6a4b7-d06e-4512-b239-0b7d4d31714e_11.jpg?w=700&q=90" alt="">
      </div>
      <div class="card__name">
        Detective Conan
      </div>
      <div class="card__position">
        Frontend Developer
      </div>
      <div class="card__location">Jakarta, Indonesia</div>
      <div class="block">
        <button class="btn btn-primary">Open To</button>
        <button class="btn btn-secondary">Add Profile Section</button>
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
  &__name {
    font-size: 28px;
    text-align: left;
    font-weight: bold;
  }
  &__position {
    margin: 8px 0;
  }

  .btn {
    padding: 8px;
    display: inline-block;
    border-radius: 16px;
    margin-right: 16px;
    font-weight: bold;
    outline: 0;
    border-color: white;
    border-width: 1px;
    &-primary {
      background: rgba($color: blue, $alpha: .7);
      color: white !important;
      border-color: #bbb;
    }
    &-secondary {
      background: white;
      color: rgba($color: blue, $alpha: .7) !important;
      border-color: #bbb;
    }
  }
  .block {
    display: block;
    margin: 16px 0;
  }
}
</style>