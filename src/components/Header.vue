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
                        <li v-for="(link, index) in links" :key="index">
                            <a :class="{ active : link.current}" href="">{{link.text}} <span >{{link.new}}</span></a>         
                        </li>
                        <li>
                            <a href="#">
                                <button type="button" class="my_button-menu">Schedule a Workout</button>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <i class="fas fa-shopping-cart"></i>
                            </a>
                        </li>
                         <li>
                            <a href="#">
                                <i class="fas fa-search"></i>
                            </a>
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

    data: function () {
        return {
            links: [
                {
                    text: "Home",
                    new: "",
                    url: "#home",
                    current: true,
                },
                {
                    text: "Services",
                    new: "",
                    url: "#services",
                    current: false,
                },
                {
                    text: "About",
                    new: "",
                    url: "#about",
                    current: false,
                },
                {
                    text: "Videos",
                    new: "",
                    url: "#videos",
                    current: false,
                },
                {
                    text: "Blog",
                    new: "",
                    url: "#blog",
                    current: false,
                },
                {
                    text: "Store",
                    new: "new",
                    url: "#store",
                    current: false,
                },
            ],
        }   
    }
}
</script>

<style lang="scss">
@import "../style/variables.scss";


.my_navbar {
    background-color: $background-color-black;

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

            button {
                padding: 16px;
                border-radius: 34px;
                font-size: 1.2rem;
                font-weight: bolder;
               
            }

            .my_button-menu {
                background-color: $color-buttom;
                color: $text-white;
                border: 1px solid $color-buttom;

                &:hover {
                    background-color: $color-red-sienna;
                    border: 1px solid $color-red-sienna;
                }
            }

            span {
                background-color: $accent-color;
                font-size: 1.4rem;
                border-radius: 2px;
            }
        }

        .active {
            color: $text-white;
        }

    
    }
}




</style>