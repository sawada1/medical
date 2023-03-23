<template>
  <div>
  <div class="landing" id="hero" data-aos="zoom-in" data-aos-duration="3000">
   <div class="image">
    <img :class="{active : theimage == 1}"  src="../assets/images/slider/pic1.jpg" alt="">   
    <img  :class="{active : theimage == 2}"  src="../assets/images/slider/pic2.jpg" alt="">   
    <img :class="{active : theimage == 3}"  src="../assets/images/slider/pic3.jpg" alt="">  
   
   </div>
   <div class="boxx">
   <h3>better
    <div class="animated-info">
    <span class="animated-item">health</span>
    <span class="animated-item">days</span>
    <span class="animated-item">lives</span>
   </div> 
  </h3>
   <p>Lorem ipsum dolor sit amet, 
   consectetur adipisicing elit.
    Quo hic nobis nisi accusamus beatae autem?</p>
    <div class="btnss">
     <button class="btn">LEARN MORE</button>
     <span>01021189596</span>
    </div>
   </div>
  
  </div>

  <div class="aboutt" id="about">
   <div class="text">
    <h4>meet dr. khaled</h4>
    <p>Protect yourself and others
     by wearing masks and washing 
     hands frequently. Outdoor is
      safer than indoor for 
      gatherings or holding events. 
      People who get sick with Coronavirus disease (COVID-19) 
    will experience mild to modera
    te symptoms and recover without special treatments.</p>
   </div>
   <div class="years" id="yearss">
    <h2>{{ years }} <span>years of experience</span></h2>
   </div>
  </div>


<div class="imagess">
 <div class="image">
  <img src="../assets/images/gallery/female-doctor-with-presenting-hand-gesture.jpg" alt="">
  <span></span>
 </div>
 <div class="image">
  <img src="../assets/images/gallery/medium-shot-man-getting-vaccine.jpg" alt="">
  <span></span>
 </div>
</div>

<div class="timeline" id="time">
<h2>our timeline</h2>
<div class="maincont">

  <div class="cont right">
    <i class="fa-solid fa-circle-check"></i>
  <div class="thetext">
    <div class="tex">
    <h3>get the vaccine</h3>
  </div>
     
      <p>Lorem ipsum dolor sit amet, 
      consectetur adipisicing elit.
       Ipsum, asperiores.</p>
       <span></span>
       <p>2023-07-15 Thursday</p>  
  </div>

    </div>

  <div class="cont left">
    <i class="fa-solid fa-book-open"></i>

  <div class="thetext">
    <div class="tex">
    <h3>Consulting your health</h3>
  </div>
     
      <p>Lorem ipsum dolor sit amet, 
      consectetur adipisicing elit.
       Ipsum, asperiores asask jlka skajska ksjalksjak sjlaksjk lksjlaksj laksjalk.</p>
       <span></span>
       <p>2023-07-15 Thursday</p>  
  </div>

    </div>
  <div class="cont right">
    <i class="fa-solid fa-receipt"></i>

  <div class="thetext">
    <div class="tex">
    <h3>Certified Nurses</h3>
  </div>
     
      <p>Lorem ipsum dolor, sit amet consectetur 
      adipisicing elit. Incidunt illum consectetur,
       nesciunt cupiditate a nisi facere at commodi
        sunt, veniam facilis quas 
      fugit distinctio assumenda! 
      Recusandae maxime dolorum 
      necessitatibus consequuntur?</p>
       <span></span>
       <p>2023-07-15 Thursday</p>  
  </div>

    </div>
  <div class="cont left">
    <i class="fa-solid fa-globe"></i>
  <div class="thetext">
    <div class="tex">
    <h3>Covid-19 Hospitals</h3>
  </div>
     
      <p>Lorem ipsum dolor, sit amet consectetur 
      adipisicing elit. Incidunt illum consectetur,
       nesciunt cupiditate a nisi facere at commodi
        sunt, veniam facilis quas 
      fugit distinctio assumenda! 
      Recusandae maxime dolorum 
      necessitatibus consequuntur?</p>
       <span></span>
       <p>2023-07-15 Thursday</p>  
  </div>

    </div>


</div>
 
</div>


