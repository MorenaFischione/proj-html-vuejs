<template>
  <section class="my_footer">
      <div class="container my_container-footer">
        <div class="row justify-content-around my_contain-footer" >
          <div class="col-4 align-self-center ">
            <div class="p-5">
              <img src="../assets/images/logo-mobile-2x.png" alt="">
            </div>
            <h3 class="text-center my_text-footer">Ac aliquam neque sagittis diam faucibus vitae  purus turpis phasellum. Pelletsque consectetur  amet purus ultices mauris.</h3>
            <div class="text-center p-5">
              <a href="#"><i class="fab fa-facebook-f pe-3"></i></a>
              <a href="#"><i class="fab fa-twitter pe-3"></i></a>
              <a href="#"><i class="fab fa-youtube pe-3"></i></a>
              <a href="#"><i class="fab fa-instagram pe-3"></i></a>
              <a href="#"><i class="fab fa-linkedin-in pe-3"></i></a>
            </div>
          </div>
          <div class="col-4 align-self-center text-center">
            <h4>Recent Post</h4>
            <ul>
              <li v-for="(link, index) in links" :key="index">
                <a href="#"> <i class="fas fa-angle-right"></i> {{link.name}} </a>
              </li>
            </ul>
            
          </div>
          <div class="col-4 align-self-center text-center">
            <h4>contacts information</h4>
            <h5> {{ adress }} </h5>
            <h5 class="my_color-text"> {{ mobile }} </h5>
            <h5 class="my_color-text"> {{ email }} </h5>
          </div>
        </div>
        <div class="row">
          <div class="col-12">

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
  height: 800px;

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
            padding: 15px;
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

}
</style>