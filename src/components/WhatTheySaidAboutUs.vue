<template>
    <div>
      <div class="bg-gradient-to-b from-red-500 to-white p-[2rem] shadow-md shadow-orange-300">
        <div class="max-w-md mx-auto">
          <h1 class="text-white font-bold text-center text-3xl font-signika">Our satisfied clients love us! 😍</h1>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 px-[1rem] md:px-[6rem] mt-[3rem]">
          <div class="flex flex-col" v-for="testimony in testimonies" :key="testimony.title">
            <div class="relative bg-white rounded-xl py-4">
              <h1 class="font-signika text-red-600 text-center font-bold">{{ testimony.title }}</h1>
              <div class="md:px-[3rem] px-[1rem] text-center py-3">
                <p>{{ testimony.testimony }}</p>
              </div>
              <div class="bg-white md:right-64 right-[8rem] rotate-45 h-[1.5rem] w-[1.5rem] absolute"></div>
            </div>
            <div>
              <div class="flex justify-center mt-6 items-center space-x-4">
                <div>
                  <img src="../assets/icons/man.png" class="rounded-full h-[3rem] object-cover w-[3rem]" alt="">
                </div>
                <div class="leading-tight">
                  <h1 class="text-gray-800 font-signika font-bold">{{ testimony.testifiedBy }}</h1>
                  <p class="text-gray-800 text-sm">{{ testimony.company }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  import { reactive } from 'vue'
  
  const testimonies = reactive([
    {
      title: '"Incredible Experience"',
      testimony: 'We had an incredible experience working with Mixland and were impressed by the big difference they made in only three weeks. Our team is so grateful for the wonderful improvements they made and their ability to quickly understand the concept.',
      testifiedBy: 'Wande Warren',
      company: 'CEO ABC Corporation'
    },
    {
      title: '"Dependable Responsive Professional"',
      testimony: 'We had a great experience working with Mixland. They were dependable, responsive, and professional. They made a big difference in our project and quickly grasped the concept. We highly recommend them!',
      testifiedBy: 'Esther Howard',
      company: 'CEO Fintech Corporation'
    }
  ])
  </script>
  
  <style scoped>
  /* Tambahkan gaya untuk latar belakang dan warna teks */
  .bg-gradient-to-b {
    background-image: linear-gradient(to bottom, #EF4444, #FFFFFF);
  }
  
  .text-red-600 {
    color: #EF4444;
  }
  
  .text-white {
    color: #ffffff;
  }
  
  .text-slate-100 {
    color: #D1D5DB;
  }
  </style>
  