<div class="patents" id="patents">
<h2>Our Patients</h2>
<div class="mainbox">
  <swiper
    :slidesPerView="1"
    :spaceBetween="10"
    :pagination="{
      clickable: true,
    }"
    :scrollbar="{ draggable: true }"
    navigation
    :breakpoints="{
      '640': {
        slidesPerView: 1,
        spaceBetween: 20,
      },
      '768': {
        slidesPerView: 2,
        spaceBetween: 40,
      },
      '1024': {
        slidesPerView: 3,
        spaceBetween: 50,
      },
    }"
    :modules="modules"
    :autoplay="{
      delay: 2500,
      disableOnInteraction: false,
    }"
    class="mySwiper"
  >
    <swiper-slide>
     <div class="stars">
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-regular fa-star"></i>
     </div>
     <h3>great services</h3>
     <p>Lorem ipsum dolor sit amet 
     consectetur, adipisicing elit.
      Assumenda labore et possimus. 
      Quae nemo, quas assumenda ab 
      voluptas culpa fuga.</p>
      <div class="theimage">
         <img src="../assets/images/reviews/1.jpeg" alt="">
         <div class="text">
          <h5>khaled sawada</h5>
          <span>recoverd</span>
         </div>
      </div>
    </swiper-slide>
    <swiper-slide>
     <div class="stars">
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-regular fa-star"></i>
     </div>
     <h3>best advices</h3>
     <p>Lorem ipsum dolor sit amet 
     consectetur, adipisicing elit.
      Assumenda labore et possimus. 
      Quae nemo, quas assumenda ab 
      voluptas culpa fuga.</p>
      <div class="theimage">
         <img src="../assets/images/reviews/2.jpeg" alt="">
         <div class="text">
          <h5>khaled sawada</h5>
          <span>recoverd</span>
         </div>
      </div>
    </swiper-slide>
    <swiper-slide>
     <div class="stars">
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-regular fa-star"></i>
     </div>
     <h3>best health care</h3>
     <p>Lorem ipsum dolor sit amet 
     consectetur, adipisicing elit.
      Assumenda labore et possimus. 
      Quae nemo, quas assumenda ab 
      voluptas culpa fuga.</p>
      <div class="theimage">
         <img src="../assets/images/reviews/3.jpeg" alt="">
         <div class="text">
          <h5>khaled sawada</h5>
          <span>recoverd</span>
         </div>
      </div>
    </swiper-slide>
   
    <swiper-slide>
     <div class="stars">
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-regular fa-star"></i>
     </div>
     <h3>great services</h3>
     <p>Lorem ipsum dolor sit amet 
     consectetur, adipisicing elit.
      Assumenda labore et possimus. 
      Quae nemo, quas assumenda ab 
      voluptas culpa fuga.</p>
      <div class="theimage">
         <img src="../assets/images/reviews/1.jpeg" alt="">
         <div class="text">
          <h5>khaled sawada</h5>
          <span>recoverd</span>
         </div>
      </div>
    </swiper-slide>
    <swiper-slide>
     <div class="stars">
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-regular fa-star"></i>
     </div>
     <h3>best advices</h3>
     <p>Lorem ipsum dolor sit amet 
     consectetur, adipisicing elit.
      Assumenda labore et possimus. 
      Quae nemo, quas assumenda ab 
      voluptas culpa fuga.</p>
      <div class="theimage">
         <img src="../assets/images/reviews/2.jpeg" alt="">
         <div class="text">
          <h5>khaled sawada</h5>
          <span>recoverd</span>
         </div>
      </div>
    </swiper-slide>
    <swiper-slide>
     <div class="stars">
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-regular fa-star"></i>
     </div>
     <h3>best health care</h3>
     <p>Lorem ipsum dolor sit amet 
     consectetur, adipisicing elit.
      Assumenda labore et possimus. 
      Quae nemo, quas assumenda ab 
      voluptas culpa fuga.</p>
      <div class="theimage">
         <img src="../assets/images/reviews/3.jpeg" alt="">
         <div class="text">
          <h5>khaled sawada</h5>
          <span>recoverd</span>
         </div>
      </div>
    </swiper-slide>
   

  </swiper>
</div>
</div>

<div class="book" id="book">
<h2>Book an appointment</h2>
<div class="theform">
 <div class="inp">
  <input type="text" placeholder="fullname">
  <input type="text" placeholder="email address">
 </div>
 <div class="inp">
  <input type="text" placeholder="phone: 01021189596">
  <input type="date" placeholder="">
 </div>
 <textarea placeholder="additional message" id="" cols="30" rows="10"></textarea>
 <div class="thebtn">
  <button class="btn btn-dark">book now</button>
 </div>
</div>
</div>

