<script>
import i1 from '$lib/assets/others/tt-icon.webp';
import i2 from '$lib/assets/others/intruder.webp';
import i3 from '$lib/assets/others/ul-icon.webp';
</script>
<div class="container mx-auto px-4 py-8">
  <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white sm:text-5xl md:text-6xl text-center mb-8">
    Our Projects
  </h1>
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
    <div class="bg-white dark:bg-gray-700 rounded-lg shadow-md overflow-hidden">
      <img src={i1} alt="Project 1" class="w-full h-48 object-cover">
      <div class="p-6">
        <h2 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Terratop</h2>
        <p class="text-gray-700 dark:text-gray-300 mb-4">
          A brief description of Project 1. This could be a 2D platformer, a puzzle game, or anything else.
        </p>
        <a href="https://hollowstring-studios.itch.io/terratop" class="text-primary-500 hover:underline">Learn More</a>
      </div>
    </div>
    <div class="bg-white dark:bg-gray-700 rounded-lg shadow-md overflow-hidden">
      <img src={i2} alt="Project 2" class="w-full h-48 object-cover">
      <div class="p-6">
        <h2 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Intruder</h2>
        <p class="text-gray-700 dark:text-gray-300 mb-4">
         A 3D horror game about scaring people without getting caught.
        </p>
        <a href="/projects" class="text-primary-500 hover:underline">Coming Soon</a>
      </div>
    </div>
    <div class="bg-white dark:bg-gray-700 rounded-lg shadow-md overflow-hidden">
      <img src={i3} alt="Project 3" class="w-full h-48 object-cover">
      <div class="p-6">
        <h2 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Untitled Land</h2>
        <p class="text-gray-700 dark:text-gray-300 mb-4">
          A 3D sandbox game About planet colonization.
        </p>
        <a href="/projects" class="text-primary-500 hover:underline">Coming Soon</a>
      </div>
    </div>
  </div>
</div>
