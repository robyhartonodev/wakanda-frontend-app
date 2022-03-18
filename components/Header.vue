<template>
  <div class="flex justify-between p-5 items-center px-32">
    <div class="text-2xl font-bold flex space-x-2 items-center">
      <img src="~/assets/images/wakanda-logo.svg" alt="logo-wakanda" class="h-8 w-8">
      <div>Wakanda</div>
    </div>
    <div class="flex items-center space-x-6 font-semibold">
      <div>Home</div>
      <div>About us</div>
      <div>How it works</div>
      <div>For Freelancer</div>
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
