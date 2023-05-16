<template>
  <div class="about">
    <img alt="background" src="@/assets/about.png">
    <div class="containr"></div>
    <div class="h1">
      <p> ABOUT US</p>
    </div>
    <div class="h2">
      <h1> WE ARE KNAGER</h1>
    </div>
    <div class="h3">
      <p>An Electronic Platform Established In 
        2017 That Seeks To Be The Leader In Logistic
        Services Through A Wide 
        Network Of Companies And Individuals And
        A feet Of Drivers Available Around The 
        Clock Through The Region
         </p>
    </div>
    <div class="line-notes"></div>
  </div>
  <header>
    <img class="logo" alt="logo" src="@/assets/logo1.png">
    <div class="menu">
      
      <input name="men" type="radio" id="app" class="tap" >
      <router-link to="/main">
      <label for="home"> Home</label>
    </router-link>
     
        <input  name="men" type="radio" id="About" class="tap"  checked>
      <label for="app">About Us</label>
    

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
    <div class="h">
     <h2>اللغة العربية</h2>
  </div>
    <button class="btn-login">login </button>
    </header>
</template>
<style scoped>
.containr{
position: absolute;
bottom: 100;
background: rgba(0,0,0,0.5);
color: white;
width: 548px;
height: 439px;
top: 100px;
left:25%;
padding:20px;
}
.logo{
  position: absolute;
  top:0;
  width: 10%;
  height: 100%;
  margin-left: 50px;
}
header{
  position: absolute;
  background-color:#FAFAFA;
  height:12%;
  width:100%;
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
.h{
  position: absolute;
  top:1.6em;
  left:80%;
  font-size: 13px;
}

.h1{
  position: relative;
  top:-70%;
  left:30%;
  color:#FAFAFA;
  width: 86.88px;
  height: 12.8px;
  font-family:'poppins';
  font-size: 17px;
}
.h2{
  position: relative;
  top:-69%;
  left:30%;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 17px;
}
.h3{
  position: relative;
  top:-50%;
  left:30%;
  color:#FAFAFA;
  width: 520px;
  height: 200.88px;
  font-family:'poppins';
  font-size: 17px;
}
.line-notes {
  position: absolute;
  width: 96px;
  height: 5px;
  left: 380px;
  top: 270px;
  background: #F5AC01;
 
}



</style>