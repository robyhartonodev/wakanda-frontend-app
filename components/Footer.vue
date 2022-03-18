<template>
  <div class="w-full h-72 bg-gray-800 px-32 p-16 flex text-white">
    <div class="flex flex-col w-1/3 space-y-10">
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
    <!-- <div class="flex w-2/3">
      <div class="flex flex-col">
        <div>cokc yep</div>
      </div>
      <div class="flex flex-col">
        <div>cokc yep</div>
      </div>
      <div class="flex flex-col">
        <div>cokc yep</div>
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: 'FooterComponent'
}
</script>
