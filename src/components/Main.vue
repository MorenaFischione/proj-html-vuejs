<template>

    <!-- AREA JAMBOTRON CON AGGIUNTA DELLE CARD IN POSITION ABSOLUTE PER POSIZIONARLE  -->
    <div class="main">
        <section class="jambotron">
            <!-- INSERIMENTO DI IMMAGINE COME BACKGROUND E POSIZIONAMENTO DELLE SCRITTE DI SINISTRA IN ABOSLUTE -->
            <div class="container-fluid my_container position-relative">
                <div class="row align-items-center my_contain-left">
                    <div class="col-10 p-3 ">
                        <h3>Certified fitness professional</h3>
                        <h1>Take control of your health</h1>
                        <div class="my_container-img">
                            <img class="my_img-zig" src="../assets/images/zigzag.png" alt="immagine zig-zag">
                        </div>
                        <p>Curabitur non nulla sit amet nisl tempus convallis quis ac  lectus dolor sit amet.</p>
                        <a href="#"><button type="button" class="btn btn-primary me-4"><i class="fas fa-play"></i>Visit my you tube  channel</button></a>
                        <a href="#"><button type="button" class="btn my_btn">Buy Avada today <i class="fas fa-arrow-right"></i></button></a>
                    </div>
                    <div class="col-2 my_contain-right">
                        <a href="#"> <i class="fas fa-play"></i></a>
                    </div>
                </div>
                <!-- POSIZIONAMENTO DELLE CARD - BOX -->
                <div class="row d-flex ">
                    <!-- CARD 1 -->
                    <div class="col-4">
                        <div class="my_card-1 d-flex">
                            <div class="align-self-end">
                                <div class="pickgradient">
                                    <img src="../assets/images/service6-2x.jpg" alt="ginnasta a riposo">
                                    <div class="my_text-card ">
                                        <div class="my_container-img ps-4">
                                            <img class="my_img-zig" src="../assets/images/zigzag.png" alt="immagine zig-zag">
                                        </div>
                                        <h3 class="ps-4">Crossfit workout</h3>
                                        <h5 class="ps-4 pb-2">Push your limits</h5>
                                    </div>
                                </div>  
                            </div>
                        </div>
                    </div>
                    <!-- CARD 2-->
                    <div class="col-4">
                        <div class="my_card-1 d-flex">
                            <div class="align-self-end">
                                <div class="pickgradient">
                                    <img src="../assets/images/box1-2x.jpg" alt="abbigliamento sportivo">
                                    <div class="my_text-card ">
                                        <div class="my_container-img ps-4">
                                            <img class="my_img-zig" src="../assets/images/zigzag.png" alt="immagine zig-zag">
                                        </div>
                                        <h3 class="ps-4">Crossfit workout</h3>
                                        <h5 class="ps-4 pb-2">Push your limits</h5>
                                    </div>
                                </div>  
                            </div>
                        </div>
                    </div>
                    <!-- CARD 3-->
                    <div class="col-4">
                        <div class="my_card-1 d-flex">
                            <div class="align-self-end">
                                <div class="pickgradient">
                                    <img src="../assets/images/box3-2x.jpg" alt="esercizi con palla pesi">
                                    <div class="my_text-card ">
                                        <div class="my_container-img ps-4">
                                            <img class="my_img-zig" src="../assets/images/zigzag.png" alt="immagine zig-zag">
                                        </div>
                                        <h3 class="ps-4">Crossfit workout</h3>
                                        <h5 class="ps-4 pb-2">Push your limits</h5>
                                    </div>
                                </div>  
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--  / FINE SECTION -->

        <!-- SECTIONT MY BLOG -->
        <section class="my_blog">
            <div class="container-fluid my_container">   
                <div class="row justify-content-center align-items-end my_contain-text">
                    <div class="col-10">
                        <h2>"How you respond ti the challenge in the second half will determine what you  become after the game, whether you  are  a winner or a loser."</h2>
                        <div class="my_container-img text-center">
                            <img class="my_img-zig my_img-zigzag" src="../assets/images/zigzag.png" alt="immagine zig-zag">
                        </div>
                        <div class="my_avatar text-center p-5">
                            <img class="my_img-avatar" src="../assets/images/avatar-1-2x.jpg" alt="immagine avatar blog">
                            <span class="my_name-avatar">Brad Johnson</span>
                            <span class="my_city-avatar" >Las Vegas</span>
                        </div>
                    </div>
                </div>     
            </div>
        </section>
        <!-- SECTION YOUTUBE CON POSIZIONAMENTO IN ABSOLUTE DELL'IMMAGINE DI SINISTRA E AGGIUNTA DI TESTO A DESTRA-->
        <section class="my_youtube">
            <div class="container-fluid">
                <div class="row my_area-right">
                    <div class="col-6 position-relative my_img-addominali">
                        <div class="my_fitness-img text-center">
                            <!-- <img src="../assets/images/service15-2x.jpg" alt=""> -->
                            <div class="col-2 my_contain-right position-absolute">
                                <a href="#"> <i class="fas fa-play"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="col-6 p-5 align-self-center">
                        <h3>Tune up your workouts</h3>
                        <h1>The best health &amp; fitness  advice online</h1>
                        <div class="d-flex">
                            <div>
                                <img src="../assets/images/unnamed.jpg" alt="img unnamed">
                            </div>
                            <div class="my_contain-logo-youtube">
                                <span>Them fusion</span>
                                <div class="my_logo-yt d-flex justify-content-around">
                                    <img class="logo-youtube" src="https://1000marche.net/wp-content/uploads/2020/03/YouTube-logo.png" alt="logo youtube">
                                    <span class="my_visualizzation align-self-center">999+</span>
                                </div>
                            </div>
                        </div>
                        <p>Arcu eu facilisi ut quisque placerat  nunc habitat. Magna semper mauris, venenatis, leo integer sit  pallentsque.</p>
                        <button class="btn btn-danger my_bottone"><i class="fas fa-play"></i>Visit my you tube  channel</button>  
                    </div>
                </div>
            </div>
        </section>
        <!-- SECTION PLAYLIST -->
        <section class="my_playlist">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <h3 class="my_playlist-title">Featured playlist</h3>
                    </div>
                </div>
                <div class="row">
                    <div class="col-4">
                        <div class="my_container-img-card position-relative text-center ">
                            <img class="my_img-card " src="../assets/images/video2-2x.jpg" alt="donna che fa pesi">
                            <div class="col-2 my_contain-play position-absolute">
                                <a href="#"> <i class="fas fa-play"></i></a>
                            </div>
                            <h5 class="pt-5">Thighs &amp; gluse workout</h5>
                            <h6>Increase your  mobility</h6>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="my_container-img-card position-relative text-center">
                            <img class="my_img-card" src="../assets/images/video7-2x.jpg" alt="donna che fa pesi">
                            <div class="col-2 my_contain-play position-absolute">
                                <a href="#"> <i class="fas fa-play"></i></a>
                            </div>
                            <h5 class="pt-5">Lift firm &amp; perk up</h5>
                            <h6>Feel your again</h6>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="my_container-img-card position-relative text-center">
                            <img class="my_img-card" src="../assets/images/video9-2x.jpg" alt="donna che fa pesi">
                            <div class="col-2 my_contain-play position-absolute">
                                <a href="#"> <i class="fas fa-play"></i></a>
                            </div>
                            <h5 class="pt-5">Slim &amp; trim  your waist</h5>
                            <h6>Shed those extra pounds</h6>
                        </div>
                    </div>
                </div>
            </div>
                    
        </section>
    </div>
