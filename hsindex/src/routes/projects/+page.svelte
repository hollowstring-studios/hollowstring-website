<script>
import i1 from '$lib/assets/others/tt-icon.webp';
import i2 from '$lib/assets/others/intruder.webp';
import i3 from '$lib/assets/others/ul-icon.webp';
</script>

<svelte:head>
  <title>Hollowstring Studios - Projects</title>
  <meta name="description" content="Explore the game projects from Hollowstring Studios, including Terratop, Intruder, and Untitled Land. See our upcoming and released indie games." />
  <script type="application/ld+json">
    [
      {
        "@context": "https://schema.org",
        "@type": "VideoGame",
        "name": "Terratop",
        "description": "A 2D Survival Game where you have to collect resources and survive as long as you can.",
        "image": "https://hollowstring.com/tt-icon.webp",
        "url": "https://hollowstring-studios.itch.io/terratop",
        "gamePlatform": ["PC", "Mobile"]
      },
      {
        "@context": "https://schema.org",
        "@type": "VideoGame",
        "name": "Intruder",
        "description": "A 3D horror game about scaring people without getting caught.",
        "image": "https://hollowstring.com/intruder.webp",
        "url": "https://hollowstring.com/projects",
        "gamePlatform": ["PC"]
      },
      {
        "@context": "https://schema.org",
        "@type": "VideoGame",
        "name": "Untitled Land",
        "description": "A 3D sandbox game About planet colonization.",
        "image": "https://hollowstring.com/ul-icon.webp",
        "url": "https://hollowstring.com/projects",
        "gamePlatform": ["PC"]
      }
    ]
  </script>
</svelte:head>
<div class="container mx-auto px-4 py-8">
  <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white sm:text-5xl md:text-6xl text-center mb-8">
    Our Projects
  </h1>
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
    <div class="bg-white dark:bg-gray-700 rounded-lg shadow-md overflow-hidden flex flex-col">
      <img src={i1} alt="Terratop game icon" class="w-full h-48 object-cover">
      <div class="p-6 flex flex-col flex-grow">
        <h2 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Terratop</h2>
        <p class="text-gray-700 dark:text-gray-300 mb-4">
          A 2D Survival Game where you have to collect resources and survive as long as you can.
        </p>
        <a href="https://hollowstring-studios.itch.io/terratop" class="text-primary-500 hover:underline mt-auto">Learn More</a>
      </div>
    </div>
    <div class="bg-white dark:bg-gray-700 rounded-lg shadow-md overflow-hidden flex flex-col">
      <img src={i2} alt="Intruder game icon" class="w-full h-48 object-cover">
      <div class="p-6 flex flex-col flex-grow">
        <h2 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Intruder</h2>
        <p class="text-gray-700 dark:text-gray-300 mb-4">
         A 3D horror game about scaring people without getting caught.
        </p>
        <a href="/projects" class="text-primary-500 hover:underline mt-auto">Coming Soon</a>
      </div>
    </div>
    <div class="bg-white dark:bg-gray-700 rounded-lg shadow-md overflow-hidden flex flex-col">
      <img src={i3} alt="Untitled Land game icon" class="w-full h-48 object-cover">
      <div class="p-6 flex flex-col flex-grow">
        <h2 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Untitled Land</h2>
        <p class="text-gray-700 dark:text-gray-300 mb-4">
          A 3D sandbox game About planet colonization.
        </p>
        <a href="/projects" class="text-primary-500 hover:underline mt-auto">Coming Soon</a>
      </div>
    </div>
  </div>
</div>
