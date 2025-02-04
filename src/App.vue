<template>

 <div id="nav">
  <div class="navigation">

    <nav>
      <div class="router">
            <router-link class="link" to="/">Inicio</router-link>
            <router-link class="link" to="/about">Procedimentos</router-link>
            <router-link class="link" to="/">Preços</router-link>
            <router-link class="link" to="/about">Galeria</router-link>
            <router-link class="link" to="/about">Contato</router-link>
          </div>

          <div class="cadastro">
            <router-link class="cad-user" to="/">Cadastre-se</router-link>
          </div>

          <div class="login">
            <router-link class="user" to="/">Login</router-link>
          </div>
    </nav>

  </div>
  <router-view/>
 </div>
</template>

<script>


</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#nav{
  background-color: aqua;
  
}

.router{

padding: 10px 4px 10px 200px;
}

.login{
  float: right;
  margin-top: -30px;
  margin-right: 70px;
  border-radius: 15px;
  padding: 0px 15px 0px 15px;
  
  }
.user{
  color: #fff;
  text-decoration: none;
  font-family: Arial, Helvetica, sans-serif;
}

.login:hover{
  background-color: red;
  color:aquamarine;
}
.cadastro{
  float: right;
  margin-top: -30px;
  margin-right: 200px;
  padding: 0px 15px 0px 15px;
  border-radius: 15px;
}
.cad-user{
  color: #fff;
  text-decoration: none;
  font-family: Arial, Helvetica, sans-serif;
}

.cadastro:hover{
  background-color: red;
  color:aquamarine;
}
.link{
  color: azure;
  padding: 0px 15px 0px 15px;
  text-decoration: none;
  font-family: Arial, Helvetica, sans-serif;
  display: inline-block;
  border-radius: 15px;
  
}
.link:hover{
  background-color: red;
  color:aquamarine;

}
nav{
  background-color: black;
  
}
.navigation{
  border: 2px solid #fff;
}

</style>