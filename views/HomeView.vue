<template>
  <div class="backgrond">
    <img alt="background" src="@/assets/car.png">
   
  </div>
  <div class="containr"></div>


  <header>
    <img class="logo" alt="logo" src="@/assets/logo1.png">
    <div class="menu">
      <input name="men" type="radio" id="app" class="tap" checked>
      <label for="app"> Home</label>

      <router-link to="/about">
        <input  name="men" type="radio" id="About" class="tap">
      <label for="app">About Us</label>
      </router-link>

      <router-link to="/Featurs">
       <input name="men"  type="radio" id="Featurs" class="tap">
      <label for="app">Featurs</label>
    </router-link>
    
    <router-link to="/Servics">
      <input name="men"  type="radio" id="Service" class="tap">
      <label for="app">Service</label>
    </router-link>

    <router-link to="/Partner">
      <input name="men"  type="radio" id="Partener" class="tap">
      <label for="app">Partner</label>
    </router-link>

    <router-link to="/Testimonials">
      <input name="men"  type="radio" id="Testimonials" class="tap">
      <label for="app">Testimonials</label>
    </router-link>
    </div>
    <div class="h2">
    <h2>اللغة العربية</h2>
  </div>
    <button class="btn-login">login </button>
    <button class="btn">Track</button>
  </header>

<div class="p1">
  <h1>Safe & Relible Logistic Solution</h1>
</div>
<div class="p2">
  <h6>KNAGER Is App Of Logistic Servics For Drop Shipping Sector.</h6>
</div>
<div class="input">
  <input type="text" placeholder="   Enter Your Order ID">

</div>

</template>

 

<style scoped>



.logo{
  position: absolute;
  top:0;
  width: 10%;
  height: 10%;
  left:0px;
}
.containr{
position: absolute;
bottom: 100;
background: rgba(0,0,0,0.5);
color: white;
width: 96.9%;
height: 93%;
top:0;
padding:20px;
}

header{
  position: absolute;
  background-color:#FAFAFA;
  height:12%;
  width:100%;
}
.logo{
  position: absolute;
  margin-left: 50px;
  width: 10%;
  height: 100%;
}
.menu{
  position: initial;
}
label{
  position: relative;
  margin-left: 40px;
  left: 190px;
  top: 20px;
  font-family: 'poppins';
  color:black;
  padding-bottom:  19px;
 padding-left: 17px;
 padding-top: 20px;
 padding-right: 10px;
 cursor: pointer;

}
input:checked +label{
  background-color: #F5AC01;
  color: #FAFAFA;
 
  
}

.tap{
  display: none;
}
a:link{
  text-decoration: none;
}
.btn-login{
 
  box-sizing: border-box;
  position: absolute;
  width: 110px;
  height: 50px;
  left: 90%;
  border:none;
  top: 10%;
  background: #F5AC01;
  border-radius: 9.69444px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 30px;
  text-transform: capitalize;
  color: #FFFFFF;
}
.h2{
  position: absolute;
  top:1.6em;
  left:80%;
  font-size: 13px;
}





.p1{
  position: absolute;
  top:240px;
  left:40px;
  width:440px;
  font-size:20px;
  font-family: 'poppins';
  color: #FAFAFA;

}
.p2{
  position: absolute;
  font-family: 'poppins';
  color: #FAFAFA; 
  font-size:20px;
  width:370px;
  top:370px;
  left:40px;
}
.input{
  box-sizing: border-box;
  width: 400px;
  height: 60px;
  top:-100px;
  left:3em;
  border: 0.969445px solid #546076;
  border-radius: 9.69444px;
  position: relative;
}
.btn{
  box-sizing: border-box;
  position: absolute;
  width: 110px;
  height: 50px;
  left: 40%;
  border:none;
  top: 490px;
  background-color: #F5AC01;
  border-radius: 9.69444px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 30px;
  text-transform: capitalize;
  color: #FFFFFF;
}

</style>