<div class="contact" id="contact">
 <div class="mainbox">
  <div class="box">
   <h3>Opening Hours</h3>
   <div class="thetext">
    <p>sunday: closed</p>   
   </div>
   <div class="thetext">
    <p>Monday, Tuesday - Firday</p>  
    <span>8:00 AM - 3:30 PM</span> 
   </div>
   <div class="thetext">
    <p>Saturday</p>  
    <span>10:30 AM - 5:30 PM</span> 
   </div>
  </div>
  <div class="box">
   <h4>Our Clinic</h4>
   <div class="text">
    <p>hello@company.co</p>
    <p>1 ahmed sawada street, giza</p>
    <p>01021189596</p>
   </div>
  </div>
  <div class="box">
   <h3>Socials</h3>
   <div class="iconss">
    <i class="fa-brands fa-facebook"></i>
    <i class="fa-brands fa-instagram"></i>
    <i class="fa-brands fa-twitter"></i>
   </div>
  </div>
 </div>
</div>
  </div>
</template>

<script>



import {ref , onMounted} from 'vue'
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

import 'swiper/css/navigation';
  import 'swiper/css/pagination';
  // import 'swiper/css/scrollbar';

// import required modules
import { Navigation, Pagination, Scrollbar, A11y , Autoplay } from 'swiper';
export default {
  name: 'HomeView',
  components: {
      Swiper,
      SwiperSlide,
    },
  setup(){



   let theimage = ref(1);      
    const randomimages = () =>{
       let counter = setInterval(() => {
         theimage.value = theimage.value + 1
         if(theimage.value == 4){
          theimage.value = 1;
         }
       }, 3000);
      
      
    }
    let years = ref(0);

    const getyears = ()=>{
     let counterr = 0;
     let thecount =  setInterval(() => {
      counterr++;
       years.value = counterr;
      if(counterr >= 12){
        counterr = 0;
      }
    
     }, 500);
    }
    getyears();

    randomimages();
    return{
      theimage,
      years,
      modules: [Navigation, Pagination, Scrollbar, A11y , Autoplay],
    }
  }

}
</script>

<style lang="scss">
@import '../sass/main.scss';
.landing{
  margin-top: 75px;
  margin-bottom: 50px;
  width: 100%;
  display: flex;
  flex-direction: column;
  position: relative;
  .image{
    width: 100%;
    // margin: 0px auto;
    position: relative;
    img{
      width: 100%;
      object-fit: cover;
      display: none;
      &.active{
        display: block;
      }
    }
   
  }
  .boxx{
    padding: 30px;
      position: absolute;
      display: flex;
      // align-items: center;
      flex-direction: column;
      background-color: #fff;
      top: 74.5%;
      right: 0;
      h3{
        font-size: 35px;
        font-weight: bolder;
      }
      p{
        width: 70%;
      }
      .btnss{
        display: flex;
        align-items: center;
        gap: 20px;
        button{
          background-color: $primary;
          color: #fff;
        }
      }
    }
}
.animated {
  position: relative;
}

.animated-info {
  display: inline-block;
  vertical-align: top;
  min-width: 250px;
  position: relative;
}

.animated-item {
  color: $primary;
}

.animated-item {
  display: block;
  opacity: 0;
  overflow: hidden;
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  animation: BottomTotop 6s linear infinite 0s;
}

.animated-item:nth-child(2n+2) {
  animation-delay: 2s;
}

.animated-item:nth-child(3n+3) {
  animation-delay: 4s;
}

@keyframes BottomTotop {
  0% {
    opacity: 0;
  }
  5% {
    opacity: 0;
    transform: translateY(5px);
  }
  10% {
    opacity: 1;
    transform: translateY(0px);
  }
  25% {
    opacity: 1;
    transform: translateY(0px);
  }
  30% {
    opacity: 0;
    transform: translateY(5px);
  }
  80% {
    opacity: 0;
  }
  100% {
    opacity: 0;
  }
}

@media(max-width: 700px){
 .landing{
  .boxx{
    // align-items: center;
    h3{
      font-size: 26px;
    }
  }
 }
}