</template>

<script>
export default {
    name : "Main",

}
</script>

<style lang="scss">
@import "../style/variables.scss";



.my_container-img {
        width: 100px;
        
        .my_img-zig {
        filter: invert(98%) sepia(21%) saturate(4983%) hue-rotate(353deg) brightness(103%) contrast(106%);
        width: 10px;
        height: auto;
        background-position: center;
        }

    }

// SCSS JAMBOTRON

.jambotron {
    width: 100%;
    height: 1000px;
    position: relative;
    background-image: url("../assets/images/slider82x-scaled.jpg");
    z-index: 1;

    .jambotron::after {
        content : "";
        display: block;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: radial-gradient(40% 50%, rgba(0,0,0,0.3), rgba(255,255,255,0.5));
    }
    

    .my_container {
            width: 80%;
            height: 100%;
            bottom: 100px;

            .my_text-card {
                content:'';
                position:absolute;
                left:0; top: 260px;
                width:100%; height:100%;
                display:inline-block;
                }


            .pickgradient{
                position:relative;
                display:inline-block;
                
                }

            .pickgradient:after {
                content:'';
                position:absolute;
                left:0; top:0;
                width:100%; height:100%;
                display:inline-block;
                background: -moz-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,0.65) 100%); /* FF3.6+ */
                background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(0,0,0,0.65)), color-stop(100%,rgba(0,0,0,0))); /* Chrome,Safari4+ */
                background: -webkit-linear-gradient(top, rgba(0,0,0,0) 0%,rgba(0,0,0,0.65) 100%); /* Chrome10+,Safari5.1+ */
                background: -o-linear-gradient(top, rgba(0,0,0,0) 0%,rgba(0,0,0,0.65) 100%); /* Opera 11.10+ */
                background: -ms-linear-gradient(top, rgba(0,0,0,0) 0%,rgba(0,0,0,0.65) 100%); /* IE10+ */
                background: linear-gradient(to bottom, rgba(0,0,0,0) 0%,rgba(0,0,0,0.65) 100%); /* W3C */
                filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#a6000000', endColorstr='#00000000',GradientType=0 ); /* IE6-9 */
                border-radius: 5px 5px 50px 5px;
                }

            img{
                display:block;
                width:100%;
                border-radius: 5px 5px 50px 5px;
                }


            .my_text-card {
                z-index: 1;

                h3 {
                    color: $text-white;
                    font-size: 2.2rem;
                    font-weight: bolder;
                }

                h5 {
                    color: $accent-color;
                    font-size: 1.7rem;
                    font-weight: bolder;
                }
            }

            .my_contain-left {
                height: 100%;
            

                button {
                        padding: 16px;
                        border-radius: 34px;
                        font-size: 1.2rem;
                        font-weight: bolder;
                        font-family: $secondary-font;

                        .fa-play {
                            color: $color-buttom;
                            font-size: .5rem;
                            padding: 5px;
                            margin-right: 10px;
                            background-color: $text-white;
                            border-radius: 5px;
                            width: 25px;
                        }
                    }

                .my_btn {
                    background-color: black;
                    border: 1px solid $paragraph-color;
                    color: $text-white;
                    padding-right: 35px;
                    padding-left: 35px;
                    font-family: $secondary-font;

                }
                
                h3 {
                    color: $color-red;
                    font-size: 1.8rem;
                    font-weight: bold ;
                }

                h1 {
                    color: $text-white;
                    font-size: 5rem;
                    font-weight: bold ;
                }
                
                p {
                    font-size: 1.6rem;
                    color: $text-white;
                }
            }

            .my_contain-right {

                .fa-play {
                        font-size: 1.5rem;
                        background-color: white;
                        padding: 44px;
                        border-radius: 50%;
                    }
                }          
    }      
}     
 
