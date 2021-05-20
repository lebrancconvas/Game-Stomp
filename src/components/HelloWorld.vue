<template>
  <div class="hello">
    <div class="topic">GameStomp เพื่อนคู่คิด มิตรคู่เกมเมอร์</div>
    <router-link to="/signup"><div class="sign-up">Sign Up</div></router-link>
    <div class="sign-in">Sign in</div>
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello .topic {
    font-size: 45px;
  }

  .hello .sign-up {
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 10px;
    padding-right: 10px;
    border-radius: 20px;
  }
</style>
