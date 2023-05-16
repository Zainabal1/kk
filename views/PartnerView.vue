<template>
    
<header>
    <img class="logo" alt="logo" src="@/assets/logo1.png">
    <div class="menu">
      <input name="men" type="radio" id="app" class="tap">
      <router-link to="/main">
      <label for="app"> Home</label>
        </router-link>
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
      <input name="men"  type="radio" id="Partener" class="tap"  checked>
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

    <div class="p">
    <h1> OUR AWESOME PARTNER</h1>
    </div>
    <div class="line-notes"></div>

  <div class="box-one"><img src="@/assets/K1.svg"></div>
  <div class="box-two"><img src="@/assets/K1.svg"></div>
  <div class="box-tree"><img src="@/assets/K1.svg"></div>
  <div class="box-for"><img src="@/assets/K1.svg"></div>
  <div class="box-five"><img src="@/assets/K1.svg"></div>

    

    <div class="row-line"></div>
    <div class="row-line2"></div>

    <div id="circul"></div>
    <div class="mobile"><img src="@/assets/Shadow.svg"></div>
<div class="mo2"><img src="@/assets/mm.svg"></div>
<div class="mo3"><img src="@/assets/mo.svg"></div>




  

<div class="p2">
    <h1> DO YOU WANT TO INCREASE YOUR INCOME BY
        JOINING KNAGER?
    </h1>
    </div>

    <div class="star"><img src="@/assets/star.svg"></div>
    <div class="star2"><img src="@/assets/star.svg"></div>
    <div class="star3"><img src="@/assets/star.svg"></div>
    <div class="star4"><img src="@/assets/star.svg"></div>
    <div class="star5"><img src="@/assets/star.svg"></div>
    <div class="star6"><img src="@/assets/star.svg"></div>
    <div class="star7"><img src="@/assets/star.svg"></div>



    <div class="t1">
    Unlimited Reception Of Requests
</div>

<div class="t2">
 Requests From Stores And Individuals
</div>

<div class="t3">
Sort As Per Your Wish Accurate Delivery Confirmation
</div>

<div class="t4">
Rewarding Profits For Each Request
</div>

<div class="t5">
Arrived The Order With Your Car Or Bike
</div>

<div class="t6">
  Branch Delivery Support
</div>
<div class="t7">
100% Advance Payment
</div>

<div class="google"><img src="@/assets/google.svg"></div>
<div class="app2"><img src="@/assets/apple.svg"></div>


<div class="b"><img src="@/assets/b.svg"></div>
<div class="containr"></div>
<div class="text"><h1>LINK YOUR ONLINE STORE OR FACILITIES NOW WITH KNAGER</h1></div>
<div class="text-2"><p>AND ADD EXPRESS DELIVERY SERVICE TO THE GROWTH AND DEVELOPMENT OF YOUR BUSINESS</p></div>

<button class="btn">Order A Captain Now </button>
    </header>
    
   

</template>




<style scoped>

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
.p2{
  position: absolute;
  top:600px;
  left:58%;
  color:black;
  width: 522.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 10px;
}
.line-notes {
  position: absolute;
  width: 96px;
  height: 5px;
  left: 30px;
  top: 170px;
  background: #F5AC01;
 
}
.box-one{
    position: absolute;
    top:250px;
    left:-540px;
    height:  200%;
}

.box-two{
    position: absolute;
    top:250px;
    left:-320px;
    height:  200%;
}
.box-tree{
    position: absolute;
    top:250px;
    left:-100px;
    height:  200%;
}
.box-for{
    position: absolute;
    top:250px;
    left:150px;
    height:  200%;
}
.box-five{
    position: absolute;
    top:250px;
    left:400px;
    height:  200%;
   
}
.row-line {
  box-sizing: border-box;
  position: absolute;
  width: 500px;
  height: 100px;
  top: 600%;
  left: 1%;
  border-bottom: 1px solid rgba(164, 180, 203, 0.5);
}
.row-line2 {
  box-sizing: border-box;
  position: absolute;
  width: 500px;
  height: 100px;
  top: 600%;
  left: 60%;
  border-bottom: 1px solid rgba(164, 180, 203, 0.5);
}
#circul {
  position: absolute;
  height: 400px;
  width: 400px;
  top: 650px;
  left:2em;
  background-color: #FDEECA;
  border-radius: 50%;
  display: inline-block;
}
.mobile{
position: absolute;
height: 500px;
width: 400px;
  top: 660px;
  left:2.5em;
}
.mo2{
    position: absolute;
height: 400px;
width: 400px;
  top: 660px;
  left:2.5em; 
}
.mo3{
    position: absolute;
height: 340px;
width: 400px;
  top: 690px;
  left:2.5em; 
}
.star{
    position: absolute;
    height: 50%;
    top:700px;
    left:8em;

}
.star2{
    position: absolute;
    height: 50%;
    top:750px;
    left:8em;

}
.star3{
    position: absolute;
    height: 50%;
    top:800px;
    left:8em;

}
.star4{
    position: absolute;
    height: 50%;
    top:850px;
    left:8em;


}
.star5{
    position: absolute;
    height: 50%;
    top:900px;
    left:8em;


}
.star6{
    position: absolute;
    height: 50%;
    top:950px;
    left:8em;


}
.star7{
    position: absolute;
    height: 50%;
    top:1000px;
    left:8em;


}
.t1{
    position: absolute;
    height: 50%;
    top:710px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t2{
    position: absolute;
    height: 50%;
    top:750px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t3{
    position: absolute;
    height: 50%;
    top:800px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t4{
    position: absolute;
    height: 50%;
    top:850px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t5{
    position: absolute;
    height: 50%;
    top:900px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t6{
    position: absolute;
    height: 50%;
    top:950px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t7{
    position: absolute;
    height: 50%;
    top:1000px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}

.google{
    position: absolute;
    top:1500%;
    left:200px;
    height: 70%;
}
.app2{
    position: absolute;
    top:1500%;
    left:400px;
    height: 70%;
}
 .b{
  position: absolute;
  width: 1550px;
height: 280px;
left: -10em;
top: 1190px;
 }
 .containr{
position: absolute;
bottom: 100;
background: rgba(0,0,0,0.5);
color: white;
width: 1380px;
height: 240px;
left: -10em;
top: 1190px;
padding:20px;
}
.text{
  position: absolute;
  top: 1250px;
  text-align: center;
  color:#FAFAFA;
  font-family:'poppins';
  font-size: 16px;
}
.text-2{
  position: absolute;
  top: 1320px;
  width: 550px;
  left:400px;
  text-align: center;
  color:#FAFAFA;
  font-family:'poppins';
  font-size: 19px;
}
.btn{
 
 box-sizing: border-box;
 position: absolute;
 width: 300px;
 height: 50px;
 left: 40%;
 border:none;
 top: 1400px;
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
</style>