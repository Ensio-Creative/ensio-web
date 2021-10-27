<template>
  <div>
    <HeaderNav />
    <div class="hero">
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
          class="lg:w-2/4 w-3/4 text-center mx-auto py-3 lg:text-base text-xs"
        >
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eveniet
          blanditiis magni voluptatem ex laborum explicabo culpa, dolor eligendi
          odio animi. Iusto doloremque delectus ex reiciendis. Nihil alias
          explicabo id, ex laborum voluptas recusandae distinctio rem officiis
          modi, maiores beatae nisi praesentium.
        </div>
      </div>
      <div class="image my-20">
        <img
          src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
          alt=""
        />
      </div>
      <div class="lg:px-20 p-5">
        <div class="text-4xl font-extrabold"><span>What</span> We Do</div>
        <div class="lg:flex justify-between py-5">
          <div class="lg:w-screen w-auto lg:m-5">
            <div>
              <img
                src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
                alt=""
              />
            </div>
            <div class="p-3">
              <div class="font-semibold text-2xl py-5">Branding</div>
              <div class="text-gray-600">
                We bring brands to life through creative solutions that conveys
                the right feeling and creates a positive first impressions that
                are both effective and innovative – setting visual, verbal and
                experiential standards that drive entire experiences.
              </div>
            </div>
          </div>
          <div class="lg:w-screen w-auto lg:m-5">
            <div>
              <img
                src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
                alt=""
              />
            </div>
            <div class="p-3">
              <div class="font-semibold text-2xl py-5">Web/App Design</div>
              <div class="text-gray-600">
                We create simple, thoughtful, intuitive and user-centric
                interfaces that mediates the space between web users and the
                information they need.
              </div>
            </div>
          </div>
          <div class="lg:w-screen w-auto lg:m-5">
            <div>
              <img
                src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
                alt=""
              />
            </div>
            <div class="p-3">
              <div class="font-semibold text-2xl py-5">
                Communications Design
              </div>
              <div class="text-gray-600">
                Through in-depth research and collaborative process, we work
                with businesses and brands to unearth their true purpose, find
                their voice, understand their customers, and define their goals.
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="lg:px-20 py-10">
        <div class="capitalize text-4xl py-3 px:lg-0 px-5">
          <span>our work </span> - featured
        </div>
        <div class="lg:flex justify-between py-5">
          <div class="m-5">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
          <div class="m-5">
            <img
              src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import aosMixin from "~/mixins/aos";
export default {
  name: "PageIndex",
  mixins: [aosMixin],
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");

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