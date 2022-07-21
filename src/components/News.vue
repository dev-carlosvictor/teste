<template>
  <div id="box-02">
    <div id="text-left-top">
      <h1 class="text1">Você ja viu energia solar <u>antes</u>!</h1>
      <h2 class="text2">mas nunca viu uma experiência assim</h2>
    </div>
     <div id="text2-left-top">
      <div class="text2-left-top">
      <img src="https://www.otovo.com/images/animated-svg/houses.svg"/>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "News",
  components: {},
};
</script>

<style scoped>
#box-02 {
  width: 100%;
  height: 500px;
  background-color: #2b4898;
}
#text-left-top{
  width: 50%;
  height: 500px;
  float: left;
  
  
}
.text1{
  color:#fff;
  float: left;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 55px;
  margin-left: 40px;
  margin-top: 100px; 
}
.text2{
  color:#f18c68;
  float: left;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 25px;
  margin-left: 40px;
  
}
#text2-left-top{
  width: 50%;
  height: 500px;
  float: right;
}
.text2-left-top{
  width: 450px;
  height: 500px;
  float: right;
  margin-top: 30px;
  margin-right: 100px;
}
 * {
     margin: 0 auto;
     padding: 0 0 0 0;
 }

</style>
