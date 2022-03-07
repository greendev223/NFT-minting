<template>
  <div class="bg-black " id="Footer">
  <div class=" flex">
      <div class="w-2/12"></div>
      <div class="w-2/12 mt-5">
        <img src="./../assets/images/logo1.png">
      </div>
      
      <div class="w-4/12 w-full
        h-full
        items-center
        justify-end
        mx-4
        hidden
        md:flex
        justify-center
        mt-10">
        <ul class="items-center text-base mr-6 hidden xl:flex">
        <li class="mx-3">
          <router-link to="/"><span class="text-white">MAIN</span></router-link>
        </li>
        <li class="mx-3">
          <router-link to="/"><span class="text-white">ABOUT</span></router-link>
        </li>
        <li class="mx-3">
          <router-link to="/"><span class="text-white">CADS</span></router-link>
        </li><li class="mx-3">
          <router-link to="/"><span class="text-white">TEAM</span></router-link>
        </li>
        <li class="mx-3">
          <router-link to="/"><span class="text-white">ROADMAP</span></router-link>
        </li>
        <li class="mx-3">
          <router-link to="/"><span class="text-white">CONTACT US</span></router-link>
        </li>
      </ul>
        
      </div>
      <div class="w-2/12 mt-5 justify-center f_btn_hidden">
        <img src="./../assets/images/connect_button.png">
      </div>
      <div class="w-2/12"></div>
      
  </div>
  
    <img src="./../assets/images/footer_char.png" class="mx-auto " >
    <p class="text-white text-center mx-auto mt-5">SOCIAL</p>
    <div class="flex space-x-6 justify-center mt-5">
        <img src="./../assets/images/Vector.png"/>
        <img src="./../assets/images/Vector1.png"/>
        <img src="./../assets/images/Vector2.png"/>
        <img src="./../assets/images/Vector3.png"/>
    </div>
    <br><br><br>
  
  </div>
  
</template> 

<script>
//import SearchField from "../components/SearchField.vue";

export default {
  name: "Stack",
  // components: {
  //   SearchField,
  // },
};
</script>
