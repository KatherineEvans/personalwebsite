<template > 
  <div id="app" > 
    <router-view/> 
  </div > 
</template > 

<style > 

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
  box-sizing: border-box;
  margin: 0;
  height: 100%;
  overflow: hidden;
  background-image: url("../images/outdoors.jpg");
  background-position: right top;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}

.laptop {
  background-image: url("../images/laptop.png");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  min-height: 850px;
  flex-shrink: 0;
  width: 100%;
  padding-top: 69.64%;
}
</style>;
