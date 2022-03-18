<template>
  <div class="p-5 flex flex-col bg-white">
    <div class="flex space-x-3 items-center">
      <div class="w-12 h-12 rounded-full flex justify-center">
        <img :src="require(`~/assets/images/${imageName}`)" alt="testimony" class="h-full w-full">
      </div>
      <div class="flex flex-col space-y-1">
        <div class="font-semibold text-lg">
          {{ name }}
        </div>
        <div class="flex space-x-2 justify-content">
          <div v-for="index in 5" :key="'star-' + index">
            <img src="~/assets/images/review-star.svg" alt="review-star-icon" class="h-4 w-4">
          </div>
        </div>
      </div>
    </div>
    <div class="text-justify mt-2">
      {{ description }}
    </div>
  </div>
</template>

<script>
export default {
  name: 'TestimonialCard',
  props: {
    imageName: {
      type: String,
      default: 'testimony-one.svg'
    },
    name: {
      type: String,
      default: 'name'
    },
    description: {
      type: String,
      default: 'description'
    }
  }
}
</script>
