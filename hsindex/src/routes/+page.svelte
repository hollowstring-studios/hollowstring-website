<script>
  import { Button } from "flowbite-svelte";
import c1 from '$lib/assets/others/terratop.webp';
import c2 from '$lib/assets/others/intruder.webp';
import c3 from '$lib/assets/others/untitled-land.webp';
</script>

<svelte:head>
  <title>Hollowstring Studios - Home</title>
  <meta name="description" content="Hollowstring Studios is an indie game development studio creating fun and interactive experiences. Explore our games like Terratop, Intruder, and Untitled Land." />
</svelte:head>

<div class="text-center">
  <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white sm:text-5xl md:text-6xl">
    Hollowstring Studios
  </h1>
  <p class="mt-3 text-base text-gray-500 dark:text-gray-400 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl">
    An Indie Game Development Studio with the goal of creating experiences that are fun to interact with.
  </p>
  <div class="mt-5 sm:mt-8 sm:flex sm:justify-center">
    <div class="rounded-md shadow">
      <Button href="/about">
        Learn More
      </Button>
    </div>
  </div>
</div>

<div class="mt-16">
  <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
    <div class="rounded-lg shadow-lg overflow-hidden">
      <img src={c1} alt="Terratop game" class="w-full h-48 object-cover">
    </div>
    <div class="rounded-lg shadow-lg overflow-hidden">
      <img src={c2} alt="Intruder game" class="w-full h-48 object-cover">
    </div>
    <div class="rounded-lg shadow-lg overflow-hidden">
      <img src={c3} alt="Untitled Land game" class="w-full h-48 object-cover">
    </div>
  </div>
</div>
