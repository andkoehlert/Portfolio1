<script setup>


</script>

<template>
  <header>
    <div class="container">
    <nav class="topnav navbar navbar-expand-lg navbar-light bg-light">
        <img src="" alt="">
        <ul  id="myLinks">
            <li><a  href="#About">About</a></li>
            <li><a  href="#kontakt">Contact</a></li>
            <li><a href="#work">My work</a></li>
          
        </ul>
       <!-- <a class="" @click="myFunction()">
  </a> -->
 
    </nav>
    <div class="text-box">
        <p>I'M</p>
        <h1>ANDREAS</h1>
        <h3>I'm a multimedia designer student & I like to do illustration and websites</h3>

        <div class="row">
            <a class="row2" href="../src/assets/CV1.pdf" target="_blank">My CV</a>
            <a class="row2" href="https://www.youtube.com/watch?v=I-BtcYGhNDg" target="_blank">CV video</a>
            <a class="row3" href="">andkoehlet@outlook.com <span>&#x27F6;</span> </a>
            <span> Check out my work down below

            </span>
        </div>
      
    </div>
    <div class="social-icons">
      <a href="https://www.linkedin.com/in/andreas-k%C3%B8hlert-85569a22a/"  target="_blank"><img src="../src/assets/link.png" alt=""></a>

        <a href="mailto: andkoehlert@outlook.com"  target="_blank"><img src="../src/assets/telegram.png" alt=""></a>
        <a href="https://www.instagram.com/andreaskoehlert/
"  target="_blank"><img src="../src/assets/instagram.png" alt=""></a>

       </div>
</div>

<div class="service1">
  <div class="container1">
  <div class="row">
    <div class="col text-center">
      <h3 class="animate-charcter"> Illustrations</h3>
    </div>
  </div>
</div>    
        <div id="work" class="box">
<a href="#work"></a>
          <div class="">
            

     <div class="">   <img class="first-card" src="../src/assets/Artboard7.png" style="height:auto;"  alt="">
     </div>
  
          
          
            
          </div>

          <div class="">
            

            <div class="">   <img class="first-card" src="../src/assets/Artboard1.png" style="height:auto;"  alt="">
            </div>
         
                 
                 
                   
                 </div>
                 
          
        </div>
        <div class="box">
          <div class="">
            

            <div class="">   <img class="first-card" src="../src/assets/Artboard12.png" style="height:auto;"  alt="">
            </div>
         
                 
                 
                   
                 </div>
                     <div class="">
            

     <div class="">   <img class="first-card" src="../src/assets/Artboard16.png" style="height:auto;"  alt="">
     </div>
  
          
          
            
          </div>
         
          
        </div>
       </div>    
  <div class="service1">
        
        
       </div>
       <div class="service2">
        <div class="title">
          <div class="container1">
  <div class="row">
    <div class="col text-center">
      <h3 class="animate-charcter"> Posters & SoMe</h3>
    </div>
  </div>
</div>        </div>
        <div class="box">

          <div class="">
            

     <div class="">   <img class="second-card" src="../src/assets/Blomsterøvelse2.psd.png" style="height:auto;"  alt="">
     </div>
  
          
          
            
          </div>

          <div class="">
            

            <div class="">   <img class="second-card" src="../src/assets/Designøvelse.png" style="height:auto;"  alt="">
            </div>
         
                 
                 
                   
                 </div>
                 
          
        </div>
        <div class="box">
          <div class="">
            

            
         
                 
                 
                   
                 </div>
                     <div class="">
            


  
          
          
            
          </div>
         
          
        </div>
         <div class="service2">
        
   
       </div>
       </div>   
       
       <div id="About" class="box-aboutme">
          <div class="">
            
            <div class="">   <img class="aboutMe-card" src="../src/assets/Aboutphoto.png" style=""  alt="">
     </div>
  
           
         
                 
                 
                   
                 </div>
                     <div 
                     class="aboutMe-text">
                     <h3 class="animate-charcter2"> About me</h3>

            <a href="#About"></a> 
<h1 class="abouth1" >Hello world!</h1>   
<p class="text-info1">
  I'm a multimedia designer student & I like to do illustrations and create websites.
  I'm passionate and dedicate myself 100% to my work. 
  
  </p>
  <h1 class="abouth1" >Hobbies?</h1>   

 <p class="text-info1">I spend alot of time playing and studying music. I also play jazz every thursday. Besides that I also like to do fitness and running. I also have a passion for photography and analyzing movies.
    
</p>   

<h1 class="abouth1" >internship 2023</h1>   

 <p class="text-info1">In january 2023 I will begin my internship. If you think I would fit your company please dont hesitate giving me a call.
    
