<template>
  <div id="box-01">
    <!-- inicio da parte da logo-->
    <div id="logo">
      <div class="logo-img">
        <img src="https://holu.com.br/assets/img/holu-logo.webp">
      </div>
    </div>
    <!-- fim da parte da logo-->

    <!-- inicio da parte do menu-->
    <div id="menu">
      <ul class="menu">
      <li><a href="#">Home</a></li>
      <li><a href="Footer.vue">Como funciona a energia solar?</a></li>
      <li><a href="#">Quem somos</a></li>
      <li><a href="#">Seja um indicador Holu</a></li>
      <li><a href="#">Projetos concluidos</a></li>
      </ul>
    </div>
    <!-- fim da parte do menu-->

    <!-- inicio da parte do botão do menu -->
    <div id="menu-button">
      <div class="menu-button">
        <input type="button" name="nome" value="Faça uma simulação" placeholder="Seu Nome" />
      </div>
    </div>
    <!-- fim da parte do botão do menu-->
  </div>
</template>

<script>
export default {
  name: "Header",
  components: {},
};
</script>

<style scoped>
#box-01 {
  width: 100%;
  height: 100px;
  background-color: #f18c68;
  align-items: center;
}

#logo {
  width: 200px;
  height: 100px;
  float: left;
  align-items: center;
}
.logo-img img{
  width: 200px;
  height: 80px;
  margin-top: 10px;
  
}

#menu {
  width: 850px;
  height: 100px;
  margin-left: 5px;
  float: left;
}
.menu{
list-style:none;
float:left;
margin-top: 40px;
}
.menu li{
position:relative;
float:left;
border-right:1px solid #fff;
font-family: Arial, Helvetica, sans-serif;
}
.menu li a{color:rgb(255, 255, 255); text-decoration:none; padding:5px 10px; display:block;}

.menu li a:hover{
-moz-box-shadow:0 3px 10px 0 #fff;
-webkit-box-shadow:0 3px 10px 0 #fff;
text-shadow:0px 0px 5px #fff;
}
.menu li  ul{
position:absolute;
top:25px;
left:0;
background-color:#fff;
display:none;
}
.menu li ul li{
display:block;
width:150px;
}
#menu-button{
   width: 250px;
  height: 100px;
  margin-right: 10px;
  float: right;
}
input{
  width: 200px;
  height: 50px;
  border-radius: 20px;
  border: 1px;
  margin-top: 25px;
  color: #f18c68;
  font-size: 15px;

}
input:hover{
  background-color: #28ae47;
  color: #fff;
  border-color: #fff;
  border: 2px;
}


</style>
