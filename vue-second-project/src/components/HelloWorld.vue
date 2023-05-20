<template>
  <div class="google">
    <img class="microphone-img" src="https://cdn.discordapp.com/attachments/1097269478280142931/1109284034091176019/7611756.png">
    <img class="search-img" src="https://cdn.discordapp.com/attachments/1097269478280142931/1109282679779770408/teste.png">
    <img class="google-img" src="https://cdn.discordapp.com/attachments/1105232971620941946/1109306862307909762/google-logo-1.png">
  </div>
  <div class="quadrado-adcionar">
    <h3 class="atalho">Adicionar atal...</h3>
    <div class="adicionar-mais"></div>
    <h2 class="maiszinho">+</h2>
  </div>
  <input class="input-text-v" v-model="inputText" type="text" placeholder="Pesquise no Google ou digite um URL" maxlength="50">
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

  .maiszinho {
    z-index: 2;
    margin-left: 33px;
    position: absolute;
    font-weight: 100;
    margin-top: 18px;
  }

  .adicionar-mais {
    width: 37px;
    margin-top: 13px;
    margin-left: 22px;
    height: 37px;
    background-color: rgb(241, 241, 241);
    position: absolute;
    border-radius: 50%;
  }

  .quadrado-adcionar{
    width: 80px;
    margin-left: 583px;
    margin-top: 77px;
    border-radius: 3px;
    position: absolute;
    height: 80px;
    background-color: white;
  }

  .atalho {
    position: absolute;
    font-size: 10px;
    font-weight: 100;
    margin-top: 60px;
    margin-left: 7px;
  }
  .quadrado-adcionar:hover {
    background-color: rgb(211, 211, 211);
  }
  .microphone-img {
    position: absolute;
    margin-left: 297px;
    margin-top: 215px;
    width: 22px;
    z-index: 1;
  }
  .input-text-v {
    width: 363px;
    border-radius: 20px;
    background-position: center center;
    /* text-align: start; */
    padding: 0 43px;
    position: absolute;
    margin-left: -226px;
    margin-top: 29px;
    height: 32px;
    border: 1px solid white;
    box-shadow: 0 0 1em rgba(0, 0, 0, 0.253);
}

.search-img {
  width: 23px;
    margin-left: -110px;
    margin-top: 214px;
    position: absolute;
    z-index: 1;
}
  .google-img {
    width: 17%;
    margin-top: 105px;
  }
</style>
