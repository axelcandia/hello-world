#Maquetado del Html .html
<div class="primer-ejercicio">
  <div class="bloque1"></div>
  <div class="bloque2"></div>
  <div class="bloque3"></div>
  <div class="bloque4"></div>
  <div class="bloque5"></div>
  <div class="bloque6"></div>
  <div class="bloque7"></div>  
</div>

#Contenido del CSS .css

* { 
  -moz-box-sizing: border-box; 
  -webkit-box-sizing: border-box; 
  box-sizing: border-box; 
}

.primer-ejercicio{
  width: 400px;
  height: 460px;
  margin: auto;
  padding: 10px;
  position: relative;

  
}
.bloque1{ 
 width: 50px;
 height: 60px;
 border: 10px solid black;
  }

.bloque2{
 width: 50px;
 height: 120px;
  border: 10px solid black;
  }
.bloque3{
 width: 50px;
 height: 95px;
  border: 10px solid black;
  background: blue;
  position: absolute;
  margin-top: -10px; 
  }
.bloque4{
    margin: 10px 40px;
 width: 170px;
 height: 180px;
  border: 10px solid black;
  background: red;
  position: absolute;
  margin-top: -180px; 
  }
.bloque5{
    margin: 10px 40px;
 width: 130px;
 height: 95px;
  border: 10px solid black;
  position: absolute;
  margin-top: -10px;
  }
.bloque6{
    margin: 10px 160px;
 width: 50px;
  height: 45px;
  border: 10px solid black;
  position: absolute;
  margin-top: -10px;
  
  }
.bloque7{
    margin: 10px 160px;
 width: 50px;
 height: 60px;
  border: 10px solid black;
  position: absolute;
  background: yellow;
  margin-top: 25px;
  
