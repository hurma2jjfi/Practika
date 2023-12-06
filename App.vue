<script>
export default{
  data() {
    return {
      Languages: []

    };
  }
};
</script>

<template>

  <!-- VARIANT 1 TASK 1 -->
<!-- <div>
  <p>Какие языки вы знаете ?</p>
  <input type="checkbox" value="Английский" v-model="Languages">Английский
  <input type="checkbox" value="Французский" v-model="Languages">Французский
  <input type="checkbox" value="Немецкий" v-model="Languages">Немецкий
  <ul><li v-for="Language in Languages" :key="Language">{{ Language }}</li></ul>
</div> -->

  <!-- VARIANT 1 TASK 1 -->
<div>
  <div class="head_line">
    <div>
      <a class="headLine_elem" href="main">ГЛАВНАЯ</a>
    </div>
    <div>
      <a class="headLine_elem" href="project">ПРОЕКТЫ</a>
    </div>
    <div>
      <a class="headLine_elem" href="services">УСЛУГИ</a>
    </div>
    <div>
      <a class="headLine_elem" href="contacts">КОНТАКТЫ</a>
    </div>
  </div>

  <div class="display">
    <p>Выбран класс</p>
    <p class="choosen"></p>
  </div>
</div>


  
</template>

<style>
* {
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Courier New', Courier, monospace;
}
.head_line {
  display: flex;
  justify-content: space-around;
  width: 500px;
  height: 35px;
align-items: center;
  background-color: rgb(99, 176, 231);

}

.headLine_elem {

  text-decoration: none;
  color: black;
  font-weight: bold;

}

.headLine_elem:hover {
  background-color: rgb(204, 50, 158);
width: 500px;
height: 35px;
transition: 1.2s ;
color: aliceblue;
}


</style>
