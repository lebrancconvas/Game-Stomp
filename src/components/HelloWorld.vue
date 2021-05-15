<template>
  <div class="hello">
    <h1>GameStomp เพื่อนคู่คิด มิตรคู่เกมเมอร์</h1>
    <button class="button is-primary">Sign Up</button>
    <button class="button is-link">Sign in</button>
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
  h1 {
    font-size: 45px;
  }
</style>
