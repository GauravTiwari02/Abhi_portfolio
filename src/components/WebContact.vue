<template>
      <!-- Contact Section -->
  <section id="contact" class="py-20 bg-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-bold text-center mb-4">Get In Touch</h2>
      <p class="text-lg text-gray-600 text-center mb-12 max-w-2xl mx-auto">Have a project in mind or want to discuss potential collaboration? Feel free to reach out!</p>

      <div class="flex flex-col md:flex-row gap-12">
        <div class="md:w-1/2">
          <form class="space-y-6">
            <div>
              <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Your Name</label>
              <input type="text" id="name" name="name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-primary-500 focus:border-primary-500" placeholder="John Doe">
            </div>
            <div>
              <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label>
              <input type="email" id="email" name="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-primary-500 focus:border-primary-500" placeholder="john@example.com">
            </div>
            <div>
              <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Your Message</label>
              <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-primary-500 focus:border-primary-500" placeholder="Tell me about your project..."></textarea>
            </div>
            <button type="submit" class="w-full bg-primary-600 hover:bg-primary-700 text-white font-medium py-3 px-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
              Send Message
            </button>
          </form>
        </div>

        <div class="md:w-1/2">
          <div class="bg-gray-50 p-8 rounded-xl h-full">
            <h3 class="text-xl font-semibold mb-6">Contact Information</h3>

            <div class="space-y-6">
              <div class="flex items-start">
                <svg class="w-6 h-6 text-primary-600 mt-1 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                </svg>
                <div>
                  <h4 class="font-medium text-gray-900">Email</h4>
                  <p class="text-gray-600">Abhisheksuyal384@gmail.com</p>
                </div>
              </div>

              <div class="flex items-start">
                <svg class="w-6 h-6 text-primary-600 mt-1 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                </svg>
                <div>
                  <h4 class="font-medium text-gray-900">Phone</h4>
                  <p class="text-gray-600">+91-8171664627</p>
                </div>
              </div>

              <div class="flex items-start">
                <svg class="w-6 h-6 text-primary-600 mt-1 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                </svg>
                <div>
                  <h4 class="font-medium text-gray-900">Location</h4>
                  <p class="text-gray-600">Nainital,Uttarakhand</p>
                </div>
              </div>
            </div>

            <div class="mt-8">
              <h4 class="font-medium text-gray-900 mb-4">Follow Me</h4>
              <div class="flex space-x-4">
                <a href="#" class="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center text-gray-700 hover:bg-primary-100 hover:text-primary-600 transition">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-2 16h-2v-6h2v6zm-1-6.891c-.607 0-1.1-.496-1.1-1.109 0-.612.492-1.109 1.1-1.109s1.1.497 1.1 1.109c0 .613-.493 1.109-1.1 1.109zm8 6.891h-1.998v-2.861c0-1.881-2.002-1.722-2.002 0v2.861h-2v-6h2v1.093c.872-1.616 4-1.736 4 1.548v3.359z" />
                  </svg>
                </a>
                <a href="#" class="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center text-gray-700 hover:bg-primary-100 hover:text-primary-600 transition">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" />
                  </svg>
                </a>
                <a href="#" class="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center text-gray-700 hover:bg-primary-100 hover:text-primary-600 transition">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm4.441 16.892c-2.102.144-6.784.144-8.883 0-2.276-.156-2.541-1.27-2.558-4.892.017-3.629.285-4.736 2.558-4.892 2.099-.144 6.782-.144 8.883 0 2.277.156 2.541 1.27 2.559 4.892-.018 3.629-.285 4.736-2.559 4.892zm-6.441-7.234l4.917 2.338-4.917 2.346v-4.684z" />
                  </svg>
                </a>
                <a href="#" class="w-10 h-10 bg-gray-100 rounded-full flex items-center justify-center text-gray-700 hover:bg-primary-100 hover:text-primary-600 transition">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm4.441 16.892c-2.102.144-6.784.144-8.883 0-2.276-.156-2.541-1.27-2.558-4.892.017-3.629.285-4.736 2.558-4.892 2.099-.144 6.782-.144 8.883 0 2.277.156 2.541 1.27 2.559 4.892-.018 3.629-.285 4.736-2.559 4.892zm-6.441-7.234l4.917 2.338-4.917 2.346v-4.684z" />
                  </svg>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

</template>

<script>
export default{
    name:'WebContact'
}
</script>