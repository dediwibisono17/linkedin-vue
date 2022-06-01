<template>
  <div class="wrapper">
    <div class="card">
        <h2>Resources</h2>
      <div class="block">
        <div>
          <b>Creator Mode</b>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quidem neque quae perferendis earum deserunt, maiores quo quod nostrum iste. Quia, illum similique. Vitae neque culpa delectus necessitatibus iusto, nihil officia!</p>
        </div>
        <div>
          <b>My Network</b>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quidem neque quae perferendis earum deserunt, maiores quo quod nostrum iste. Quia, illum similique. Vitae neque culpa delectus necessitatibus iusto, nihil officia!</p>
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
  
}
</style>