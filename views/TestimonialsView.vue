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
      <input name="men"  type="radio" id="Partener" class="tap" >
      <label for="app">Partner</label>
    </router-link>

    <router-link to="/Testimonials">
      <input name="men"  type="radio" id="Testimonials" class="tap" checked>
      <label for="app">Testimonials</label>
    </router-link>
    </div>
    <div class="h2">
    <h2>اللغة العربية</h2>
  </div>
    <button class="btn-login">login </button>

    <div class="p">
    <h1> WHAT OUR CLIENT SAY</h1>
    </div>
    <div class="line-notes"></div>

    <div class="note"><p>LOREM IPSUIM DOLOR SIT AMET CONSECTETUR.IN NUNC MASSA NETUS QUIS NISI
      INTERDUM.PROIN MORBI BLANDIT NON VEL SEMPER ENIM.
      LOREM IPSUM DOLOR SIT AMET CONSECTETUR.IN NUNC MASSA NETUS QUIS NISI
      INTRDUM.PROIN MORBI BLANDIT NON VEL SEMPER ENIM.
    </p></div>


    <div class="img"><img src="@/assets/mann.svg"></div>
    <div class="name"><p>Ali Ahmed</p></div>
    <div class="n"><p>Fashion Company</p></div>

    <div class="box">
      <div class="p2">
    <h1> Always Listening , Always
      understanding
    </h1>

      </div>
      <div class="input">
  <input type="text">

