<template>
    <div class="divide-y py-3 md:px-6 px-4">
      <div class="flex flex-wrap justify-center md:space-y-0 space-y-4 items-center md:justify-between py-1">
        <!-- Brand Logo starts here -->
        <div>
          <h1 class="text-xl md:text-2xl font-bold font-signika text-red-400">En<span class="text-red-600">Bot</span></h1>
        </div>
        <!-- Brand Logo ends here -->
        <div>
          <div class="md:flex hidden text-red-500 font-bold text-sm space-x-4 items-center">
            <a href="#" class="lab la-twitter"></a>
            <a href="#" class="lab la-facebook-f"></a>
            <a href="#" class="lab la-instagram"></a>
            <a href="#" class="lab la-github"></a>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap md:space-y-0 space-y-4 justify-between text-sm text-gray-500 py-3">
        <div>
          &copy; {{ new Date().getFullYear() }} All rights reserved
        </div>
        <div class="flex items-center space-x-6">
          <div>
            <a href="">Privacy and Policy</a>
          </div>
          <div>
            <a href="">Terms and Conditions</a>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  
  </script>
  
  <style>
    @media (max-width: 768px) {
      .text-xl {
        font-size: 1.5rem;
      }
  
      .md:text-2xl {
        font-size: 2rem;
      }
  
      .px-4 {
        padding-left: 1rem;
        padding-right: 1rem;
      }
  
      .py-3 {
        padding-top: 0.75rem;
        padding-bottom: 0.75rem;
      }
  
      .space-x-6 {
        margin-right: 1.5rem;
      }
  
      .md:space-x-12 {
        margin-right: 3rem;
      }
  
      .md:flex {
        display: flex;
      }
  
      .hidden {
        display: none;
      }
    }
  
    /* Tambahkan efek hover pada tautan */
    a {
      color: inherit;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    /* Tambahkan efek ikon pada media sosial */
    .lab {
      display: inline-block;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: #ff0000;
      text-align: center;
      line-height: 20px;
      color: #ffffff;
    }
  
    .lab.la-twitter {
      background-color: #1da1f2;
    }
  
    .lab.la-facebook-f {
      background-color: #1877f2;
    }
  
    .lab.la-instagram {
      background-color: #c32aa3;
    }
  
    .lab.la-github {
      background-color: #333333;
    }
  </style>
  