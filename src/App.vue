<template>
  <div id="app">
    <header>
      <div id="menu">
        <div id="logoAndQS">
        <img src="./assets/logoQS.png" alt="" id="logoQS">
        <h1 id="QS">QS</h1>
        </div>
        
        <ul>
          <li> <a href="">Главная</a> </li>
          <li> <a href="">О нас</a> </li>
          <li> <a href="">Услуги</a> </li>
          <li> <a href="">Отзывы</a> </li>
          <li> <a href="">Команда</a> </li>
          <li> <a href="">Demo</a> </li>
        </ul>
        <a id="enterInCabinet" href="">Вход<br> в кабинет</a>
        <div id="numberSupport">+7(953)098-89-83</div>
      </div>
    </header>
    <section id="firstSection">
      <div id=""></div>
    </section>
  </div>
</template>

<script>

export default {
  name: 'App',
  methods: {
    catBy: () => {
      document.getElementById('catHappy').style.display = 'block';
    }
  },
}
</script>

<style>
html {
  width: 100%;
  margin: 0;
  padding: 0;
}

body {
  width: 100%;
  margin: 0;
  padding: 0;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#menu {
  display: inline-flex;
  align-items: center;
  justify-content: space-between;
  background: url('./assets/fonMenu.jpg') no-repeat;
  background-size: cover;
  width: 100%;
  margin: 0;
  padding: 0;
}
#logoAndQS {
  display: inline-flex;
  justify-content: space-between;
  align-items: center;
}
#logoQS {
  margin-left: 20px;
  margin-bottom: 5px;
  margin-top: 10px;
}

#menu > ul {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-around;
}

ul > li {
  display: flex;
  justify-content: space-around;
}

ul > li > a {
  background: url('./assets/gear.png');
  text-decoration: none;
  color: white;
}
</style>
