<script setup>
  import Header from './components/Header.vue'
</script>

<template>
  <span class="center">
    <img alt="Vue logo" src="./assets/logo.png" />
    <img alt="Vue logo" src="./assets/logo.svg" />
  </span>
  <Header msg="Todo App" desc="With Vite and Vue" />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
}

.container {
  max-width: 500px;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 1px solid steelblue;
  padding: 30px;
  border-radius: 5px;
}

.btn {
  display: inline-block;
  background: #000;
  color: #fff;
  border: none;
  padding: 10px 20px;
  margin: 5px 10px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
}

.btn:focus {
  outline: none;
}

.btn:active {
  transform: scale(0.98);
}

.btn-block {
  display: block;
  width: 100%;
}

img {
  width: 75px;
  padding: 5px;
  margin-top: 25px;
}

.center {
  display: flex;
  justify-content: center;
}
</style>
