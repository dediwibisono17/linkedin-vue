<template>
  <div class="wrapper">
    <div class="card">
        <h2>Experience</h2>
      <div class="block">
        <div class="portfolio">
          <div class="portfolio__img">
            <img src="https://www.pakbob.id/wp-content/uploads/2021/11/Twitter.jpg" alt="">
          </div>
          <div class="portfolio__desc">
            <b>Frontend Developer</b><br>
            <small>Twitter</small><br>
            <small>2010-Present</small>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quidem neque quae perferendis earum deserunt, maiores quo quod nostrum iste. Quia, illum similique. Vitae neque culpa delectus necessitatibus iusto, nihil officia!</p>
          </div>
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
  .portfolio {
    display: block;
    &__img {
      width: 100px;
      height: 100px;
      display: inline-block;
      img {
        width: 100%;
        height: 100%;
        object-fit: cover;
      }
    }
    &__desc {
      display: inline-block;
      width: 70%;
      vertical-align: top;
      margin-left: 8px;
    }
  }
  small {
    color: #777;
  }
}
</style>