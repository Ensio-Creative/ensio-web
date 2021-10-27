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
        <div class="lg:text-5xl text-3xl font-black lg:w-2/5 text-center lg:mx-auto mx-5">
          Let's talk about your project
        </div>
        <div class="lg:w-2/5 mx-auto text-center py-3 text-lg">
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

.contact {
  font-family: "Poppins";
}
.p-8 {
  background: #ffdd14;
  width: 30%;
}
@media (max-width: 600px) {
  .p-8 {
    width: 100%;
    margin-top: 5px;
  }
}
</style>