<template>
  <section class="my_footer">
      <div class="container my_container-footer">
        <div class="row justify-content-around my_contain-footer" >
          <div class="col-4 my_padding">
            <div>
              <img src="../assets/images/logo-mobile-2x.png" alt="">
            </div>
            <h3 class="text-center my_text-footer pt-5 ">Ac aliquam neque sagittis diam faucibus vitae  purus turpis phasellum. Pelletsque consectetur  amet purus ultices mauris.</h3>
            <div class="text-center p-4">
              <a href="#"><i class="fab fa-facebook-f pe-3"></i></a>
              <a href="#"><i class="fab fa-twitter pe-3"></i></a>
              <a href="#"><i class="fab fa-youtube pe-3"></i></a>
              <a href="#"><i class="fab fa-instagram pe-3"></i></a>
              <a href="#"><i class="fab fa-linkedin-in pe-3"></i></a>
            </div>
          </div>
          <div class="col-4 text-center my_padding">
            <h4>Recent Post</h4>
            <ul>
              <li v-for="(link, index) in links" :key="index">
                <a href="#"> <i class="fas fa-angle-right"></i> {{link.name}} </a>
              </li>
            </ul>
            
          </div>
          <div class="col-4  text-center my_padding">
            <h4>contacts information</h4>
            <h5> {{ adress }} </h5>
            <h5 class="my_color-text"> {{ mobile }} </h5>
            <h5 class="my_color-text"> {{ email }} </h5>
          </div>

           <div class="col-12 text-center border-top">
            <p class="p-5 my_copyright">Copyright 2012 - 2020 | Avada theme the <strong class="my_accent-text">ThemeFusion</strong> all right reserved | Powered by <strong class="my_accent-text">Wordpress</strong></p> 
          </div>
        </div>
       
        
      </div>
  </section>
</template>

<script>
export default {
    name: "Footer",

    data: function(){
      return {
          links: [
            {
              name: "The best protein shake",
              url: "#protein",
            },
            {
              name: "Ultimate cardio workout",
              url: "#cardio",
            },
            {
              name: "New juices available now",
              url: "#juices",
            },
            {
              name: "Tips to find training partners ",
              url: "#partners",
            },
            {
              name: "20 best healthy recipes ",
              url: "#20",
            },
          ],

          adress: "4746 Tipple Road Michigan 48449",
          mobile: "1.8000.000.0000",
          email: "info@your-company.com",
        
      } 
    }


}
</script>

<style lang="scss">
@import "../style/variables.scss";

.my_footer {
  background-color: $background-color-black;
  height: 680px;

  .my_container-footer {
    height: 100%;

    .my_contain-footer {
      height: 100%;
    }
  }

  .my_text-footer {
    color: $text-white;
    font-size: 1.3rem;
  }
  .fab {
    color: $color-red;
    font-size: 1.4rem;
  }

  ul {
        list-style-type: none;
        height: 100%;

        li {
            align-self: center;
            padding: 12px;
        }

        a {
            text-decoration: none;
            color: $text-white;
            font-family: $main-font;
            font-size: 1.4rem;
            font-weight: bolder;
        }
  }

  h4 {
    color: $text-white;
    text-transform: uppercase;
  }

  .my_color-text {
    color: $text-white;
  }

  h5 {
    color: $primary-color;
  }

  .my_padding {
    padding: 100px 0;
  }

  .my_copyright {
    color: $primary-color;
    font-size: 1.1rem;
    font-family: $secondary-font;

    .my_accent-text {
      color: $text-white;
    }
  }

}
</style>