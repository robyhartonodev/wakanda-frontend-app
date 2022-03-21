<template>
  <div class="w-full h-full bg-gray-800 px-5 md:px-32 p-16 flex flex-col md:flex-row text-gray-100 space-x-0 md:space-x-10 space-y-10">
    <div class="flex flex-col w-full md:w-1/3 space-y-10">
      <div class="text-2xl font-bold flex space-x-2 items-center">
        <img src="~/assets/images/wakanda-logo-white.svg" alt="logo-wakanda-white" class="h-10 w-10">
        <div>Wakanda</div>
      </div>
      <div class="flex space-x-6">
        <div class="h-10 w-10 p-2 rounded-full bg-gray-600 flex justify-center items-center cursor-pointer">
          <img src="~/assets/images/instagram.svg" alt="logo-social-instagram" class="h-full w-full">
        </div>
        <div class="h-10 w-10 p-2 rounded-full bg-gray-600 flex justify-center items-center cursor-pointer">
          <img src="~/assets/images/dribbble.svg" alt="logo-social-dribbble" class="h-full w-full">
        </div>
        <div class="h-10 w-10 p-2 rounded-full bg-gray-600 flex justify-center items-center cursor-pointer">
          <img src="~/assets/images/twitter.svg" alt="logo-social-twitter" class="h-full w-full">
        </div>
        <div class="h-10 w-10 p-2 rounded-full bg-gray-600 flex justify-center items-center cursor-pointer">
          <img src="~/assets/images/youtube.svg" alt="logo-social-youtube" class="h-full w-full">
        </div>
      </div>
      <div>
        Copyright &#169; 2022 Wakanda. All rights reserved
      </div>
    </div>

    <div class="flex flex-col md:flex-row w-full md:w-2/3 space-x-0 space-y-5 md:space-x-16">
      <div class="flex flex-col space-y-5">
        <div class="text-xl font-semibold">
          Company
        </div>
        <a href="#">About us</a>
        <a href="#">Blog</a>
        <a href="#">Contact us</a>
        <a href="#">How it works</a>
        <a href="#">For freelancer</a>
      </div>
      <div class="flex flex-col space-y-5">
        <div class="text-xl font-semibold">
          Support
        </div>
        <a href="#">Help center</a>
        <a href="#">Terms of service</a>
        <a href="#">Legal</a>
        <a href="#">Privacy policy</a>
        <a href="#">Status</a>
      </div>
      <div class="flex flex-col space-y-5">
        <div class="text-xl font-semibold">
          Subscribe to our newsletter
        </div>
        <div>
          <input class="rounded-md bg-gray-500 text-gray-100 p-2 w-full" type="text" placeholder="Your email address">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterComponent'
}
</script>
