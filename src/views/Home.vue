<template>
<div class="home">
  <div class="box-header-principal">
    <Header></Header>
  </div>
  <div class="box-mensagens-enviadas">
    <br>
    <br>
    <p id="postagem">Postagens</p>
    <br>
    <div class="card-postagem">
      <br>
      <p>Hoje ainda terça :'(</p>
      <p>24/08/2021</p>
      <p>às 09:50</p>
      <img src="../assets/sad.png" alt=""><br>
      <input type="text" placeholder="Adicione seu comentário">
      <button>Comentar</button>

       <div class="box-mensagem">
         <br>
        <p><strong>Faça uma postagem</strong></p><br>
        <label>Inserir mensagem</label><br>
        <input type="text"><br>
        <label>Carregar imagem</label><br>
        <input type="file"><br>
        <label>Data: </label><br>
        <input type="date"><br>
        <label>Hora: </label><br>
        <input type="text"><br>
        <button>Postar</button>
    </div>
    </div>

  </div>

  <br>
  <br>

</div>
</template>
<script>
import Header from '../components/Header.vue'
export default {
  name: "Home",
  components:{
    Header
  },
  methods: {
  },
};
</script>

<style>
.home .box-mensagens-enviadas{
  background: rgb(227, 236, 240);
  width: 400px;
  margin-left: 38%;
  height: 800px;
  border-radius: 10px;
  margin-top: -60px;
  font-size: 17px;
  font: 'Roboto'; 
}

#postagem{
  font-size: 24px;
  margin: 0px 0px 20px 150px;
}

.home .box-mensagens-enviadas .card-postagem{
  background: rgb(255, 255, 255);
  width: 380px;
  margin-left: 10px;
  height: 400px;
}

.home .box-mensagens-enviadas .card-postagem p,
.home .box-mensagens-enviadas .card-postagem img{
  margin: 0px 0px 0px 20px;
}

.home .box-mensagens-enviadas .card-postagem img{
  width: 100px;
  height: 100px;
}

.home .box-mensagens-enviadas .card-postagem button{
  margin-left: 10px;
}

.home .box-mensagens-enviadas button{
  margin: 20px 0px 20px 0px;
}

.home .box-mensagens-enviadas .card-postagem .box-mensagem label,
.home .box-mensagens-enviadas .card-postagem .box-mensagem input,
.home .box-mensagens-enviadas .card-postagem .box-mensagem button{
  margin: 0px 0px 10px 20px;
}

.home .box-mensagens-enviadas .card-postagem .box-mensagem{
  background:  rgb(237, 243, 248);
}

.home .box-mensagens-enviadas .card-postagem .box-mensagem button{
  width: 120px;
}

</style>