<script>
import 'vue3-carousel/dist/carousel.css';
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel';
export default {
  components: {
    Carousel,
    Slide,
    Pagination,
    Navigation,
  },
  data() {
    return {
      testimonials: [
        {
          content: 'I will never stop visiting this place. It is just a hideaway for me. It is located in a quiet district and I like to come here after work. I enjoy my meals and think of my global plans. Everything is perfect here.',
          author: 'John Doe'
        },
        {
          content: 'I had my birthday party here this weekend. I have heard so many good reviews of this restaurant. It did not disappoint. The food was spectacular. Fresh and delicious. Everyone was very pleased.',
          author: 'Julia Smith'
        },
        {
          content: 'This place was fun and the food was good. The diversity of your menu impressed so much. All the dishes tasted great. Thank you! Would definitely recommend to all my friends.',
          author: 'Alex Ross'
        }
      ]
    }
  },
}
/*
install vue-owl-carousel
buat owl carousel untuk testimony
*/
</script>
<template>
    <main class="page-content">
        <!-- Section Intro-->
        <section class="context-dark">
          <div class="parallax-container">
            <div class="parallax-content">
              <div class="container">
                <div class="section-110 row justify-content-sm-center align-items-sm-center">
                  <div class="col-lg-8"><img src="@/assets/images/logo/logo-front.png" alt="" width="175" height="173">
                    <h1 class="font-accent"><span class="big">About Us</span></h1>
                    <ul class="list-inline list-inline-dashed p">
                      <li class="list-inline-item"><a href="/">Home</a></li>
                      <li class="list-inline-item">About Us
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- Section About us-->
        <section class="section-98 section-md-110">
          <div class="container">
            <div class="row justify-content-xl-center">
              <div class="col-xl-10">
                <h1><span class="d-block font-accent big">Who We Are</span></h1>
                <hr class="divider bg-mantis offset-top-30"><img class="img-fluid mx-auto d-block shadow-drop-xl offset-top-66" src="@/assets/images/packs-microgreens-min.jpg" alt="" width="570" height="321">
                <p class="offset-top-50">At Veggies & Co, we are passionate about providing our customers with the freshest and most nutritious microgreens and vegetables available. We believe that everyone should have access to healthy and delicious produce, which is why we work passionately to produce the best products for our store.</p>
              </div>
            </div>
          </div>
        </section>
        <!-- Section Our Awards-->
        <section class="context-dark">
          <div class="parallax-container">
            <div class="parallax-content">
              <div class="container section-98 section-md-110">
                <div class="row">
                  <div class="col-lg-4 text-lg-left">
                    <h1><span class="d-block font-accent big">The Achievement</span><span class="d-block offset-top-4 h3 text-light text-uppercase">We are Proud of</span></h1>
                    <hr class="divider hr-lg-left-0 bg-mantis offset-top-30">
                    <p>Homegrown in our own founder residence, we started this journey with a humble beggining. We started from nothing and will keep getting better from then, now and future.</p>
                    <p>Such a prestigious achievement makes us very proud. And to keep us going from our humble beggining we look forward for a brighter future.</p>
                  </div>
                  <div class="col-lg-8 offset-top-66 offset-lg-top-0">
                    <div class="row">
                      <!-- Ilustrasi Achievement ??? -->
                      <!-- <div class="col-4"><img class="img-fluid mx-auto d-block" src="../assets/images/Clean.png" alt="" width="170" height="326"></div>
                      <div class="col-4"><img class="img-fluid mx-auto d-block" src="images/image-07-170x326.png" alt="" width="170" height="326"></div>
                      <div class="col-4"><img class="img-fluid mx-auto d-block" src="images/image-08-170x326.png" alt="" width="170" height="326"></div> -->
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- Section Best Goods-->
        <section class="margin-bottom">
          <div class="container section-66 section-md-bottom-0">
            <div class="row flex-lg-row-reverse">
              <div class="col-lg-5 text-lg-left section-lg-50">
                <h1><span class="d-block font-accent big">Best Food</span><span class="d-block offset-top-4 h3 text-light text-uppercase">From our Head Chef</span></h1>
                <hr class="divider hr-lg-left-0 bg-mantis offset-top-30">
                <p>The work is always in a full swing in our kitchen! Everyone here is on fire when it comes to cooking. The best cooks all over the world are gathered here together to create something really special to impress you deeply.</p>
                <p>The latest in cooking fashion, best recipes and fresh goods, this is the formula of our success.</p>
              </div>
              <div class="col-lg-7 align-self-lg-end d-none d-md-block"><img class="img-food" src="@/assets/images/microgreen-product1-min.jpg" alt="" width="669" height="610"></div>
            </div>
          </div>
        </section>

        <!-- Testimonials-->
        <section class="bg-gray-darkest section-98 section-110 context-dark">
          <div class="container">
            <h1><span class="d-block font-accent big">Testimonials</span><span class="d-block offset-top-4 h3 text-light text-uppercase">What people say</span></h1>
            <hr class="divider bg-mantis offset-top-30">
            <carousel :items-to-show="1" :wrapAround="true" :autoplay="2500" :transition="500">
              <slide v-for="slide in testimonials" :key="slide">
                <div>
                  <blockquote class="quote inset-left-7p inset-right-7p">
                    <div class="icon mdi mdi-comment-text-outline"></div>
                    <p class="offset-top-30">
                      <q>{{ slide.content }}</q>
                    </p>
                    <h6 class="text-uppercase">
                      <cite class="text-normal text-light">- {{ slide.author }}, Visitor</cite>
                    </h6>
                  </blockquote>
                </div>
              </slide>

              <template #addons>
                <navigation />
                <pagination />
              </template>
            </carousel>
          </div>
        </section>
    </main>
</template>