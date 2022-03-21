<template>
  <div class="flex flex-col md:flex-row justify-between p-5 items-center px-5 md:px-32 space-y-2 md:space-y-0">
    <div class="text-2xl font-bold flex space-x-2 items-center">
      <img src="~/assets/images/wakanda-logo.svg" alt="logo-wakanda" class="h-10 w-10">
      <div>Wakanda</div>
    </div>
    <div class="flex flex-col md:flex-row justify-center items-center space-x-0 md:space-x-6 space-y-3 md:space-y-0 font-semibold">
      <a href="#">Home</a>
      <a href="#">About us</a>
      <a href="#">How it works</a>
      <a href="#">For Freelancer</a>
      <button class="p-3 bg-blue-700 text-white px-6 rounded-lg font-bold">
        Get started
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderComponent'
}
</script>
