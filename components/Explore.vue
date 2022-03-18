<template>
  <div class="px-32 bg-blue-200 pt-16">
    <div class="flex">
      <div class="flex flex-col w-1/2 space-y-5">
        <div class="text-5xl font-bold leading-relaxed">
          Explore and hire talent from our platform
        </div>
        <div class="leading-relaxed">
          We've got experts for every industry - all under one roof!
          You can find everything from WordPress developers to Graphic designers to
          copywriters and many more at Wakanda.
        </div>
        <div>
          <button class="p-3 bg-blue-700 text-white px-6 rounded-lg font-bold">
            Explore now
          </button>
        </div>
      </div>
      <div class="w-1/2 h-full flex justify-center">
        <img src="~/assets/images/hero-person-two.svg" alt="hero-person" style="width:30rem;">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ExploreComponent'
}
</script>
