<template>
  <div>
    <div class="flex md:flex-row flex-col items-center justify-center px-4 md:px-[6rem] bg-gray-100">
      <div class="md:w-1/3 md:py-[4rem] py-[1rem]">
        <div class="space-y-4">
          <div>
            <h1 class="text-4xl md:text-5xl font-semibold font-signika animate-fade-side-right text-black">Start learning TOEFL easily, anywhere, anytime with EnBot</h1>
          </div>
          <p class="text-base md:text-lg text-black">Becoming a TOEFL platform that facilitates you in learning TOEFL structure, especially in speaking and listening.</p>
          <div>
            <a href="https://657801ece5dec61ef3f4966a--enbot-talkbot.netlify.app/" target="_blank" class="transform hover:scale-110 transition-transform duration-300 bg-gradient-to-r from-purple-500 to-pink-500 flex items-center space-x-1 font-medium rounded-md shadow-md text-sm md:text-base capitalize text-white px-4 py-3">
              <span>Try our main feature</span>
              <span class="las la-arrow-right text-lg font-extrabold"></span>
            </a>
          </div>
        </div>
      </div>

      <div class="md:w-2/3">
        <img class="w-full transform hover:scale-110 transition-transform duration-300" src="../assets/icons/4.png" alt="">
      </div>
    </div>
  </div>
</template>

<style>
  /* Tambahkan warna latar belakang dan perubahan tampilan tombol */
  .bg-gradient-to-r {
    background-image: linear-gradient(to right, #8B5CF6, #EC4899);
  }

  .shadow-md {
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
  }

  /* Ubah warna teks menjadi putih */
  .text-white {
    color: #ffffff;
  }

  /* Tambahkan efek animasi ke judul */
  .animate-fade-side-right {
    animation: fadeSideRight 1s ease-in-out forwards;
  }

  @keyframes fadeSideRight {
    0% {
      opacity: 0;
      transform: translateX(-20px);
    }
    100% {
      opacity: 1;
      transform: translateX(0);
    }
  }

  /* Tambahkan perubahan responsif menggunakan media query */
  @media (max-width: 768px) {
    .flex {
      flex-direction: column-reverse;
    }

    .md:w-1/3,
    .md:w-2/3 {
      width: 100%;
    }

    .md:px-[6rem] {
      padding-left: 1rem;
      padding-right: 1rem;
    }

    .md:py-[4rem] {
      padding-top: 1rem;
      padding-bottom: 1rem;
    }

    .text-4xl {
      font-size: 3rem;
    }

    .text-base {
      font-size: 0.875rem;
    }

    .text-sm {
      font-size: 0.75rem;
    }

    .md:text-base {
      font-size: 1rem;
    }

    .px-4 {
      padding-left: 0.5rem;
      padding-right: 0.5rem;
    }

    .py-3 {
      padding-top: 0.75rem;
      padding-bottom: 0.75rem;
    }
  }
</style>
