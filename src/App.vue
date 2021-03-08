<template>
  <div id="app">
    
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
*{
  margin: 0;
  padding:0 ;
  box-sizing: border-box;
}

#app{
  width: 100vw;
  height: 100vh;
  background-color: #F2F3FB;
  display: flex;
  align-items: center;
  justify-content: center;
}
#card{
  background-color: #fff;
  width: 700px;
  height:500px;
  max-width: 100%;
  max-height: 100%;
  box-shadow: 10px 10px 15px #ACACAC, -10px -10px 15px #ACACAC;
  position: absolute;
}
#header{
  width: 100%;
  height: 20%;
  max-height: 100px;
  background: linear-gradient(to left, #5ccde1 29%, #29d4ff 71%);
  color: #fff;
  text-align: center;
  padding: 10px;
}
#content{
  position: relative;
  z-index: 2;
  left: 10%;
  top: -5%;
  width: 80%;
  height:70%;
  max-width: 100%;
  max-height: 80%;
  background-color: #fff;
  /* box-shadow: 5px 5px 5px #ACACAC, -5px -5px 5px #ACACAC; */
  box-shadow: 15px 11px 8px -4px rgba(172,172,172,0.23), -15px -11px 8px -4px rgba(172,172,172,0.23);
}
#footer{
  position: relative;
  bottom: 0;
  width: 100%;
  height: 20%;
  max-height: 100px;
  text-align: center;
}
.btn{
  background-color: transparent;
  border: 1px solid #5ccde1;
  cursor: pointer;
  border-radius: 5px;
  color: #5ccde1;
  font-size: 20px;
  padding: 5px 10px;
  transition: all 0.5s ease-in-out;
}
.btn:hover{
  background-color: #5ccde1;
  color: #fff;
}
</style>
