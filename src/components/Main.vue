<template>
    <div class="main">
        <section class="jambotron">
            <div class="container-fluid my_container position-relative">
                <div class="row align-items-center my_contain-left">
                    <div class="col-10 p-3 ">
                        <h3>Certified fitness professional</h3>
                        <h1>Take control of your health</h1>
                        <div class="my_container-img">
                            <img src="../assets/images/zigzag.png" alt="immagine zig-zag">
                        </div>
                        <p>Curabitur non nulla sit amet nisl tempus convallis quis ac  lectus dolor sit amet.</p>
                        <a href="#"><button type="button" class="btn btn-primary me-4"><i class="fas fa-play"></i>Visit my you tube  channel</button></a>
                        <a href="#"><button type="button" class="btn my_btn">Buy Avada today <i class="fas fa-arrow-right"></i></button></a>
                    </div>
                    <div class="col-2 my_contain-right">
                        <a href="#"> <i class="fas fa-play"></i></a>
                    </div>
                </div>
                <div class="row d-flex ">
                    <div class="col-4">
                        <div class="my_card-1 d-flex">
                            <div class="my_text-card align-self-end">
                                <div class="my_container-img text-center ">
                                    <img     src="../assets/images/zigzag.png" alt="immagine zig-zag">
                                </div>
                                <h3 class="ps-4">Crossfit workout</h3>
                                <h5 class="ps-4 pb-2">Push your limits</h5>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="my_card-2 d-flex">
                            <div class="my_text-card align-self-end">
                                <div class="my_container-img text-center ">
                                    <img src="../assets/images/zigzag.png" alt="immagine zig-zag">
                                </div>
                                <h3 class="ps-4">New gym apparel</h3>
                                <h5 class="ps-4 pb-2">Look good, feel good</h5>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="my_card-3 d-flex">
                            <div class="my_text-card align-self-end">
                                <div class="my_container-img text-center ">
                                    <img src="../assets/images/zigzag.png" alt="immagine zig-zag">
                                </div>
                                <h3 class="ps-4">Team traning</h3>
                                <h5 class="ps-4 pb-2">Find a partner</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="my_blog">
            <div class="container-fluid my_container">   
                <div class="row justify-content-center align-items-end my_contain-text">
                    <div class="col-10">
                        <h2>"How you respond ti the challenge in the second half will determine what you  become after the game, whether you  are  a winner or a loser."</h2>
                        <div class="my_container-img text-center">
                            <img src="../assets/images/zigzag.png" alt="immagine zig-zag">
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
        height: 50px;

        img {
        filter: invert(98%) sepia(21%) saturate(4983%) hue-rotate(353deg) brightness(103%) contrast(106%);
        width: 50%;
        height: auto;
        background-position: center;
        }

    }

.jambotron {
    width: 100%;
    height: 1000px;
    background-image: url("../assets/images/slider82x-scaled.jpg");
    

    .my_container {
            width: 80%;
            height: 100%;
            bottom: 100px;

            .my_card-1 {
                background-image: url("../assets/images/box1-2x.jpg");
                background-position: center;
                background-size: cover; 
                border-radius: 5px 5px 50px 5px;
                filter: brightness(60%);
                height: 500px;
            }

            .my_card-2 {
                background-image: url("../assets/images/service6-2x.jpg");
                background-position: center;
                background-size: cover; 
                border-radius: 5px 5px 50px 5px;
                filter: brightness(50%);
                height: 500px;

            }

            .my_card-3 {
                background-image: url("../assets/images/box3-2x.jpg");
                background-position: center;
                background-size: cover; 
                border-radius: 5px 5px 50px 5px;
                filter: brightness(50%);
                height: 500px;

            }

            .my_text-card {
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

.my_blog {
    width: 100%;
    height: 1200px;
    background-image: linear-gradient(to bottom right, blue 0%, #a03483 50%, rgb(175, 5, 5) 100%);
    padding: 200px;

    .my_container {
        width: 80%;
        height: 100%;

    
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


</style>