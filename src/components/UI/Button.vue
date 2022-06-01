<template>
  <div>
      <button type="button" class="button">
          {{msg}}
      </button>
    </div>
</template>
<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>
<style lang="scss" scoped>
.button {
  background: red;
}
// eslint-disable-next-line prettier/prettier
</style>