</p>  
 
          
          
            
          </div>
          
        </div>
<div id="kontakt" class="contact-me" >
  <a href="#"></a>


<p>  Need a webpage or content for social media?
</p>  <a class="button" href="mailto: andkoehlert@outlook.com">Send me an email</a>
<p class="Info">Or give me a call "41 60 22 26"</p>
<div class="social-icons">
      <a href="https://www.linkedin.com/in/andreas-k%C3%B8hlert-85569a22a/"><img src="../src/assets/link.png" alt=""></a>

        <a href="mailto: andkoehlert@outlook.com"><img src="../src/assets/telegram.png" alt=""></a>
        <a href="https://www.instagram.com/andreaskoehlert/
"><img src="../src/assets/instagram.png" alt=""></a>

       </div>
</div>




  </header>
  

  <RouterView />
</template>


<script setup>

function myFunction() {
  var x = document.getElementById("myLinks");
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>


<style scoped>
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}

.topnav a {
  float: left;
  display: block;
  color: #000000;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}


.container{
  
  background-image:url(../src/assets/Artboard11.png);

background-color: #f0f4f6;
    width: 100%;
    height: 100vh;
    background-size: cover;
    background-position: center;
    padding: 0 8%;
    position: relative;

}

nav{
    display: flex;
    width: 100%;
    align-items: center;
    flex-wrap: wrap;
    padding: 5px 0;
}


.cart-icon{
    width: 30px;
    cursor: pointer;
    
}
nav ul{
    flex: 1;
    text-align: right;
    padding-right: 110px;

}

nav ul li{
    display: inline-block;
    list-style-type: none;
    margin: 10px 30px;
}

nav ul li a{
    color: #0e0e0e;
    text-decoration: none;
    position: relative;
}

nav ul li a::after{
    content:'';
    width: 0;
    height: 3px;
    position:absolute;
    bottom: -5px;
    left: 50%;
    transform: translateX(-50%);
    background: #d8d505;
    transition: 0.3s;

}

nav ul li a:hover::after{
    width: 50%;
}


.text-box{
    color: #f5f505;
    position: absolute;
    bottom: 8%;

}

.text-box p{
font-size: 10vw;
font-weight: 0;
}

.text-box h1{
    font-size: 10vw;
    line-height: 80%;
    
    color: transparent;
    -webkit-text-stroke: 1px #ffffff;
    background: url(../src/assets/back.png);
    -webkit-background-clip: text;

    background-position: 0 0;
    animation: back 20s linear infinite; 
   
}
@keyframes back{
    100%{
        background-position: 2000px 0;
    }
}



.row{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    margin-top: 30px;

}

.text-box a{
    color: #ffffff ;
    text-decoration: none;
    padding: 10px 20px;
    margin-right: 20px;
    border: 2px solid #ecdd09;
    display: flex;
    align-items: center;
}



.text-box a span{
    font-size: 30px;
    line-height: 15px;
    margin-left: 5px;
}

.social-icons{
    position: absolute;
    right: 5%;
    bottom: 8%;
}

.social-icons img{
    width: 25px;
    display: block;
    margin: 25px 5px;
}


.service1{
  /*
  background-image: url(../src/assets/bubbel1.png);
*/
 color: #efeb0b;
 background-color: #f0f4f6;
  width: 100%;
}

.service2{
  /*
  background-image: url(../src/assets/bubbel1.png);
*/
 color: #efeb0b;
background-color: rgb(255, 255, 255);
  width: 100%;
}

.animate-charcter
{
   text-transform: uppercase;
  background-image: linear-gradient(
    -225deg,
    #f4e00b 0%,
    #2c99cf 29%,
    #dd8e06 67%,
    #fff800 100%
  );
  background-size: auto auto;
  background-clip: border-box;
  background-size: 200% auto;
  color: #fff;
  background-clip: text;
  text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 5s linear infinite;
  display: inline-block;
      font-size: 8vh;
      text-align: center;
      
}

.animate-charcter2
{
   text-transform: uppercase;
  background-image: linear-gradient(
    -225deg,
    #f4e00b 0%,
    #2c99cf 29%,
    #dd8e06 67%,
    #fff800 100%
  );
  background-size: auto auto;
  background-clip: border-box;
  background-size: 200% auto;
  color: #fff;
  background-clip: text;
  text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 5s linear infinite;
  display: inline-block;
      font-size: 8vh;
      text-align: center;
      
}
.container1 {
  display: grid;
  place-items: center;  
  text-align: center;
  height: vh
}

@keyframes textclip {
  to {
    background-position: 200% center;
  }
}
.box{
  display: flex;

}

.box-aboutme{
  display: flex;
background-color: #f0f4f6;}
.box-aboutme h1{
 color: #20cbe1;
}
.box-aboutme p{
 color: #000000;
}

.first-card {
  object-fit: cover;
  height: 100%;
  width: 90%;
  border: 2px solid #fff;
  border-radius: 20px;
  margin: 5%;
  overflow: hidden;
}
.second-card {
  object-fit: cover;
  height: 100%;
  width: 70%;
  border: 2px solid #fff;
  border-radius: 20px;
  margin: 10% 15% 0% 15%;
  overflow: hidden;
}

.aboutMe-card {
  object-fit: cover;
  height: 100%;
  width: 100%;
  border-radius: 20px;
  margin: 5%;
  overflow: hidden;
}

.aboutMe-text {
  object-fit: cover;
  height: 100%;
  font-size: 1.2em;
  overflow: hidden;
  display: flex;
  flex-direction: column;
}


.Info{
  padding: 1%;
color:#000000;
font-size: 20px;
}






.button{
background-color: #fcf563;
color: #000000;
text-decoration: none;
border: 2px solid transparent;

font-weight: bold;
padding: 9px 22px;
border-radius: 30px;
transition: .4ss;
}

.button:hover{
  background-color: transparent;
  border: 2px solid #e9851b;
  cursor: pointer;
  color: #000000;
}





/* Kontakt mig*/
.contact-me{
  width: 100%;
  height: 290px;
  background-color: #76cbf8;
  color: #000000;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

.contact-me p{
  font-size: 25px;
  font-weight: bold;
  margin-bottom: 25px;
}



/* responsive */
@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }

  .animate-charcter{
    font-size: 3rem;
    
  }
  .box{
flex-direction:column-reverse;  }


.text-info1{

}
.text-info1{
  padding: 1em 0em;
  margin-left: 2em;
  width: 300px;
}

.abouth1{
  margin-left: 1.3em;
font-size: 1.5em;
}


.animate-charcter2
{
   text-transform: uppercase;
  background-image: linear-gradient(
    -225deg,
    #f4e00b 0%,
    #2c99cf 29%,
    #dd8e06 67%,
    #fff800 100%
  );
  background-size: auto auto;
  background-clip: border-box;
  background-size: 200% auto;
  color: #fff;
  background-clip: text;
  text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 5s linear infinite;
  display: inline-block;
      font-size: 3vh;
      margin-left: 1.3em;
      margin-bottom: 1em;

      
}

.social-icons{
    position: absolute;
    right: 1%;
    bottom: 1%;
}

.social-icons img{
    width: 20px;
    display: block;
    margin: 15px 5px;
}

/*ABOUT */


.box-aboutme{
flex-direction: column;

}
.aboutMe-card {
  object-fit: cover;
  height: 100%;
  width: 90%;
  margin: 5%;
  overflow: hidden;
  flex-direction: row-reverse;

}

.aboutMe-text {
  font-size: 15px;
  font-weight: bold;
 
}
.aboutMe-text h1 {

}



.contact-me p{
  font-size: 15px;
  font-weight: bold;
  padding-left: 20px;
}
.contact-me{
  width: 100%;
  height: 150px;
  background-color: #fff;
  color: #000000;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  padding-top: 1.5em;
}

.container{
  height: 80vh;
}

.text-box{
  
}

.text-box a{
    color: #060606 ;
    text-decoration: none;
    padding: 5px 20px;
    margin-right: 20px;
    border: 2px solid #000000;
    align-items: right;
    
}
.text-box p{
  line-height: 10px;

}
.text-box h1{
  line-height: 80px;

}


.row{
display: flex ;
flex-wrap:wrap-reverse;    
margin-top: 30px;

}
.topnav a {
  float: left;
  display: block;
  color: #000000;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}


.container{
  
  background-image:url(../src/assets/Artboard8.png);

background-color: #f0f4f6;
    width: 100%;
    height: 60vh;
    background-size: cover;
    background-position: center;
    padding: 0 8%;
    position: relative;

}

nav{
    display: flex;
    flex-direction: row;
    width: 100%;
    align-items: center;
    flex-wrap: wrap;
    padding: 5px 0;
}


.cart-icon{
    width: 30px;
    cursor: pointer;
    
}
nav ul{
    flex: 1;
    text-align: center;
    padding-right: 10px;

}

nav ul li{
    display: inline-block;
    list-style-type: none;
    margin: 2px 1px;
}

nav ul li a{
    color: #0e0e0e;
    text-decoration: none;
    position: relative;
}


}


</style>

