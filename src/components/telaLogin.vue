<template>
  <form class="caixaLogin">
    <div class="login">

      <h1> Login </h1>
      
      <label> Email </label>
      <input type="text" placeholder="email" />
      <br /> <br />
      
      <label> Senha </label>
      <input type="password" placeholder="senha" />
      <br /> <br />
    
      <button class="entrar">Entrar</button>

      <br /> <br />
      
      <button class="cadastrar">Cadastrar</button>
    </div>
  </form>
</template>

<script>
export default {};
</script>

<style scoped>

h1{
    margin-bottom: 33px;
    margin-top: -35px;
}

.caixaLogin {
  width: 160px;
  height: 240px;
  text-align: center;
  margin: auto;
  background-color:rgb(224, 224, 224) ;
  margin-top: 100px;
  padding: 60px;
  border-radius: 8px;
}

label{
    margin-right: 140px;
    margin-left: -10px;
    
}


input{
  padding: 5px;
  margin-bottom: 15px;
  margin-left: -10px;
  margin-top: 3px;
}

.entrar{
  padding: 5px;
  width: 183px;
  color: white;
  background-color: purple;
  text-align: center;
  margin-left: -12px;
  
}

.cadastrar{
  padding: 5px;
  width: 183px;
  color: purple;
  background-color:white;
  text-align: center;
  margin-left: -12px;
  
}

</style>

