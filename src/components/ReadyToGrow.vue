<template>
  <div class="bg-white py-4">
    <div class="max-w-md px-1 mx-auto">
      <h1 class="text-3xl md:text-4xl font-bold font-sgnika text-center animate-fade-in-down">Ready to improve your English language with EnBot?</h1>
      <div class="mt-8 flex justify-center">
        <a href="https://657801ece5dec61ef3f4966a--enbot-talkbot.netlify.app/" target="_blank" class="btn">Start Our Main Feature</a>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style>
  @media (max-width: 768px) {
    .text-3xl {
      font-size: 2.5rem;
    }

    .md:text-4xl {
      font-size: 3rem;
    }

    .px-1 {
      padding-left: 0.25rem;
      padding-right: 0.25rem;
    }

    .py-4 {
      padding-top: 1rem;
      padding-bottom: 1rem;
    }

    .mt-8 {
      margin-top: 2rem;
    }
  }

  /* Tambahkan efek animasi */
  .animate-fade-in-down {
    animation: fade-in-down 1s ease-in-out forwards;
  }

  .btn {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    background-color: #ff0000;
    color: #ffffff;
    padding: 0.75rem 1.5rem;
    border-radius: 0.25rem;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    font-weight: 600;
    text-decoration: none;
    transition: background-color 0.3s ease-in-out, transform 0.3s ease-in-out;
  }

  .btn:hover {
    background-color: #ff0000;
    transform: scale(1.1);
  }

  @keyframes fade-in-down {
    0% {
      opacity: 0;
      transform: translateY(-20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }
</style>
