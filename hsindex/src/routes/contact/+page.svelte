<svelte:head>
  <title>Contact Hollowstring Studios</title>
  <meta name="description" content="Contact Hollowstring Studios for inquiries, collaborations, or to learn more about our indie game development projects. Reach out to us via email or our contact form." />
</svelte:head>

<div class="container mx-auto px-4 py-8">
  <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white sm:text-5xl md:text-6xl text-center mb-8">
    Contact Us
  </h1>
  <p class="text-center text-white pb-4">
  Besides making games we are also open for work with other teams.
  <br>You can contact us if you want to work with us.
  </p>
  <div class="max-w-lg mx-auto">
    <form class="bg-white dark:bg-gray-700 rounded-lg shadow-md p-8" action="https://formsubmit.co/hollowstringstudios@gmail.com" method="POST">
      <div class="mb-4">
        <label for="name" class="block text-gray-700 dark:text-gray-300 font-bold mb-2">Name</label>
        <input type="text" id="name" name="name" class="w-full px-3 py-2 border rounded-lg text-gray-700 dark:text-gray-300 bg-white dark:bg-gray-800 focus:outline-none focus:border-primary-500" />
      </div>
      <div class="mb-4">
        <label for="email" class="block text-gray-700 dark:text-gray-300 font-bold mb-2">Email</label>
        <input type="email" id="email" name="email" class="w-full px-3 py-2 border rounded-lg text-gray-700 dark:text-gray-300 bg-white dark:bg-gray-800 focus:outline-none focus:border-primary-500" />
      </div>
      <div class="mb-4">
        <label for="message" class="block text-gray-700 dark:text-gray-300 font-bold mb-2">Message</label>
        <textarea id="message" name="message" rows="5" class="w-full px-3 py-2 border rounded-lg text-gray-700 dark:text-gray-300 bg-white dark:bg-gray-800 focus:outline-none focus:border-primary-500"></textarea>
      </div>
      <div class="text-center">
        <button type="submit" class="bg-primary-500 hover:bg-primary-700 text-white font-bold py-2 px-4 rounded-lg">
          Send Message
        </button>
      </div>
    </form>
    <div class="text-center mt-8">
      <p class="text-gray-700 dark:text-gray-300">You can also reach us at:</p>
      <a href="mailto:hollowstringstudios@gmail.com" class="text-primary-500 hover:underline">hollowstringstudios@gmail.com</a>
    </div>
  </div>
</div>
