<template>
  <div class="navbar">
    <div class="flex justify-between p-5 lg:px-20">
      <div>
        <img class="logo" src="/ensio-creative-logo.png" alt="" />
      </div>
      <div class="flex nav">
        <nuxt-link to="/" exact-active-class="active">
          <div class="px-5">Home</div>
        </nuxt-link>
        <nuxt-link to="/work" exact-active-class="active">
          <div class="px-5">Work</div>
        </nuxt-link>
        <nuxt-link to="/about" exact-active-class="active">
          <div class="px-5">About Us</div>
        </nuxt-link>
        <nuxt-link to="/contact" exact-active-class="active">
          <div class="px-5">Contact</div>
        </nuxt-link>
      </div>
      <div class="toggler pt-2" @click="openNav">
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
          data-v-28046fd4=""
        >
          <path
            d="M3 4H21V6H3V4ZM3 11H15V13H3V11ZM3 18H21V20H3V18Z"
            fill="black"
            data-v-28046fd4=""
          ></path>
        </svg>
      </div>
    </div>
    <!-- mobile nav start -->
    <div id="myNav" class="overlay">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav"
        >&times;</a
      >
      <!-- Overlay content -->
      <div class="overlay-content">
        <nuxt-link to="/">
          <div class="px-5">Home</div>
        </nuxt-link>
        <nuxt-link to="/work">
          <div class="px-5">Work</div>
        </nuxt-link>
        <nuxt-link to="/about">
          <div class="px-5">About Us</div>
        </nuxt-link>
        <nuxt-link to="/contact">
          <div class="px-5">Contact</div>
        </nuxt-link>
      </div>
    </div>
    <!-- mobile nav end -->
  </div>
</template>
<script>
export default {
  onMounted() {
    document.getElementById("myNav").style.height = "0%";
  },
  methods: {
    openNav() {
      document.getElementById("myNav").style.height = "100%";
    },
    closeNav() {
      document.getElementById("myNav").style.height = "0%";
    },
  },
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
.navbar {
  /* width: 100%;
  position: fixed; */
  font-family: "Poppins";
}
/* The Overlay (background) */
.overlay {
  /* Height & width depends on how you want to reveal the overlay (see JS below) */
  display: none;
  height: 0%;
  width: 100%;
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  left: 0;
  top: 0;
  background-color: #ffdd14; /* Black fallback color */
  background-color: #ffdd14; /* Black w/opacity */
  /* overflow-x: hidden; Disable horizontal scroll */
  overflow-y: hidden;
  transition: 0.5s; /* 0.5 second transition effect to slide in or slide down the overlay (height or width, depending on reveal) */
}

/* Position the content inside the overlay */
.overlay-content {
  font-weight: bolder;
  position: relative;
  top: 25%; /* 25% from the top */
  width: 100%; /* 100% width */
  text-align: center; /* Centered text/links */
  margin-top: 5px; /* 30px top margin to avoid conflict with the close button on smaller screens */
}

/* The navigation links inside the overlay */
.overlay a {
  padding: 8px;
  text-decoration: none;
  font-size: 36px;
  color: #000;
  display: block; /* Display block instead of inline */
  transition: 0.3s; /* Transition effects on hover (color) */
}

/* When you mouse over the navigation links, change their color */
/* .overlay a:hover,
.overlay a:focus {
  color: #f1f1f1;
} */

/* Position the close button (top right corner) */
.overlay .closebtn {
  position: absolute;
  top: -16px;
  right: 10px;
  font-size: 60px;
}

.logo {
  width: 100px;
}
.toggler {
  display: none;
}
.nav {
  display: flex;
  font-weight: 700;
}
.active {
  border-bottom: 2px solid #ffdd14;
}
/* When the height of the screen is less than 450 pixels, change the font-size of the links and position the close button again, so they don't overlap */
@media screen and (max-height: 450px) {
  .overlay a {
    font-size: 20px;
  }
  .overlay .closebtn {
    font-size: 40px;
    top: 15px;
    right: 35px;
  }
}
@media (max-width: 600px) {
  .overlay {
    display: block;
  }
  .toggler {
    display: block;
  }
  .nav {
    display: none;
  }
}
</style>