<template>
    <section class="jambotron">
        <div class="container-fluid my_container">
            <div class="row align-items-center my_contain-left">
                <div class="col-10 p-3 ">
                    <h3>Certified fitness professional</h3>
                    <h1>Take control of your health</h1>
                    <div class="my_container-img">
                        <img src="../assets/images/zigzag.png" alt="immagine zig-zag">
                    </div>
                    <p>Curabitur non nulla sit amet nisl tempus convallis quis ac  lectus dolor sit amet.</p>
                    <a href="#"><button type="button" class="btn btn-primary"><i class="fas fa-play"></i>Visit my you tube  channel</button></a>
                </div>
                <div class="col-2 my_contain-right">
                    <a href="#"> <i class="fas fa-play"></i></a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name : "Main",

}
</script>

<style lang="scss">
@import "../style/variables.scss";

.jambotron {
    
    height: 900px;
    background-image: url("../assets/images/slider82x-scaled.jpg");

    .my_container {
            width: 80%;
            height: 100%;

            .my_contain-left {
                height: 100%;
            
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

                button {
                        padding: 16px;
                        border-radius: 34px;
                        font-size: 1.2rem;
                        font-weight: bolder;

                        .fa-play {
                            color: $color-buttom;
                            font-size: .5rem;
                            padding: 5px;
                            margin-right: 10px;
                            background-color: white;
                            border-radius: 5px;
                            width: 25px;
                        }
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


</style>