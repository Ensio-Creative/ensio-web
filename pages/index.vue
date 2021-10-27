<template>
  <div>
    <div class="hero">
      <HeaderNav />
      <div
        class="lg:py-32 py-24"
        data-aos="fade-up"
        data-aos-offset="300"
        data-aos-easing="ease-in-out"
      >
        <div
          class="
            heading
            lg:w-2/4
            w-3/4
            text-center
            mx-auto
            font-black
            capitalize
          "
        >
          We're <span>passionate</span> about solving problems
        </div>
        <div
          class="
            lg:w-2/4
            text-gray-600 text-center
            mx-auto
            p-5
            lg:text-base
            text-sm
            font-thin
          "
        >
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eveniet
          blanditiis magni voluptatem ex laborum explicabo culpa, dolor eligendi
          odio animi. Iusto doloremque delectus ex reiciendis. Nihil alias
          explicabo id, ex laborum voluptas recusandae distinctio rem officiis
          modi, maiores beatae nisi praesentium.
        </div>
      </div>
      <div class="">
        <!-- <div class="capitalize font-semibold lg:text-4xl text-2xl px:lg-0 px-5">
          <span>our work </span> - featured
        </div> -->
        <div class="lg:flex justify-between">
          <div class="">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
          <div class="">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
          <div class="">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
        </div>
        <div class="lg:flex justify-between">
          <div class="">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
          <div class="">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
          <div class="">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
        </div>
        <!-- <div class="text-center py-5 capitalize text-xl">
          <nuxt-link to="/work">&#8594; view all works</nuxt-link>
        </div> -->
      </div>
      <div class="lg:px-20 p-5 py-16">
        <div class="lg:text-4xl text-2xl font-extrabold lg:px-5">
          Our Expertise
        </div>
        <div class="lg:flex justify-between py-5">
          <div class="lg:w-screen w-auto lg:m-5">
            <div class="p-3">
              <div class="font-extrabold lg:text-2xl text-xl py-8">
                Branding
              </div>
              <div class="text-gray-600 lg:text-base text-sm font-thin">
                We bring brands to life through creative solutions that conveys
                the right feeling and creates a positive first impressions that
                are both effective and innovative – setting visual, verbal and
                experiential standards that drive entire experiences.
              </div>
            </div>
          </div>
          <div class="lg:w-screen w-auto lg:m-5">
            <div class="p-3">
              <div class="font-extrabold lg:text-2xl text-xl py-8">
                Web/App Design
              </div>
              <div class="text-gray-600 lg:text-base text-sm font-thin">
                We create simple, thoughtful, intuitive and user-centric
                interfaces that mediates the space between web users and the
                information they need.
              </div>
            </div>
          </div>
          <div class="lg:w-screen w-auto lg:m-5">
            <div class="p-3">
              <div class="font-extrabold lg:text-2xl text-xl py-8">
                Communications Design
              </div>
              <div class="text-gray-600 lg:text-base text-sm font-thin">
                Through in-depth research and collaborative process, we work
                with businesses and brands to unearth their true purpose, find
                their voice, understand their customers, and define their goals.
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="lg:flex">
        <div
          class="
            text-5xl
            more
            text-white
            w-screen
            font-medium
            text-xl
            lg:p-20
            p-14
            lg:py-32
          "
        >
          <div class="text-2xl">Want to see more?</div>
          <nuxt-link to="/work"
            ><div class="yellow font-extrabold py-3 leading-normal">
              View all works
            </div></nuxt-link
          >
        </div>
        <div
          class="text-5xl w-screen bg-yellow text-xl lg:p-20 p-14 lg:py-32"
        >
          <div class="text-2xl">Have a Project?</div>
          <nuxt-link to="/contact"
            ><div class="font-extrabold py-3 leading-normal">Get in touch</div></nuxt-link
          >
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import aosMixin from "~/mixins/aos";
export default {
  head() {
    return {
      title: "Ensio Creative - Brand Identity | Web Development | Communications Design",
    };
  },
  name: "PageIndex",
  mixins: [aosMixin],
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;800&display=swap");
.yellow {
  color: #ffdd14;
}
.more {
  background-color: #252529;
}
.bg-yellow {
  background-color: #ffdd14;
}
.hero {
  font-family: "Poppins";
}
.heading {
  font-size: 50px;
}
div span {
  border-bottom: 3px solid #ffdd14;
}
.image img {
  width: 100%;
  height: 80vh;
}
@media (max-width: 600px) {
  .heading {
    font-size: 30px;
  }
  .image img {
    height: auto;
  }
}
</style>