<template>
  <div>
    <div class="flex items-center justify-between py-[1rem] px-4 md:px-[6rem]">
      <!-- Brand Logo starts here -->
      <div>
        <h1 class="text-xl font-bold font-signika text-red-400">En<span class="text-red-600">Bot</span></h1>
      </div>
      <!-- Brand Logo ends here -->
      <!-- Router links starts here -->
      <div class="md:flex space-x-6 capitalize hidden">
        <div>
          <a href="https://6577fa9d946ff519cb0245c1--enbot-chatbot.netlify.app/" target="_blank" class="nav-link">ChatBot</a>
        </div>
        <div>
          <a href="https://657801ece5dec61ef3f4966a--enbot-talkbot.netlify.app/" target="_blank" class="nav-link">TalkBot</a>
        </div>
        <div>
          <a href="https://65899d59215c8cf2506c9bad--enbot-doctorwords.netlify.app/" target="_blank" class="nav-link">Doctor Words</a>
        </div>
      </div>
      <!-- Router links ends here -->
      
      <div class="md:hidden block" @click="showSidebar">
        <span class="las la-bars text-xl font-extrabold" v-if="!navBarShouldShow"></span>
        <span v-else class="las la-times text-xl font-extrabold"></span>
      </div>
    </div>
    <div v-if="navBarShouldShow" class="bg-white w-full animate-fade-in-down py-[2rem] shadow-sm shadow-orange-200 relative block md:hidden">
      <div class="divide-y px-[1rem]">
        <div class="py-4 text-lg font-bold">
          <a href="https://6577fa9d946ff519cb0245c1--enbot-chatbot.netlify.app/" target="_blank" class="nav-link">ChatBot</a>
        </div>
        <div class="py-4 text-lg font-bold">
          <a href="https://657801ece5dec61ef3f4966a--enbot-talkbot.netlify.app/" target="_blank" class="nav-link">TalkBot</a>
        </div>
        <div class="py-4 text-lg font-bold">
          <a href="https://65899d59215c8cf2506c9bad--enbot-doctorwords.netlify.app/" target="_blank" class="nav-link">Doctor Words</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const navBarShouldShow = ref(false)

function showSidebar() {
  navBarShouldShow.value = !navBarShouldShow.value
}
</script>

<style scoped>
.nav-link {
  transition: all 0.3s ease;
}

.nav-link:hover {
  color: red; /* Ubah warna sesuai keinginan */
  /* Tambahkan efek animasi atau perubahan visual lainnya */
}
</style>
