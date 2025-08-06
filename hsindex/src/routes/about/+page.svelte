<script>
import f1 from '$lib/assets/founders/nabir14.webp';
import f2 from '$lib/assets/founders/ankan.webp';
import f3 from '$lib/assets/founders/moshfiq.webp';
import f4 from '$lib/assets/founders/oneil.webp';
</script>

<svelte:head>
  <title>About Hollowstring Studios</title>
  <meta name="description" content="Learn about Hollowstring Studios, an indie game development company founded in 2025. Meet the team and discover our passion for creating immersive gaming experiences." />
  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "name": "Hollowstring Studios",
      "url": "https://hollowstring.com",
      "logo": "https://hollowstring.com/logo.png",
      "description": "An Indie Game Development Studio with the goal of creating experiences that are fun to interact with.",
      "founder": [
        {
          "@type": "Person",
          "name": "MD Mushfique Farhan Nabir",
          "jobTitle": "Co-founder & Lead Developer"
        },
        {
          "@type": "Person",
          "name": "Ankan Das",
          "jobTitle": "Co-founder & Lead Artist"
        },
        {
          "@type": "Person",
          "name": "MD Moshfiqur Rahman Khan",
          "jobTitle": "Co-founder & Lead Designer"
        }
      ]
    }
  </script>
</svelte:head>
<h1 class="text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white sm:text-5xl md:text-6xl text-center mb-8">
    About Hollowstring Studios
  </h1>
  <div class="mt-16">
    <h2 class="text-3xl font-extrabold tracking-tight text-gray-900 dark:text-white text-center mb-8">Meet the Founders</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="bg-white dark:bg-gray-700 rounded-lg shadow-lg p-6 text-center">
        <img class="w-64 h-64 object-cover rounded-full mx-auto mb-4" src={f1} alt="Founder 1">
        <h3 class="text-xl font-bold text-gray-900 dark:text-white mb-2">MD Mushfique Farhan Nabir</h3>
        <p class="text-gray-700 dark:text-gray-400">Co-founder & Lead Developer</p>
      </div>
      <div class="bg-white dark:bg-gray-700 rounded-lg shadow-lg p-6 text-center">
        <img class="w-64 h-64 object-cover rounded-full mx-auto mb-4" src={f2} alt="Founder 2">
        <h3 class="text-xl font-bold text-gray-900 dark:text-white mb-2">Ankan Das</h3>
        <p class="text-gray-700 dark:text-gray-400">Co-founder & Lead Artist</p>
      </div>
      <div class="bg-white dark:bg-gray-700 rounded-lg shadow-lg p-6 text-center">
        <img class="w-64 h-64 object-cover rounded-full mx-auto mb-4" src={f3} alt="Founder 3">
        <h3 class="text-xl font-bold text-gray-900 dark:text-white mb-2">MD Moshfiqur Rahman Khan</h3>
        <p class="text-gray-700 dark:text-gray-400">Co-founder & Lead Designer</p>
      </div>
    </div>
  </div>

  <div class="container mx-auto px-4 py-8">
  <div class="prose prose-lg mx-auto dark:prose-invert">
    <p class="text-white">
    Founded in 2025, Hollowstring Studios emerged from the rebranding of Orthos Studios. The original studio, also established by the same three founders, initially developed both games and applications. However, this dual focus led to significant challenges, including project delays and team fragmentation.
    <br><br>
    As Orthos Studios grew, it began to lose its creative focus, becoming more corporate in nature. Recognizing this, the founders decided to restructure and refocus their vision. Thus, Hollowstring Studios was born.
    <br><br>
    Hollowstring Studios is a dedicated indie game studio, returning to the founders' original passion for creating immersive and enjoyable gaming experiences. Our focus is not solely on financial success, but on the creative satisfaction that comes from building games we love. We are a small, passionate team committed to crafting unique and engaging worlds for our players.
    </p>
  </div>
</div>
