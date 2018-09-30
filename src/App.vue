<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
html {
  font-size: 62.5%;
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
  background-image: url("http://lichfieldsfurniture.co.uk/wp-content/uploads/2016/10/Cafe-background-1.jpg");
  background-size: cover;
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
</style>
