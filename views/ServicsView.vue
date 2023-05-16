<template>
    <div class="background"></div>
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
       <input name="men"  type="radio" id="Featurs" class="tap" >
      <label for="app">Featurs</label>
    </router-link>
    
    <router-link to="/Servics">
      <input name="men"  type="radio" id="Service" class="tap" checked>
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
    <h1> MULTIPLE JOBS AND MORE</h1>
    </div>
    <div class="line-notes"></div>
    <id class="box1">
        <img alt="img1" class="img1" src="@/assets/food.svg">
    
    </id>
    <div class="word-1">
    <h1>Restaurants</h1>
    </div>
    <id class="box2">
        <img alt="img2" class="img2" src="@/assets/sch.svg">
        <div class="i2">
        <img alt="img2" class="img2" src="@/assets/sche.svg">
        </div>
      
    </id>
    <div class="word-2">
        <h1>Scheduling</h1>
    </div>

    <id class="box3">
        <img alt="img3" class="img3" src="@/assets/sch.svg">
        <div class="i3">
        <img alt="img3" class="img3" src="@/assets/foodd.svg">
        </div>
      
    </id>
    <div class="word-3">
        <h1>Food</h1>
    </div>

    <id class="box4">
        <img alt="img4" class="img4" src="@/assets/sch.svg">
        <div class="i4">
        <img alt="img4" class="img4" src="@/assets/EC.svg">
        </div>
      
    </id>
    <div class="word-4">
        <h1>Ecommerce</h1>
    </div>

    <id class="box5">
        <img alt="img5" class="img5" src="@/assets/sch.svg">
        <div class="i5">
        <img alt="img5" class="img5" src="@/assets/shopping.svg">
        </div>
      
    </id>
    <div class="word-5">
        <h1>Shopping Companies</h1>
    </div>

    <id class="box6">
        <img alt="img6" class="img6" src="@/assets/sch.svg">
        <div class="i6">
        <img alt="img6" class="img6" src="@/assets/ice-k.svg">
        </div>
      
    </id>
    <div class="word-6">
        <h1>Bakeries And Sweets</h1>
    </div>

    <id class="box7">
        <img alt="img7" class="img7" src="@/assets/sch.svg">
        <div class="i7">
        <img alt="img7" class="img7" src="@/assets/pub.svg">
        </div>
      
    </id>
    <div class="word-7">
        <h1>Publishing Companies</h1>
    </div>

    <id class="box8">
        <img alt="img8" class="img8" src="@/assets/sch.svg">
        <div class="i8">
        <img alt="img8" class="img8" src="@/assets/tr.svg">
        </div>
      
    </id>
    <div class="word-8">
        <h1>Transportation</h1>
    </div>

    <id class="box9">
        <img alt="img9" class="img9" src="@/assets/sch.svg">
        <div class="i9">
        <img alt="img9" class="img9" src="@/assets/co.svg">
        </div>
      
    </id>
    <div class="word-9">
        <h1>Goverment Facilities</h1>
    </div>

    <id class="box10">
        <img alt="img10" class="img10" src="@/assets/sch.svg">
        <div class="i10">
        <img alt="img10" class="img10" src="@/assets/com.svg">
        </div>
      
    </id>
    <div class="word-10">
        <h1>Commercial Facilities</h1>
    </div>

    <id class="box11">
        <img alt="img11" class="img11" src="@/assets/sch.svg">
        <div class="i11">
        <img alt="img11" class="img11" src="@/assets/pro.svg">
        </div>
      
    </id>
    <div class="word-11">
        <h1>Productive Families</h1>
    </div>

    <id class="box12">
        <img alt="img12" class="img12" src="@/assets/sch.svg">
        <div class="i12">
        <img alt="img12" class="img12" src="@/assets/o.svg">
        </div>
      
    </id>
    <div class="word-12">
        <h1>Mobile Application</h1>
    </div>
    </header>
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
.background{
    background-color:#F5AC01; 
    width: 100%;
    height: 100%;
    padding: 0;
    margin-left: 0;
    left: 0;
}
.p{
  position: absolute;
  top:90px;
  left:2%;
  color:#FAFAFA;
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
  background: #FAFAFA;
 
}
.box1{
    position: absolute;
    top:200px;
    left:-590px;
}
.word-1{
 position: absolute;
  top:210px;
  left:6em;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box2{
    position: absolute;
    top:300px;
    left:-590px;
}
.i2{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-2{
 position: absolute;
  top:300px;
  left:6em;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box3{
    position: absolute;
    top:400px;
    left:-590px;
}
.i3{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-3{
 position: absolute;
  top:400px;
  left:6em;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box4{
    position: absolute;
    top:500px;
    left:-590px;
}
.i4{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-4{
 position: absolute;
  top:500px;
  left:6em;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box5{
    position: absolute;
    top:200px;
    left:-17em;
}
.i5{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-5{
 position: absolute;
  top:210px;
  left:410px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box6{
    position: absolute;
    top:300px;
    left:-17em;
}
.i6{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-6{
 position: absolute;
  top:310px;
  left:410px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box7{
    position: absolute;
    top:400px;
    left:-17em;
}
.i7{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-7{
 position: absolute;
  top:410px;
  left:410px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box8{
    position: absolute;
    top:490px;
    left:-17em;
}
.i8{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-8{
 position: absolute;
  top:500px;
  left:410px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box9{
    position: absolute;
    top:200px;
    left: 17%;
}
.i9{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-9{
 position: absolute;
  top:210px;
  left:910px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box10{
    position: absolute;
    top:300px;
    left: 17%;
}
.i10{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-10{
 position: absolute;
  top:310px;
  left:910px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box11{
    position: absolute;
    top:390px;
    left: 17%;
}
.i11{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-11{
 position: absolute;
  top:400px;
  left:910px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}
.box12{
    position: absolute;
    top:490px;
    left: 17%;
}
.i12{
  position: absolute;
    top:20px;
    left:2px;
    height: 60%;
}
.word-12{
 position: absolute;
  top:500px;
  left:910px;
  color:#FAFAFA;
  width: 552.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 16px;  
}


</style>