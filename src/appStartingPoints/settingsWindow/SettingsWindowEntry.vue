<template>
  <div id="app">Settings</div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.buttons {
  display: flex;
  flex-direction: column;
  align-items: center;
}
button {
  width: 100%;
  height: 30px;
  background-color: white;
  border: 2px solid #494949;
  color: #494949;
  text-transform: uppercase;
  text-decoration: none;
  margin-bottom: 5px;
  cursor: pointer;
  font-weight: bold;
  transition: all 0.4s ease 0s;
}
button:hover {
  background-color: #494949;
  border: 2px solid black;
  color: white;
}
button:active {
  letter-spacing: 1px;
  transition: all 0.1s ease 0s;
}
</style>
