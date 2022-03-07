<template>
  <div class="flex w-full bg-black bg-opacity-80 fixed header" style="top:0;">
    <div class="w-1/4"></div>
    <div class="w-2/4 w-full items-center justify-end hidden mx-4 md:flex justify-center">
      <ul class="items-center text-base mr-6 hidden md:flex header ">
        <li class="mx-3">
          <a href="/"><span class="text-white">MAIN</span></a>
        </li>
        <li class="mx-3">
          <a href="#Write"><span class="text-white">ABOUT</span></a>
        </li>
        <li class="mx-3">
          <a href="#Cards"><span class="text-white">CARDS</span></a>
        </li><li class="mx-3">
          <a href="#Team"><span class="text-white">TEAM</span></a>
        </li>
        <li class="mx-3">
          <a href="#Roadmap"><span class="text-white">ROADMAP</span></a>
        </li>
        <li class="mx-3">
          <a href="#Footer"><span class="text-white">CONTACTUS</span></a>
        </li>
        
      </ul>
    </div>
    <div class="w-1/4  justify-start items-center flex justify-second mx-auto hidden md:flex">
      
          <img src="./../assets/images/connect_button.png" style="width:80%;">
     
    </div>
    <div class="md:hidden flex items-center" style="margin-left:auto;">
      <button class="outline-none mobile-menu-button">
        <svg
          class="w-6 h-6 text-gray-500"
          x-show="!showMenu"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
        <path d="M4 6h16M4 12h16M4 18h16"></path>
        </svg>
      </button>
    </div>
    
    <!-- Mobile menu -->
    <div class="hidden mobile-menu">
      <ul class="">
        <li class="active"><a href="/" class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold">Home</a></li>
        <li><a href="#services" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Services</a></li>
        <li><a href="#about" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">About</a></li>
        <li><a href="#contact" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Contact Us</a></li>
      </ul>
    </div>
  </div>
    
  
</template> 

<script>
export default {
  
};

</script>
