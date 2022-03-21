<template>
  <div class="h-full w-full px-5 md:px-32 p-10">
    <div class="flex flex-col md:flex-row space-y-5">
      <div class="flex flex-col w-full md:w-1/2 space-y-5">
        <div class="text-3xl md:text-5xl font-bold leading-relaxed">
          Recruit top talented freelancer for your business
        </div>
        <div class="leading-relaxed">
          Connect you to thousands of talented freelancers from any industry. You can have the best people in just few simple steps
        </div>
        <div>
          <button class="p-3 bg-blue-700 text-white px-6 rounded-lg font-bold">
            Get started
          </button>
        </div>
      </div>
      <div class="w-full md:w-1/2 h-full flex justify-center">
        <img src="~/assets/images/hero-person.svg" alt="hero-person" style="width:30rem;">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroComponent'
}
</script>
