<template>
<!-- Portfolio Section -->
<section id="portfolio" class="py-20 bg-white">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-3xl font-bold text-center mb-4">My Portfolio</h2>
    <p class="text-lg text-gray-600 text-center mb-12 max-w-2xl mx-auto">
      A selection of my recent design and video projects that highlight my creativity and expertise
    </p>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
      <!-- Project 1 -->
      <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition duration-300">
        <div class="h-48 overflow-hidden bg-gray-200 flex items-center justify-center">
          <img class="max-w-full h-full w-full object-cover" src="https://images.pexels.com/photos/4348404/pexels-photo-4348404.jpeg" alt="Brand Identity Design">
        </div>
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">Brand Identity Design</h3>
          <p class="text-gray-600 mb-4">Developed complete branding packages including logos, color palettes, and typography for businesses.</p>
          <button class="text-primary-600 font-medium hover:text-primary-700 transition">View Project →</button>
        </div>
      </div>

      <!-- Project 2 -->
      <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition duration-300">
        <div class="h-48 overflow-hidden bg-gray-200 flex items-center justify-center">
          <img class="max-w-full h-full w-full object-cover" src="https://www.searchenginejournal.com/wp-content/uploads/2023/02/video-editing-63e0bfec39a26-sej.png" alt="Video Editing Project">
        </div>
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">Video Editing</h3>
          <p class="text-gray-600 mb-4">Edited professional promotional videos with smooth transitions, effects, and sound design for clients.</p>
          <button class="text-primary-600 font-medium hover:text-primary-700 transition">View Project →</button>
        </div>
      </div>

      <!-- Project 3 -->
      <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition duration-300">
        <div class="h-48 overflow-hidden bg-gray-200 flex items-center justify-center">
          <img class="max-w-full h-full w-full object-cover" src="https://cdn.kwork.com/files/portfolio/t3/93/573cb9da4ec6bc97fb572593d6594491ef64a3e3-1701154730.jpg" alt="Poster Design">
        </div>
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">Creative Poster Design</h3>
          <p class="text-gray-600 mb-4">Designed eye-catching posters and marketing materials with strong visual impact and unique concepts.</p>
          <button class="text-primary-600 font-medium hover:text-primary-700 transition">View Project →</button>
        </div>
      </div>

      <!-- Project 4 -->
      <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition duration-300">
        <div class="h-48 overflow-hidden bg-gray-200 flex items-center justify-center">
          <img class="max-w-full h-full w-full object-cover" src="https://animationexplainers.com/wp-content/uploads/2021/11/motion-graphics.jpg" alt="Motion Graphics">
        </div>
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">Motion Graphics</h3>
          <p class="text-gray-600 mb-4">Produced animated intros, transitions, and engaging visuals for social media and marketing campaigns.</p>
          <button class="text-primary-600 font-medium hover:text-primary-700 transition">View Project →</button>
        </div>
      </div>
    </div>

    <div class="text-center mt-12">
      <button class="border border-primary-600 text-primary-600 hover:bg-primary-600 hover:text-white font-medium py-2 px-6 rounded-lg transition duration-300">
        View All Projects
      </button>
    </div>
  </div>
</section>


</template>
<script>
export default {
  name: 'WebPortfolio',
  }
</script>