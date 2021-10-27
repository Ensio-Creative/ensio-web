<template>
  <div>
    <HeaderNav />
    <div class="contact">
      <div
        class="py-20"
        data-aos="fade-up"
        data-aos-offset="300"
        data-aos-easing="ease-in-out"
      >
        <div
          class="
            lg:text-5xl
            text-3xl
            font-black
            lg:w-2/5
            text-center
            lg:mx-auto
            mx-5  
          "
        >
          Let's talk about your project
        </div>
        <div class="lg:w-2/5 mx-auto text-center font-thin py-3 text-lg">
          we are currently working remotely
        </div>
      </div>
      <div class="lg:flex justify-between lg:px-40 p-10">
        <div class="p-8">
          <div class="text-2xl font-medium">Call Us</div>
          <div class="py-3">+2347 03964 4259</div>
        </div>
        <div class="p-8">
          <div class="text-2xl font-medium">Get in Touch</div>
          <div class="py-3">hello@ensiocreative.com</div>
        </div>
        <div class="p-8">
          <div class="text-2xl font-medium">Work with us</div>
          <div class="py-3">talents@ensiocreative.com</div>
        </div>
      </div>
      <div class="text-center lg:text-4xl font-semibold py-8">Our Work</div>
      <div class="lg:flex">
        <div class="container lg:w-3/6">
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
        <div class="container lg:w-3/6">
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
        <div class="container lg:w-3/6">
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
      <div class="lg:flex">
        <div class="container lg:w-3/6">
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
        <div class="container lg:w-3/6">
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
        <div class="container lg:w-3/6">
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
import aosMixin from "~/mixins/aos";
export default {
  head() {
    return {
      title: "Contact - Ensio Creative",
    };
  },
  name: "PageIndex",
  mixins: [aosMixin],
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;800&display=swap");

.contact {
  font-family: "Poppins";
}
.p-8 {
  background: #ffdd14;
  width: 30%;
}

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
  .p-8 {
    width: 100%;
    margin-top: 5px;
  }
}
</style>