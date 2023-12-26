<template>
    <div>
      <div class="py-[3rem] px-[1rem] md:px-[8rem]">
        <h1 class="text-2xl font-bold text-center font-signika">Features for a better experience</h1>
        <div class="flex flex-wrap md:space-y-0 space-y-8 justify-between my-6 items-center">
          <div class="flex md:flex-row items-center space-y-3 md:space-y-0 flex-col space-x-3 md:w-[30%]">
            <a href="https://6577fa9d946ff519cb0245c1--enbot-chatbot.netlify.app/" target="_blank" class="feature-link">
              <div>
                <span class="las orangered bg-orange-100 px-2 py-2 rounded-full la-comments text-xl"></span>
              </div>
              <div class="space-y-2">
                <h1 class="font-extrabold text-center md:text-left">Chat Bot</h1>
                <p class="leading-tight text-center md:text-left">Seamless conversational experience. Learn English effortlessly with our chatbot</p>
              </div>
            </a>
          </div>
          <div class="flex md:flex-row items-center space-y-3 md:space-y-0 flex-col space-x-3 md:w-[30%]">
            <a href="https://657801ece5dec61ef3f4966a--enbot-talkbot.netlify.app/" target="_blank" class="feature-link">
              <div>
                <span class="las text-emerald-600 bg-emerald-100 px-2 py-2 rounded-full la-robot text-xl"></span>
              </div>
              <div class="space-y-2">
                <h1 class="font-extrabold text-center md:text-left">Talk Bot</h1>
                <p class="leading-tight text-center md:text-left">Converse, learn, and explore with TalkBot—your interactive language companion</p>
              </div>
            </a>
          </div>
          <div class="flex md:flex-row flex-col items-center space-y-3 md:space-y-0 space-x-3 md:w-[30%]">
            <a href="https://65899d59215c8cf2506c9bad--enbot-doctorwords.netlify.app/" target="_blank" class="feature-link">
              <div>
                <span class="las text-pink-600 bg-pink-100 px-2 py-2 rounded-full la-spell-check text-xl"></span>
              </div>
              <div class="space-y-2">
                <h1 class="font-extrabold text-center md:text-left">Doctor Words</h1>
                <p class="leading-tight text-center md:text-left">Embrace the English Language with Our Dictionary</p>
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  
  </script>
  
  <style>
  .orangered {
    color: orangered;
  }
  
  /* Efek saat kursor mengarah ke fitur */
  .feature-link:hover {
    transform: scale(1.05); /* Ubah sesuai keinginan */
    transition: transform 0.3s ease; /* Ubah sesuai keinginan */
  }
  
  </style>
  