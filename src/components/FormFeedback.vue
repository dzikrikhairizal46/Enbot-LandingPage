<template>
  <div class="container mx-auto py-8">
    <h1 class="text-2xl font-bold text-center mb-4">Feedback Form</h1>
    <form class="max-w-md mx-auto">
      <div class="mb-4">
        <label for="name" class="block font-semibold mb-2 text-gray-700">Your Name</label>
        <input type="text" id="name" v-model="name" class="w-full border border-gray-300 rounded p-2 focus:outline-none focus:border-blue-500" />
      </div>
      <div class="mb-4">
        <label for="email" class="block font-semibold mb-2 text-gray-700">Your Email</label>
        <input type="email" id="email" v-model="email" class="w-full border border-gray-300 rounded p-2 focus:outline-none focus:border-blue-500" />
      </div>
      <div class="mb-4">
        <label for="message" class="block font-semibold mb-2 text-gray-700">Message</label>
        <textarea id="message" v-model="message" class="w-full border border-gray-300 rounded p-2 focus:outline-none focus:border-blue-500"></textarea>
      </div>
      <button type="submit" class="bg-red-500 hover:bg-red-600 text-white py-2 px-4 rounded-full transition-colors duration-200">Submit</button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: '',
      email: '',
      message: '',
    };
  },
};
</script>

<style>
input[type="text"],
input[type="email"],
textarea {
  height: 40px;
}

.container {
  padding: 2rem;
}

@media (max-width: 640px) {
  .container {
    padding: 1rem;
  }
}
</style>
