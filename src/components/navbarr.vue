<template>
    <div>
        <!-- <div class="thenav">
        <div class="list">
         <ul class="firstlist">
           <li>
            <a href="">home</a>
           </li>
           <li>
            <a href="">about</a>
           </li>
           <li>
            <a href="">timeline</a>
           </li>
         </ul>
         <div class="logo">
          <h2>Medic Care</h2>
          <span>Health Specialist</span>
         </div>
         <ul class="secondlist">
           <li>
            <a href="">testimonials</a>
           </li>
           <li>
            <a href="">booking</a>
           </li>
           <li>
            <a href="">contact</a>
           </li>
         </ul>
         <i class="fa-solid fa-bars"></i>
        </div>
    </div>   -->






   <nav class="navbar navbar-expand-lg bg-light fixed-top shadow-lg">
                <div class="container">
                    <!-- <a class="navbar-brand mx-auto d-lg-none" href="index.html">
                        Medic Care
                        <strong class="d-block">Health Specialist</strong>
                        
                    </a> -->
                    <div class="logoo navbar-brand mx-auto d-flex d-lg-none">
                        <h2>Medic Care</h2>
                     <span>Health Specialist</span>
                    </div>

                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>

                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav mx-auto">
                            <li class="nav-item active">
                                <a class="nav-link" href="#hero">Home</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#about">About</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#time">Timeline</a>
                            </li>

                            <!-- <a class="navbar-brand d-none d-lg-block" href="index.html">
                                Medic Care
                                <strong class="d-block">Health Specialist</strong>
                            </a> -->
                            <div class="logoo navbar-brand d-none d-lg-flex">
                        <h2>Medic Care</h2>
                     <span>Health Specialist</span>
                    </div>

                            <li class="nav-item">
                                <a class="nav-link" href="#patents">Testimonials</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#book">Booking</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#contact">Contact</a>
                            </li>
                        </ul>
                    </div>

                </div>
            </nav>


    </div>
</template>

<script>
import {ref} from 'vue'
export default {
    setup(){


        return{}
    }
}

</script>

<style lang="scss">

@import '../sass/main.scss';


.navbar{
    .container{
    
        .logoo{
          
                align-items: center;
                flex-direction: column;
                text-align: center;
                h2{
                    color: $primary;
                    font-weight: bolder;
                    font-size: 19px;
                }
                span{
                    // text-align: center;
                    font-size: 13px;
                    font-weight: bold;
                }
            }

        .navbar-collapse{
          
            .navbar-nav{
            align-items: center;
            gap: 40px;
          
            a{
                font-size: 18px;
          
            }
          
            }
        }
    }
}

@media(max-width: 991.82px){
   .navbar{
    .container{
    
        .navbar-collapse{
            .navbar-nav{
                align-items: flex-start;
            
            gap: 20px;
            }
          
        }
    }
   }
}

</style>