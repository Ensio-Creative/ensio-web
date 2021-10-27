<template>
  <div>
    <HeaderNav />
    <div class="about">
      <div
        data-aos="fade-up"
        data-aos-offset="300"
        data-aos-easing="ease-in-out"
        class="
          heading
          lg:px-20
          mx-auto
          capitalize
          lg:text-5xl
          text-3xl
          lg:w-2/4
          text-center
          py-32
          font-black
        "
      >
        we create unique experiences for lasting impressions
      </div>
      <div class="image1 my-20">
        <img
          src="https://images.unsplash.com/photo-1457131760772-7017c6180f05?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=853&q=80"
          alt=""
        />
      </div>
      <div class="lg:px-20 p-5">
        <div class="capitalize text-3xl">We are ensio creative</div>
        <div class="lg:text-xl text-sm lg:w-2/4">
          A Team of designers, developers, strategists and creators dedicated to
          building wonderful things
        </div>
      </div>
      <div class="lg:flex justify-between lg:p-10 py-5">
        <div class="container m-5">
          <img src="/alabo.jpg" alt="Avatar" class="image" />
          <div class="overlay">
            <div>Gabirel Ugochukwu</div>
            <div class="text-xs">Team Lead</div>
          </div>
        </div>
        <div class="container m-5">
          <img src="/alabo.jpg" alt="Avatar" class="image" />
          <div class="overlay">
            <div>Ifeanyichukwu Adams</div>
            <div class="text-xs">
              Fullstack, Blockchain and Senior Developer
            </div>
          </div>
        </div>
        <div class="container m-5">
          <img src="/alabo.jpg" alt="Avatar" class="image" />
          <div class="overlay">
            <div>Alabo Excel</div>
            <div class="text-xs">Front-end Developer</div>
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
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@500;800&display=swap");

.about {
  font-family: "Poppins";
}
.image1 img {
  width: 100%;
  height: 80vh;
}
* {
  box-sizing: border-box;
}

/* Container needed to position the overlay. Adjust the width as needed */
.container {
  position: relative;
  width: 100%;
  /* max-width: 300px; */
}

/* Make the image to responsive */
.image {
  display: block;
  width: 100%;
  height: auto;
}

/* The overlay effect - lays on top of the container and over the image */
.overlay {
  position: absolute;
  bottom: 0;
  background: #ffdd14;
  background: #ffdd14; /* Black see-through */
  color: #f1f1f1;
  width: 100%;
  transition: 0.5s ease;
  opacity: 0;
  color: white;
  font-size: 20px;
  padding: 20px;
  text-align: center;
}

/* When you mouse over the container, fade in the overlay title */
.container:hover .overlay {
  opacity: 1;
}
@media (max-width: 600px) {
  .image1 img {
    height: auto;
  }
  .container img {
    width: 90%;
  }
  .overlay {
    width: 90%;
  }
}
</style>