<template>
  <div class="bg-gray-50 py-12 px-4 md:px-16">
    <div class="flex flex-col-reverse md:flex-row items-center">
      <div class="md:w-1/2">
        <img src="../assets/icons/man.png" class="h-72 md:h-auto mx-auto md:mx-0 animate-fade-in-left" alt="">
      </div>
      <div class="md:w-1/2 mt-8 md:mt-0">
        <h1 class="text-3xl md:text-4xl font-bold font-sgnika py-3 animate-fade-in-right">Speak Freely with EnBot</h1>
        <p class="leading-tight text-gray-500 mt-3 animate-fade-in-right">We offer features for those who lack confidence in their English speaking abilities. Speak about anything with EnBot as if it were your closest companion, boosting your confidence along the way</p>
      </div>
    </div>
  </div>
</template>

<style>
@keyframes fade-in-left {
  0% {
    opacity: 0;
    transform: translateX(-20px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes fade-in-right {
  0% {
    opacity: 0;
    transform: translateX(20px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.animate-fade-in-left {
  animation: fade-in-left 1s ease-in-out forwards;
}

.animate-fade-in-right {
  animation: fade-in-right 1s ease-in-out forwards;
}

@media (max-width: 767px) {
  .flex-col-reverse {
    flex-direction: column;
  }

  .md:w-1/2 {
    width: 100%;
  }

  .h-72 {
    height: auto;
  }
}
</style>
