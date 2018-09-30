<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>

html {
  font-size: 62.5%;
  background-image: url("../Images/Woodtable.jpeg");
  height: 100%; 
  background-position: cover;
  background-repeat: no-repeat;
  background-size: cover;
}

*, 
*::after, 
*::before {
  margin: 0;
  padding: 0;
  box-sizing: inherit;
  /*resetting the browser settings */
}

body {
  font-family: "Lato", sans-serif;
  font-weight: 400;
/*  font-size: 16px;*/
  line-height: 1.7;
  color: #777;
  padding: 3rem;
  box-sizing: border-box;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.class {
  
}
</style>
