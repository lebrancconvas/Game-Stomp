<template>
  <div class="hello">
    <div class="topic">GameStomp เพื่อนคู่คิด มิตรคู่เกมเมอร์</div>
    <div class="sign-up">Sign Up</div>
    <div class="sign-in">Sign in</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello .topic {
    font-size: 45px;
  }
</style>
