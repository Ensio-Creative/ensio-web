<template>
  <div>
    <HeaderNav />
    <div class="py-10 work">
      <!-- <div
        data-aos="fade-up"
        data-aos-offset="300"
        data-aos-easing="ease-in-out"
        class="
          heading
          lg:w-2/4 lg:text-5xl
          font-black
          text-3xl
          lg:px-20
          px-5
          capitalize
        "
      >
        our projects are great experience
      </div> -->
      <div class="lg:flex lg:px-3">
        <div class="container lg:w-3/6 m-5">
          <img
            src="https://images.unsplash.com/photo-1593642532871-8b12e02d091c?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=812&q=80"
            alt="Avatar"
            class="image"
          />
          <div class="overlay">
            <div class="text">Bluemeen Partners</div>
            <div class="p-10">
              <img class="ml-auto mt-40" src="/arrow.svg" alt="" />
            </div>
          </div>
        </div>
        <div class="container lg:w-3/6 m-5">
          <img
            src="https://images.unsplash.com/photo-1593642532871-8b12e02d091c?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=812&q=80"
            alt="Avatar"
            class="image"
          />
          <div class="overlay">
            <div class="text">Bluemeen Partners</div>
            <div class="p-10">
              <img class="ml-auto mt-40" src="/arrow.svg" alt="" />
            </div>
          </div>
        </div>
        <div class="container lg:w-3/6 m-5">
          <img
            src="https://images.unsplash.com/photo-1593642532871-8b12e02d091c?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=812&q=80"
            alt="Avatar"
            class="image"
          />
          <div class="overlay">
            <div class="text">Bluemeen Partners</div>
            <div class="p-10">
              <img class="ml-auto mt-40" src="/arrow.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="lg:flex lg:px-3 pb-5">
        <div class="container lg:w-3/6 m-5">
          <img
            src="https://images.unsplash.com/photo-1593642532871-8b12e02d091c?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=812&q=80"
            alt="Avatar"
            class="image"
          />
          <div class="overlay">
            <div class="text">Bluemeen Partners</div>
            <div class="p-10">
              <img class="ml-auto mt-40" src="/arrow.svg" alt="" />
            </div>
          </div>
        </div>
        <div class="container lg:w-3/6 m-5">
          <img
            src="https://images.unsplash.com/photo-1593642532871-8b12e02d091c?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=812&q=80"
            alt="Avatar"
            class="image"
          />
          <div class="overlay">
            <div class="text">Bluemeen Partners</div>
            <div class="p-10">
              <img class="ml-auto mt-40" src="/arrow.svg" alt="" />
            </div>
          </div>
        </div>
        <div class="container lg:w-3/6 m-5">
          <img
            src="https://images.unsplash.com/photo-1593642532871-8b12e02d091c?ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=812&q=80"
            alt="Avatar"
            class="image"
          />
          <div class="overlay">
            <div class="text">Bluemeen Partners</div>
            <div class="p-10">
              <img class="ml-auto mt-40" src="/arrow.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Work - Ensio Creative",
    };
  },
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@500;800&display=swap");

.work {
  font-family: "Poppins";
}
/* img {
  height: 40vh;
  width: 100%;
} */

.container {
  position: relative;
  /* width: 50%; */
}

.image {
  display: block;
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: 0.9s ease;
  background-color: #008cba;
}

.container:hover .overlay {
  opacity: 1;
}

.text {
  color: white;
  font-size: 30px;
  font-weight: 700;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}
@media (max-width: 600px) {
  img {
    height: auto;
  }
  .container {
    width: 88%;
  }
}
</style>