</div>
    </div>

    <button class="btn">Send </button>

  <div class="backgrond"></div>

  <img class="logo2"  src="@/assets/logo2.svg">
  <div class="note2"><p>An Electronice Platform Established In 2017 That<br>
                       Seeks To Be The First Platform In Logistics Services<br>
                       And The Leader In Delivery And Freight Services
    </p></div>

    <img class="logo3"  src="@/assets/logo3.svg">
    <div class="p4">
    <h1>Tax Number:345644245252525</h1>

      </div>

      <div class="p3">
    <h1>Line Company For<br>
      Programming And Marketing
     </h1>

      </div>

      <div class="p5">
    <h1>Quick Links</h1>
    

      </div>
      <div class="arrow1"><img src="@/assets/arrow.svg">
      <div class="arrow-t"><h1>Terms A nd Conditions</h1></div>
      </div>
      <div class="arrow2"><img src="@/assets/arrow.svg">
      <div class="arrow-t2"><h1>Privacy Of Use</h1></div>
      </div>
      <div class="arrow3"><img src="@/assets/arrow.svg">
        <div class="arrow-t3"><h1>Return Policy</h1></div>
    </div>
      <div class="arrow4"><img src="@/assets/arrow.svg">
        <div class="arrow-t4"><h1>Business Cooperation</h1></div>
      </div>
      <div class="arrow5"><img src="@/assets/arrow.svg">
        <div class="arrow-t5"><h1>Developers Portal</h1></div>
        <div class="arrow-t6"><h1>@Copyrights 2022 Knagr .All Reservec</h1></div>
      </div>



  <div class="p6"><h1>Get In Touch</h1></div>

  <div class="info"><img src="@/assets/tax.svg"></div>
   <div class="info2"> <img src="@/assets/mail.svg"></div>
   <div class="info3"> <img src="@/assets/loc.svg"></div>
  
  <div class="lcon"><img src="@/assets/Saudi.svg"></div>
  <div class="lcon2"><img src="@/assets/stc.svg"></div>
  <div class="lcon3"><img src="@/assets/visa.svg"></div>
  <div class="lcon4"><img src="@/assets/whats.svg"></div>
  <div class="lcon5"><img src="@/assets/insta.svg"></div>
  <div class="lcon6"><img src="@/assets/tw.svg"></div>

    
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
.line-notes {
  position: absolute;
  width: 96px;
  height: 5px;
  left: 30px;
  top: 170px;
  background: #F5AC01;
 
}
.note{
  position: absolute;
  color:#898989;
  top: 250px;
  left: 2em;
  width: 540px;
  height: 93.8px;
  font-family:'poppins';
  font-size: 16px;

}
.img{
  position: absolute;
  top: 400px;
  left:-45%;
}
.name{
  position: absolute;
  top: 410px;
  left: 7em;
  color: #353535;
  font-size: 16px;
  font-family:'poppins';


}
.n{
  position: absolute;
  top: 440px;
  left: 7.7em;
  color:#878787;
  font-size: 14px;
  font-family:'poppins';
}
.box{
position: absolute;
width: 460px;
height: 500%;
left: 750px;
top: 197px;

background: #F9F9F9;
}
.p2{
  position: absolute;
  font-size: 13px;
  top:3em;
  left:6em;
  font-family:'poppins';
}
.input{
position: absolute;
width: 330px;
height: 45%;
left: 80px;
top: 130px;
background: white;
}
.btn{
 
 box-sizing: border-box;
 position: absolute;
 width: 300px;
 height: 40px;
 left: 67%;
 border:none;
 top: 500px;
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
.backgrond{
  background-color: #F5AC01;
  position: absolute;
  width: 1420px;
  height: 390px;
  left: -10em;
  top: 690px;
}
.logo2{
  position: absolute;
  top:730px;
  margin-left: 50px;
  width: 10%;
  height: 100%;
}
.note2{
position: absolute;
width: 390px;
height: 90.61px;
left: 60px;
top: 820px;
color: #FAFAFA;
font-size: 13px;
font-family: 'Poppins';
}
.logo3{
  position: absolute;
  top:930px;
  margin-left: 50px;
  width: 10%;
  height: 60%;

}
.p3{
  position: absolute;
width: 390px;
height: 90.61px;
left: 200px;
top: 940px;
color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.p4{
  position: absolute;
width: 390px;
height: 90.61px;
left: 50px;
top: 990px;
color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.p5{
  position: absolute;
  top: 750px;
  left:550px;
  color: #FAFAFA;
font-size: 10px;
font-family: 'Poppins';
}
.arrow1{
  position: absolute;
  top: 790px;
  left:-5em;
  height: 20%;
}
.arrow2{
  position: absolute;
  top: 830px;
  left:-5em;
  height: 20%;
}
.arrow3{
  position: absolute;
  top: 870px;
  left:-5em;
  height: 20%;
}
.arrow4{
  position: absolute;
  top: 910px;
  left:-5em;
  height: 20%;
}
.arrow5{
  position: absolute;
  top: 950px;
  left:-5em;
  height: 20%;
}
.arrow-t{
  position: absolute;
  top: 0em;
  left:650px;
  color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.arrow-t2{
  position: absolute;
  top: 0.5em;
  left:650px;
  color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.arrow-t3{
  position: absolute;
  top: 0.5em;
  left:650px;
  color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.arrow-t4{
  position: absolute;
  top: 0em;
  left:650px;
  color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.arrow-t5{
  position: absolute;
  top: 0em;
  left:650px;
  color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.arrow-t6{
  position: absolute;
  top: 6em;
  left:620px;
  color: #FAFAFA;
font-size: 5px;
font-family: 'Poppins';
}
.p6{
  position: absolute;
  top: 750px;
  left:960px;
  color: #FAFAFA;
font-size: 10px;
font-family: 'Poppins';
}
.info{
  position: absolute;
  top: 790px;
  left:390px;
  height: 30%;
  
}
.info2{
  position: absolute;
  top: 830px;
  left:390px;
  height: 30%;
  
}
.info3{
  position: absolute;
  top: 870px;
  left:420px;
  height: 30%;
  
}
.lcon{
  position: absolute;
  top: 920px;
  left:360px;
  height: 30%;

}
.lcon2{
  position: absolute;
  top: 920px;
  left:420px;
  height: 30%;

}
.lcon3{
  position: absolute;
  top: 920px;
  left:480px;
  height: 30%;

}
.lcon4{
  position: absolute;
  top: 960px;
  left:350px;
  height: 30%;

}
.lcon5{
  position: absolute;
  top: 960px;
  left:420px;
  height: 30%;

}
.lcon6{
  position: absolute;
  top: 960px;
  left:480px;
  height: 30%;

}
</style>