.aboutt{
  display: flex;
  align-items: center;
  width: 90%;
  margin: 100px auto;
  // margin-top: 150px;
  gap: 20px;
  .text{
   width: 65%;
   display: flex;
   flex-direction: column;
   gap: 10px;
   h4{
    font-weight: bolder;
    font-size: 30px;
    color: black;
   }
   p{
    color: gray;
    font-size: 18px;
    line-height: 40px;
   }
  }
  .years{
    width: 50%;
    height: 450px;
    background-color: #fff;
 display: flex;
 align-items: center;
 justify-content: center;
    // padding: 100px 20px;
    box-shadow: 3px 5px 15px 10px rgba(0, 0, 0, 0.415); 
    border-radius: 50%;
    //       background-color: #fff;
    //           box-shadow: 4px 7px 15px 7px rgba(0, 0, 0, 0.415);  
          // padding: 200px 0px; 
    h2{    
        // border-radius: 50%;
        //   background-color: #fff;
        //       box-shadow: 4px 7px 15px 7px rgba(0, 0, 0, 0.415);  
        //   padding: 200px 0px;
          display: flex;
          align-items: center;
          flex-direction: column;
          font-size: 90px;
          font-weight: bolder;
          color: $primary;
          span{
            font-size: 18px;
            color: gray;
          }
    }
  }
 
}

@media(max-width:975px){
  .aboutt{
    flex-direction: column;
    margin-top: 250px;
    height: 700px;
    .text{
      width: 100%;
      align-items: center;
      text-align: center;
    }
    .years{
      width: 90%;
      height: 100%;
    }
  }
}



.imagess{
  width: 90%;
  margin: 50px auto;
  display: flex;
  align-items: center;
  gap: 20px;
  .image{
    width: 50%;
    position: relative;
    overflow: hidden;
    img{
      width: 100%;
      object-fit: cover;
    }
    span{
      position: absolute;
      width: 100%;
      height: 100%;
      background-color: $primary;
      top: 0;
      right: 0;
      opacity: 0.5;
      transition: 0.5s;
      transform: translateY(-150%);
    }
    &:hover{
      span{
        transform: translateY(0);
      }
    }
  }
}

@media(max-width:620px){
  .imagess{
    flex-direction: column;
    .image{
      width: 100%;
    }
  }
}


.timeline{
  h2{
    color: black;
    font-weight: bolder;
    font-size: 30px;
    text-align: center;
    margin: 50px 0px;
  }
  .maincont{
    width: 80%;
    margin: 30px auto;
    position: relative;
    padding: 20px;
    &::after{
      content: '';
      background-color: #333;
      position: absolute;
      height: 100%;
      width: 3px;
      top: 0;
      right: 49%;
      z-index: -1;
      animation: linee 3s linear forwards;
    }
    .cont{
      position: relative;
      padding: 10px 50px;
      width: 50%;
      // margin: 20px 0px;
      // background-color: red;
      // display: flex;
      // flex-direction: column;
      animation:  movedown 1s linear forwards;
       opacity: 0;
       &:nth-child(1){
        animation-delay: 1s;
       }
       &:nth-child(2){
        animation-delay: 2s;
       }
       &:nth-child(3){
        animation-delay: 3s;
       }
       &:nth-child(4){
        animation-delay: 4s;
       }
      .thetext{
        background-color: #fff;
        
       box-shadow: 5px 5px 15px 10px rgba(0, 0, 0, 0.386);
    

      }
      .tex{
        width: 100%;
        background-color: black;
        padding: 10px;
        color: #fff;
        display: flex;
        font-weight: bolder;
        h3{
          font-size: 29px;
        }
      }
      p{
        padding: 10px;
      }
    
      i{
        position: absolute;
        top: 20px;
        font-size: 27px;
        color: $primary;
        background-color: #fff;
        // box-shadow: 5px 5px 10px 10px rgba(0, 0, 0, 0.422);
        padding: 15px;
        border-radius: 50%;
      }
      span{
          position: absolute;
          border-width: 15px;
          border-style: solid;
          top: 25px;
          display: block;
        }
     
      &.left{
          left: 51.5%;
          i{
            left: -7.5%;
          }
          span{
            left: 5%;
          border-color: transparent black transparent transparent;
          }
          .tex{
            justify-content: flex-start;
          }
      }
      &.right{
        right: 0%;
        i{
          right: -7.5%;
        }
        span{
          right: 5%;
          border-color: transparent transparent transparent black;

        }
      
        .tex{
          justify-content: flex-end;
        }
       
      }
    }
  }
}

@keyframes linee{
  0%{
    height: 0;
  }
  100%{
    height: 100%;
  }
}

@keyframes  movedown{
  0%{
    opacity: 1;
    transform: translateY(-30px);
  }
  100%{
    opacity: 1;
    transform: translateY(0px);
  }
}

