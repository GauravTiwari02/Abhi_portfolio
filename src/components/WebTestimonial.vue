<template>
   <!-- Testimonials Section -->
<section id="testimonials" class="py-20 bg-gray-50">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-3xl font-bold text-center mb-12">What Clients Say</h2>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <!-- Testimonial 1 -->
      <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
        <div class="flex items-center mb-6">
          <div class="w-14 h-14 rounded-full overflow-hidden mr-4">
            <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Client photo" class="w-full h-full object-cover">
          </div>
          <div>
            <h4 class="font-semibold">Sarah Johnson</h4>
            <p class="text-gray-600 text-sm">Founder, BrightBrands</p>
          </div>
        </div>
        <p class="text-gray-700 italic leading-relaxed">
          "Abhishek completely transformed our brand identity. From logo to marketing visuals, his creativity gave our business a professional edge. The feedback from our customers has been overwhelmingly positive."
        </p>
        <div class="flex mt-4">
          <span class="text-yellow-400">★★★★★</span>
        </div>
      </div>

      <!-- Testimonial 2 -->
      <div class="bg-white p-8 rounded-xl shadow-md hover:shadow-lg transition duration-300">
        <div class="flex items-center mb-6">
          <div class="w-14 h-14 rounded-full overflow-hidden mr-4">
            <img src="https://randomuser.me/api/portraits/men/43.jpg" alt="Client photo" class="w-full h-full object-cover">
          </div>
          <div>
            <h4 class="font-semibold">Michael Chen</h4>
            <p class="text-gray-600 text-sm">Marketing Director, GreenLeaf Media</p>
          </div>
        </div>
        <p class="text-gray-700 italic leading-relaxed">
          "Working with Abhishek was seamless. His video editing skills turned our campaign footage into engaging stories that drove results. He’s reliable, detail-oriented, and truly understands branding."
        </p>
        <div class="flex mt-4">
          <span class="text-yellow-400">★★★★★</span>
        </div>
      </div>
    </div>
  </div>
</section>

</template>
<script>
export default{
    name:'WebTestimonial',
}
</script>