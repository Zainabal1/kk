<template>
    <header>
    <img class="logo" alt="logo" src="@/assets/logo1.png">
    <div class="menu">
      
      <input name="men" type="radio" id="app" class="tap" >
      <router-link to="/main">
      <label for="home"> Home</label>
    </router-link>
    <router-link to="/about">
        <input  name="men" type="radio" id="About" class="tap" >
      <label for="app">About Us</label>
    </router-link>

      <router-link to="/Featurs">
       <input name="men"  type="radio" id="Featurs" class="tap" checked>
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

    <div class="p">
    <h1> WHY CHOOSE US</h1>
    </div>
    <div class="line-notes"></div>
    </header>
    <id class="box1">
        <img alt="img1" class="img1" src="@/assets/location.png">
     
    </id>
    <id class="box2">
        <img alt="img1" class="img2" src="@/assets/box.png">
    </id>
    <id class="box3">
        <img alt="img3" class="img3" src="@/assets/poll.png">
    </id>
    <id class="box4">
        <img alt="img4" class="img4" src="@/assets/phone.png">
    </id>
    <id class="box5">
        <img alt="img5" class="img5" src="@/assets/man.png">
    </id>
    <id class="box6">
        <img alt="img6" class="img6" src="@/assets/c.png">
    </id>
    <div class="text-1">
      <h1> INSIDE AND OUT SIDE THE REGION</h1>
    </div>
    <div class="pr">
        <p>LOREM IPSUM DOLOR SIT AMET CONESCTEUR.
           FUSCE.LOREM IPSUM DOLORSIT AMET
           CONSECTETUR.FUSE.
        </p>
    </div>

    <div class="text-2">
      <h1> ALL KINDS OF PRODUCT</h1>
    </div>
    <div class="pr2">
        <p>LOREM IPSUM DOLOR SIT AMET CONESCTEUR.
           FUSCE.LOREM IPSUM DOLORSIT AMET
           CONSECTETUR.FUSE.
        </p>
    </div>

    <div class="text-3">
      <h1> FULL COVERAGE</h1>
    </div>
    <div class="pr3">
        <p>LOREM IPSUM DOLOR SIT AMET CONESCTEUR.
           FUSCE.LOREM IPSUM DOLORSIT AMET
           CONSECTETUR.FUSE.
        </p>
    </div>

    <div class="text-4">
      <h1> DELIVERY IN LESS THEN AN HOUR</h1>
    </div>
    <div class="pr4">
        <p>LOREM IPSUM DOLOR SIT AMET CONESCTEUR.
           FUSCE.LOREM IPSUM DOLORSIT AMET
           CONSECTETUR.FUSE.
        </p>
    </div>
    
    <div class="text-5">
      <h1> DOOR PICKUP</h1>
    </div>
    <div class="pr5">
        <p>LOREM IPSUM DOLOR SIT AMET CONESCTEUR.
           FUSCE.LOREM IPSUM DOLORSIT AMET
           CONSECTETUR.FUSE.
        </p>
    </div>

    <div class="text-6">
      <h1> ONLINE PAMENT</h1>
    </div>
    <div class="pr6">
        <p>LOREM IPSUM DOLOR SIT AMET CONESCTEUR.
           FUSCE.LOREM IPSUM DOLORSIT AMET
           CONSECTETUR.FUSE.
        </p>
    </div>
</template>
<style scoped>
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
.p{
  position: absolute;
  top:90px;
  left:2%;
  color:black;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;
}
.line-notes {
  position: absolute;
  width: 96px;
  height: 5px;
  left: 30px;
  top: 170px;
  background: #F5AC01;
 
}
.box1{
position: absolute;
width: 360px;
height: 30%;
left: 30px;
top: 197px;

background: #F9F9F9;
}
.box2{
position: absolute;
width: 360px;
height: 30%;
left: 35%;
top: 197px;

background: #F9F9F9;
}
.box3{
position: absolute;
width: 360px;
height: 30%;
left: 68%;
top: 197px;

background: #F9F9F9;
}
.box4{
position: absolute;
width: 360px;
height: 30%;
left: 68%;
top: 65%;

background: #F9F9F9;
}
.box5{
position: absolute;
width: 360px;
height: 30%;
left: 35%;
top: 65%;

background: #F9F9F9;
}
.box6{
position: absolute;
width: 360px;
height: 30%;
left: 2.4%;
top: 65%;

background: #F9F9F9;
}
.img1{
    position: absolute;
    top:30%;
    left:2em;
    width: 20%;
    height: 35%;

}
.img2{
    position: absolute;
    top:30%;
    left:2em;
    width: 20%;
    height: 35%;

}
.img3{
    position: absolute;
    top:30%;
    left:2em;
    width: 20%;
    height: 35%;

}
.img4{
    position: absolute;
    top:30%;
    left:2em;
    width: 20%;
    height: 35%;

}
.img5{
    position: absolute;
    top:30%;
    left:2em;
    width: 20%;
    height: 35%;

}
.img6{
    position: absolute;
    top:30%;
    left:2em;
    width: 20%;
    height: 35%;

}
.text-1{
    position: absolute;
    font-size: 8px;
    top:40%;
    left:20em;
    width: 243.33px;
    height: 44.3px;
    color:#F5AC01;
    font-family: 'poppins';
}
.pr{
    position: absolute; 
    font-size: 8px;
    top:50%;
    left:20em;
    width: 243.33px;
    height: 44.3px;
    color:#878787;
    font-family: 'poppins';  
}
.text-2{
    position: absolute;
    font-size: 8px;
    top:40%;
    left:70em;
    width: 243.33px;
    height: 44.3px;
    color:#F5AC01;
    font-family: 'poppins';
}
.pr2{
    position: absolute; 
    font-size: 8px;
    top:50%;
    left:70em;
    width: 243.33px;
    height: 44.3px;
    color:#878787;
    font-family: 'poppins';  
}
.text-3{
    position: absolute;
    font-size: 8px;
    top:40%;
    left:123em;
    width: 243.33px;
    height: 44.3px;
    color:#F5AC01;
    font-family: 'poppins';
}
.pr3{
    position: absolute; 
    font-size: 8px;
    top:50%;
    left:123em;
    width: 243.33px;
    height: 44.3px;
    color:#878787;
    font-family: 'poppins';  
}
.text-4{
    position: absolute;
    font-size: 8px;
    top:70%;
    left:20em;
    width: 243.33px;
    height: 44.3px;
    color:#F5AC01;
    font-family: 'poppins';
}
.pr4{
    position: absolute; 
    font-size: 8px;
    top:80%;
    left:20em;
    width: 243.33px;
    height: 44.3px;
    color:#878787;
    font-family: 'poppins';  
}
.text-5{
    position: absolute;
    font-size: 8px;
    top:70%;
    left:70em;
    width: 243.33px;
    height: 44.3px;
    color:#F5AC01;
    font-family: 'poppins';
}
.pr5{
    position: absolute; 
    font-size: 8px;
    top:80%;
    left:70em;
    width: 243.33px;
    height: 44.3px;
    color:#878787;
    font-family: 'poppins';  
}
.text-6{
    position: absolute;
    font-size: 8px;
    top:70%;
    left:125em;
    width: 243.33px;
    height: 44.3px;
    color:#F5AC01;
    font-family: 'poppins';
}
.pr6{
    position: absolute; 
    font-size: 8px;
    top:80%;
    left:125em;
    width: 243.33px;
    height: 44.3px;
    color:#878787;
    font-family: 'poppins';  
}


</style>