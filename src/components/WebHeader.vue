<template>
<nav class="bg-white shadow-sm fixed top-0 left-0 right-0 z-50">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between h-16">
      <!-- Logo -->
      <div class="flex items-center">
        <span class="text-xl font-bold text-primary-600">Abhishek Suyal</span>
      </div>

      <!-- Desktop Menu -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#home" class="text-gray-700 hover:text-primary-600 transition">Home</a>
        <a href="#about" class="text-gray-700 hover:text-primary-600 transition">About</a>
        <a href="#services" class="text-gray-700 hover:text-primary-600 transition">Services</a>
        <a href="#portfolio" class="text-gray-700 hover:text-primary-600 transition">Portfolio</a>
        <a href="#contact" class="text-gray-700 hover:text-primary-600 transition">Contact</a>
      </div>

      <!-- Mobile Menu Button -->
      <div class="md:hidden flex items-center">
        <button class="mobile-menu-button">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"></path>
          </svg>
        </button>
      </div>
    </div>
  </div>

  <!-- Mobile Menu (animated) -->
  <div class="mobile-menu max-h-0 overflow-hidden transition-all duration-500 ease-in-out bg-white md:hidden">
    <a href="#home" class="block px-4 py-2 text-gray-700 hover:bg-gray-100">Home</a>
    <a href="#about" class="block px-4 py-2 text-gray-700 hover:bg-gray-100">About</a>
    <a href="#services" class="block px-4 py-2 text-gray-700 hover:bg-gray-100">Services</a>
    <a href="#portfolio" class="block px-4 py-2 text-gray-700 hover:bg-gray-100">Portfolio</a>
    <a href="#contact" class="block px-4 py-2 text-gray-700 hover:bg-gray-100">Contact</a>
  </div>
</nav>

</template>
<script>    
export default {
  name: 'WebHeader',
  mounted() {
    document.title = "Abhishek Suyal - Graphic Designer";
  }
}
</script>

<style scoped></style>