//  SCSS SECTION BLOG
.my_blog {
    width: 100%;
    height: 1200px;
    background-image: linear-gradient(to bottom right, blue 0%, #a03483 50%, rgb(175, 5, 5) 100%);
    padding: 200px;

    .my_container {
        width: 80%;
        height: 100%;

        .my_container-img {
            width: 100%;
        }

        .my_img-zigzag {
            width: 40px;
        }
    
        .my_contain-text {
            height: 100%;
        }

        h2 {
            color: $text-white;
            font-size: 3rem;
            font-weight: bold;
            text-align: center;
        }
        

                
        .my_img-avatar {
            border-radius: 50%;
            object-fit: contain;
            object-position: center;
        }

        .my_name-avatar {
            color: $text-white; 
            font-size: 1.5rem;
            padding:10px;
            font-weight: bolder;
        }

        .my_city-avatar {
            color: $paragraph-color; 
            font-size: 1.5rem;
            padding: 10px;
            font-weight: bolder;    
        }
        
    }
    
}


.my_fitness-img {
    width: 100%;
    padding-left: 0;
    top: -100px;
    
     
    img {
        width: 100%;
        border-radius: 5px 5px 70px 5px;
    }

    .my_contain-right {
        top:50%;
        left:50%;
        transform: translate(-50%,-50%); 
        background-color: white;
        padding: 40px 50px 40px 40px;
        border-radius: 50%;
        width: 20px;
    }
    
}

.my_area-right {
    height: 680px;
}

.my_img-addominali {
    background-image: url(../assets/images/service15-2x.jpg);
    background-position: center;
    background-size: cover;
    top: -120px;
    height: 800px;
}

.my_contain-logo-youtube {
        width: 150px;

        .my_logo-yt {
            border: 1px solid black;
        }

        .logo-youtube {
        width: 50%;
        padding: 0 10px 0;
        border-right: 1px solid black;
        }

        .my_visualizzation {
            font-size: .8rem;
            padding: 5px;
        }
    }

    button {
        padding: 16px;
        border-radius: 34px;
        font-size: 1.2rem;
        font-weight: bolder;
        font-family: $secondary-font;
        

        .fa-play {
            color: $color-buttom;
            font-size: .5rem;
            padding: 5px;
            margin-right: 10px;
            background-color: $text-white;
            border-radius: 5px;
            width: 25px;
        }
    }

.my_playlist-title {
    padding : 150px 30px 30px 30px;
}

.my_container-img-card {
    width: 100%;
    padding:30px;
    border-radius: 35px;



    .my_img-card {
    width: 100%;
    height: 300px;
    border-radius: 5px 5px 50px 5px;
    object-fit: cover;
    object-position: center;
    }

    .my_contain-play {
    top: 50%;
    left: 50%;
    transform: translate(-50%, -95%);
    background-color: white;
    padding: 15px 28px 15px 15px;
    border-radius: 50%;
    width: 20px;
    }

    h6 {
        color: $color-buttom;
    }
}



</style>