@media(max-width:930px){
  .timeline{
    .maincont{
      &::after{
        left: 0%;
      }
      .cont{
        width: 100%;
        &.right,&.left{
          right: 0;
          left: 0;
          .tex{
            justify-content: flex-start;
          }
        
          i{
            // background-color: transparent;
            width: fit-content;
           left: -7%;
           right: 0px; 
          }
        }
        .thetext{
          width: 100%;
          h3{
            font-size: 14px;
          }
          p{
            font-size: 13px;
            font-weight: bold;
          }
          span{
            // position: relative;
            right: 92.4%;
            // top: -80px;
            left: 0%;
            border-color: transparent black transparent transparent;
          }
        }
      }
    }
  }
}

@media(max-width:500px){
  .timeline{
    .maincont{
      .cont{
        &.right,&.left{
          i{
            width: fit-content;
           left: -18%;
           right: 0px; 
          }
        }
        .thetext{
         
          span{
            right: 79%;
            left: 0%;
            // top: 10px;
            // border-width: 21px;
          }
        }
      }
    }
  }
}


.patents{
  h2{
    font-size: 35px;
    text-align: center;
    margin: 50px 0px;
    color: black;
    font-weight: bolder;
  }
  .mainbox{
    width: 90%;
    margin: 30px auto;
    .swiper {
  width: 100%;
  height: 100%;
  
}

.swiper-slide {
  background-color: black;
color: #fff;
  display: flex;
  flex-direction: column;
  padding: 20px;
  gap: 5px;
  
  .stars{
    i{
      margin: 0px 5px;
    }
  }
  p{
    font-size: 13px;
    font-weight: bold;
  }

  h3{
    color: $primary;
    font-weight: bolder;
    font-size: 17px;
  }
  .theimage{
    display: flex;
    align-items: center;
    gap: 20px;
    img{
      width: 70px;
      border-radius: 50%;
    }
    
    
    .text{
      display: flex;
      align-items: center;
      gap: 10px;
      flex-direction: column;
      span{
       color: gray;
      }
      h5{
        font-weight: bolder;
      }
    }
  }
}

.swiper-slide img {
  // display: block;
  // width: 100%;
  // height: 100%;
  // object-fit: cover;
}
  }
}


.book{
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  margin: 50px 0px;
  h2{
    text-align: center;
    margin: 50px 0px;
    font-size: 35px;
    font-weight: bolder;
  }
  .theform{
    width: 60%;
     background-color: #fff;
     box-shadow: 5px 5px 10px 10px rgba(0, 0, 0, 0.41);
     display: flex;
     flex-direction: column;
     padding: 30px;
     gap: 20px;
     input,textarea{
      border: none;
      border-bottom: 2px solid #333;
      padding: 10px;
      background-color: transparent;
      resize: none;
      outline: none;
      // width: 100%;
     }
     .inp{
      width: 100%;
      display: flex;
      align-items: center;
      justify-content:space-between;
      input{
        width: 80%;
        margin: 5px;
      }
     }
     .thebtn{
      display: flex;
      align-items: center;
      justify-content: center;
      button{
      text-align: center;
      font-size: 20px;

      &:hover{
        background-color: $primary;
      }
     }
     }
    
  }
}




.contact{
  background-color: $section;
  padding: 30px;
  .mainbox{
    display: grid;
    grid-template-columns:repeat( 3 , 1fr);
    .box{
      h4{
        font-weight: bolder;
      }
      text-align: center;
      display: flex;
      align-items: center;
      flex-direction: column;
      gap: 20px;
      .thetext{
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        span{
          display: block;
          color: black;
        }
        p{
          display:block;
          color: gray;
          font-weight: bold;
        }
        // flex-direction: column;
      }
    }
    .text{
      display: flex;
      flex-direction: column;
      gap: 10px;
      p{
        color: #333;
        font-size: 18px;
      }
    }
    .iconss{
      display: flex;
      align-items: center;
      gap: 20px;
      i{
        font-size: 30px;
        cursor: pointer;
        transition: 0.4s;
        &:hover{
          color: $primary;
        }
      }
    }
  }
}
@media(max-width:730px){
  .book{
    h2{
      font-size: 30px;
    }
    .theform{
      width: 90%;
      input{
        width: 100%;
      }
      .inp{
        flex-direction: column;
        gap: 10px;
        input{
          width: 100%;
        }
      }
    }
  }
  .contact{
    .mainbox{
      gap: 30px;
      grid-template-columns: repeat(2 , 1fr);
    }
  }
}
@media(max-width:520px){
  .contact{
    .mainbox{
      grid-template-columns: repeat(1 , 1fr);
    }
  }
}
</style>
