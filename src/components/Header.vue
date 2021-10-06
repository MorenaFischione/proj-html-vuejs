<template>
    <section class="my_navbar">
        <nav class="container-fluid my_container"> 
            <div class="row">
                <div class="col-3 p-3">
                    <a class="navbar-brand" href="#">
                        <img src="../assets/images/logo-2x.png" alt="logo palestra" >
                    </a>
                </div>
                <div class="col-9">
                    <ul class="d-flex justify-content-end">
                        <li>
                            <a class="active" href="#">Home</a>
                        </li>
                        <li>
                            <a href="#">Services</a>
                        </li>
                        <li>
                            <a href="#">About</a>
                        </li>
                        <li>
                            <a href="#">Videos</a>
                        </li>
                        <li>
                            <a href="#">Blog</a>
                        </li>
                        <li>
                            <a href="#">Store New</a>
                        </li>
                        <li>
                            <a href="">
                                <button type="button" class="btn btn-primary">Schedule a Workout</button>
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <i class="fas fa-shopping-cart"></i>
                            </a>
                        </li>
                         <li>
                            <i class="fas fa-search"></i>
                        </li>
                    </ul>

                </div>
            </div>
            
        </nav>
    </section>
</template>

<script>
export default {
    name: "Header",

}
</script>

<style lang="scss">
@import "../style/variables.scss";


.my_navbar {
    background-color: $background-color;

    .my_container {
        width: 80%;
    }

    img {
        padding: 20px;
        width: 100%;
    }

    ul {
        list-style-type: none;
        height: 100%;

        li {
            align-self: center;
            padding: 20px;
        }

        a {
            text-decoration: none;
            color: $primary-color;
            font-family: $main-font;
            font-size: 1.5rem;

            
          
            .fas{
                color: grey;
            }

            button {
                padding: 16px;
                border-radius: 34px;
                font-size: 1.2rem;
                font-weight: bolder;
            }
        
        }
    }
}




</style>