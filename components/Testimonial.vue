<template>
  <div class="px-32 p-16 flex flex-col items-center bg-gray-100">
    <div class="tracking-widest text-blue-600 font-semibold">
      TESTIMONIAL
    </div>
    <div class="text-5xl leading-relaxed font-bold text-center">
      See what they're saying
    </div>
    <div class="text-5xl leading-relaxed font-bold text-center">
      about us
    </div>
    <div class="grid grid-cols-3 gap-6 w-full mt-8">
      <TestimonyCard
        name="Cara Bedlord"
        description="Wakanda was amazing. I highly recommend for those who want to hire professional freelancer. The project was done quickly and high-quaility. Communication was clear and fast replies."
        image-name="testimony-one.svg"
      />
      <TestimonyCard
        name="Robert Fox"
        description="I'm so happy because the freelance talent we work with are more productive than we have ever thought. Recommend for people who want to find professional freelancer on this platform."
        image-name="testimony-two.svg"
      />
      <TestimonyCard
        name="Albert Flores"
        description="I am happy to say that I have hire couple of freelancers through Wakanda and they are high-quality ones. Working with them is not just easier; it has also been more effective. Having found a great freelance team, I cannot imagine switching to any other hiring platform."
        image-name="testimony-three.svg"
      />
      <TestimonyCard
        name="Kathryn Murphy"
        description="One of the best things about Wakanda is that it really simplifies the process of finding and hiring people. The quality is good as well, every freelancer I've hired has benn high-quality and professional. I would recommend this to anyone who needs a freelancer."
        image-name="testimony-four.svg"
      />
      <TestimonyCard
        name="Esther Howard"
        description="have used a lot of freelance hiring platforms, but none compare to Wakanda. The quality of freelancers that I can find here is unmatched and the service is top-notch. The customer service is also excellent, which cannot be said for my previous experiences in using other apps. I would highly recommend this product for anyone looking to hire a freelancer."
        image-name="testimony-five.svg"
      />
      <TestimonyCard
        name="Eleanor Pena"
        description="I have used a number of different freelance hiring platforms and none come close to Wakanda. The quality of the freelancers on here is top notch and it's easy to browse through the listings. I've been using it for six months now and I've found my perfect freelancer without any regrets whatsoever."
        image-name="testimony-six.svg"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'TestimonialComponent'
}
</script>
