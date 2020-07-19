<template>
  <div class="login">
    <telaLogin />
  </div>
</template>
<script>

import telaLogin from "../components/telaLogin"

export default {
  name: "Login",

  components:{
    telaLogin,
  },

  data() {
    return {
      dialog: false
    }
  }
};
</script>
<style scoped>


</style>
