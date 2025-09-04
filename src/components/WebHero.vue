<template>

  <!-- Hero Section -->
  <section id="home" class="py-20 bg-gradient-to-r from-indigo-50 to-blue-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex flex-col md:flex-row items-center justify-between">
        <div class="md:w-1/2 mb-10 md:mb-0">
        <h1 class="text-4xl md:text-5xl font-bold mb-4 animate-fadeIn">
  Hi, I'm <span class="text-primary-600">Abhishek Suyal</span>
</h1>
<p class="text-xl text-gray-600 mb-8 animate-fadeIn animation-delay-200">
  I create stunning graphics, visual identities, and digital artwork that bring ideas to life
</p>

          <button class="bg-primary-600 hover:bg-primary-700 text-white font-medium py-3 px-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 animate-fadeIn animation-delay-400">
            Hire Me
          </button>
        </div>
        <div class="md:w-1/2 flex justify-center">
  <div class="w-64 h-64 md:w-96 md:h-96 bg-primary-100 rounded-2xl flex items-center justify-center overflow-hidden shadow-xl">
    <!-- Profile image -->
    <img 
      :src="heroImage" 
      alt="Abhishek Suyal" 
      class="w-full h-full object-fill transform hover:scale-105 transition duration-500 animate-fadeIn animation-delay-600"
    />
  </div>
</div>

      </div>
    </div>
  </section>
</template>
<script>
import assets from '../assets/IMG_7151.jpg';
export default {
  name: 'WebHero',
  data() {
    return {
      heroImage: assets
    }
  }
}
</script>