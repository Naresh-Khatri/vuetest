<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class = "logo" src="@/assets/build-a-bot-logo.png">
            Build a Bot
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <temptest/>
    </main>
 </div>
</template>

<script>
// import homePage from './home/homePage.vue';
// import robotBuilder from './build/robotBuilder.vue';
import temptest from './build/temptest.vue';

export default {
  name: 'App',
  components: {
    // robotBuilder,
    temptest,
  },
};
</script>

<style>
body{
  background:linear-gradient(to bottom , #287,#123);
  background-attachment: fixed;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
 }
 main{
   margin: 0 auto;
   padding: 30px;
   background-color:  white;
   width:10;
   min-height: 300px;
 }
 header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
