<template>
  <div class="bg-blue-600 px-5 md:px-32 flex flex-col items-center w-full h-full text-white p-16">
    <div class="tracking-widest text-lg">
      FEATURE
    </div>

    <div class="text-5xl font-bold text-wrap text-center">
      The benefit of using our platform
    </div>

    <div class="grid grid-cols-3 gap-5 mt-12 md:mt-24">
      <div class="flex flex-col space-y-3 col-span-3 md:col-span-1">
        <div class="w-24 h-24 bg-blue-100 rounded-full p-6">
          <div class="text-center text-black w-full h-full">
            <img src="~/assets/images/prize.svg" alt="logo-prize" class="h-12 w-12">
          </div>
        </div>
        <div class="text-xl font-semibold">
          Professional &#38; Fast
        </div>
        <div>
          Search and hire the most talented freelancers to match your needs.
          No matter what you need done, we've got the perfect freelancer for you.
        </div>
      </div>

      <div class="flex flex-col space-y-3 col-span-3 md:col-span-1">
        <div class="w-24 h-24 bg-blue-100 rounded-full p-6">
          <div class="text-center text-black w-full h-full">
            <img src="~/assets/images/support.svg" alt="logo-support" class="h-12 w-12">
          </div>
        </div>
        <div class="text-xl font-semibold">
          24/7 support
        </div>
        <div>
          You have any concerns or questions? Don't worry,
          we have our support team to help you at anytime and anywhere.
        </div>
      </div>

      <div class="flex flex-col space-y-3 col-span-3 md:col-span-1">
        <div class="w-24 h-24 bg-blue-100 rounded-full p-6">
          <div class="text-center text-black w-full h-full">
            <img src="~/assets/images/shield.svg" alt="logo-shield" class="h-12 w-12">
          </div>
        </div>
        <div class="text-xl font-semibold">
          Safe &#38; Secure
        </div>
        <div>
          We know that safety is the most important thing for our customer,
          so all of our payments are processed instantly and securely.
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BenefitComponent'
}
</script>
