<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import WelcomeItem from './components/WelcomeItem.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/ml.png" width="350" height="350" />
  </header>


  <main>
    <div class="parent">
    <div class="login">
    <HelloWorld />
    </div>
    <br>
    <div class="heropoll">
    <TheWelcome />
    </div>
    <br>
    <div class="price">
    <WelcomeItem />  
    </div>
    </div>
  </main>
  
</template>

<style>
  .login{
    background-color: #FFEDDB;
    text-align: center;
  }

  .heropoll{
    background-color: #EDCDBB;
  }

  .price{
    background-color: #E3B7A0;
    text-align: center;
  }

  .parent{
    background-color: #EEE9DA;
  }
</style>