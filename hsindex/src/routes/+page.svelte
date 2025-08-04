<script>
  import { Button } from "flowbite-svelte";
</script>

<div class="text-center">
  <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white sm:text-5xl md:text-6xl">
    Hollowstring Studios
  </h1>
  <p class="mt-3 text-base text-gray-500 dark:text-gray-400 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl">
    An Indie Game Development Studio with the goal of creating experiences that are fun to interact with.
  </p>
  <div class="mt-5 sm:mt-8 sm:flex sm:justify-center">
    <div class="rounded-md shadow">
      <Button href="/about" color="dark">
        Learn More
      </Button>
    </div>
    <div class="mt-3 sm:mt-0 sm:ms-3">
      <Button href="/projects" color="light">
        Our Projects
      </Button>
    </div>
  </div>
</div>
