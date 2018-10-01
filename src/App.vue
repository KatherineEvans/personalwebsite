<template > 
  <div id="app" > 
    <router-view/> 
  </div > 
</template > 

<style > 

html {
  font-size: 62.5%;
}
#app {
  max-width: 1240px; 
  min-width: 1240px;
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
  overflow-y: hidden;
  background-image: url("../images/outdoors.jpg");
  max-width: 1240px; 
  min-width: 1240px;
  background-position: right top;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}

.header {
  text-align: center;
  font-size: 16px;
  color: #DCDCDC;
}
.laptop {
  background-image: url("../images/laptop-green.png");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  position: relative;
  min-height: 850px;
  flex-shrink: 0;
  width: 100%;
  padding-top: 69.64%;
  z-index: 2;
}

/*.laptop_computerScreen {
  background-color: black;
  background-position: center;
  flex-shrink: 0;
  width: 71%;
  height: 56%;
  left: 156px;
  position: absolute;
  top: 40px;
  z-index: 3;
}*/
</style>;
