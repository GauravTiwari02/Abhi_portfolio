<template>
<!-- About Section -->
<section id="about" class="py-20 bg-white">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-3xl font-bold text-center mb-12">About Me</h2>
    <div class="flex flex-col md:flex-row items-center gap-12">
      <!-- Profile Image -->
      <div class="md:w-1/3 flex justify-center">
        <div class="w-50 h-80 bg-gray-200 rounded-lg overflow-hidden shadow-md">
          <img class="max-w-full h-full object-fill transform hover:scale-105 transition duration-500 animate-fadeIn" src="../assets/abhi.png" alt="me">
        </div>
      </div>

      <!-- About Content -->
      <div class="md:w-2/3">
        <p class="text-lg text-gray-600 mb-6">
          I'm a passionate <span class="font-semibold">Graphic Designer & Video Editor</span> with a strong eye for detail and creativity. 
          I specialize in crafting stunning visuals, branding assets, and motion graphics that bring ideas to life. 
          With expertise in both design and video production, I help businesses and individuals tell their stories in a visually compelling way. 
          My focus is on delivering designs and edits that are not only visually appealing but also impactful and meaningful.
        </p>

        <!-- Skills -->
        <div class="mb-6">
          <h3 class="text-xl font-semibold mb-4">My Skills</h3>
          <div class="flex flex-wrap gap-3">
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Adobe Photoshop</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Adobe Illustrator</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Adobe Premiere Pro</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">After Effects</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Canva</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Motion Graphics</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Branding</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Video Editing</span>
            <span class="bg-gray-100 px-4 py-2 rounded-full text-sm font-medium">Content Creation</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

</template>

<script>
export default {
  name: 'WebAbout'
}
</script>
<style scoped>
</style>