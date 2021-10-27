<template>
  <div class="footer">
    <div class="lg:px-20 p-8 lg:flex justify-between">
      <div class="py-4">
        <img src="/footer-logo.png" alt="" />
        <div class="pt-6">T: +2347 03964 4259</div>
        <div class="py-1">E: hello@ensiocreative.com</div>
      </div>
      <div class="lg:px-20 py-4">
        <nuxt-link to="/about">
          <div class="py-1">About</div>
        </nuxt-link>
        <nuxt-link to="/work">
          <div class="py-1">Work</div>
        </nuxt-link>
        <nuxt-link to="/contact">
          <div class="py-1">Contact</div>
        </nuxt-link>
      </div>
      <div class="lg:px-20 py-4">
        <div class="py-1">Web Development</div>
        <div class="py-1">Branding</div>
        <div class="py-1">UI/UX Design</div>
        <div class="py-1">App Development</div>
        <div class="py-1">Communications Design</div>
      </div>
      <div class="lg:px-20 py-4">
        <div class="py-1">Facebook</div>
        <div class="py-1">Twitter</div>
        <div class="py-1">Instagram</div>
        <div class="py-1">Linkedin</div>
      </div>
    </div>
    <hr>
    <div class="lg:px-20 p-6">
      © 2021 Ensio Creative
    </div>
  </div>
</template>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@500;800&display=swap");


.footer {
  background: #000;
  color: white;
  font-family: "Poppins";
}
img {
  width: 150px;
}
@media (max-width: 600px) {
  .footer{
    font-size: 14px;
  }
}
</style>