<template>
<div class="principal">
    <div class="box-header-principal">
        <Header></Header>
    </div>
    <div class="box-login">
      <br>
      <br>
      <p id="p">Fazer login</p>
      <label>Usuário: </label>
        <input id="input1" type="text">
        <br>
        <br>
      <label>Senha: </label>
        <input id="input2" type="password">
        <br>
      <button>
        <router-link to="/Home">Faça Login</router-link>
      </button>
    </div>
</div>
</template>

<script>
import Header from '../components/Header.vue'
export default {
  name: "Principal",
  components:{
    Header
  },
  methods: {
  },
};
</script>

<style>
.box-login p{
  color: black;
}

.box-header-principal{
  width: 102%;
  margin-top: -9px;
  margin-left: -9px;
}

.principal .box-login{
  background: rgb(227, 236, 240);
  width: 300px;
  margin-left: 40%;
  height: 300px;
  border-radius: 10px;
  margin-top: -60px;
  font-size: 17px;
  font: 'Roboto'; 
}

.principal .box-login p{
  font-size: 20px;
  margin: 0px 0px 60px 100px;
  color: rgb(8, 0, 36);
}

.principal .box-login label{
  font-size: 18px;
  margin: 0px 0px 0px 30px;
}

#input1{
    margin: 0px -20px 0px 0px;
}

#input2{
  margin: 0px 0px 0px 10px;
}

button{
  margin: 30px 0px 0px 110px;
  width: 100px;
}

a{
  text-decoration: none;
  color: black;
}

html{
  background: rgb(157, 206, 252);
}

</style>
