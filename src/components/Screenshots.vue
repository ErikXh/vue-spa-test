<template>

<!-- Screenshots section-->
<section class="bg-white w-full py-6">
  <div class="grid justify-center content-center">
    <div class="container max-w-7xl mx-auto flex flex-col text-center w-3/6">
     <div class="py-3">
       <h1 class="font-light text-xl text-gray-600 uppercase">
          app screenshots
       </h1>
       <p class="text-sm text-gray-500 font-light py-3">
         Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
         Molestiae magni, quas facere nulla nemo aliquid possimus accusantium aperiam vitae quod.
       </p>
     </div>
    </div>
      <!-- Screenshots section -->
     <div class="container mx-auto flex justify-center content-center">
      <div class="flex content-center px-3">
        <button type="button" class="left-click-js">
          <i class="ri-arrow-left-s-line green-circle text-green-300 font-light text-xl"></i>
        </button>
      </div>
      <div class="w-10/12 flex justify-center">
        <img src="./img/vertical_phone.png" 
        alt="image of a phone with screenshots of the app" class="object-contain">
        <div class="container relative top-3 hidden ">
          <img src="./img/phone_view.jpeg" alt="screenshot of the app" class="object-contain">
        </div>    
      </div>
       <div class="flex content-center px-3">
         <button type="button" class="right-click-js">
          <i class="ri-arrow-right-s-line green-circle text-green-300 font-light text-xl"></i>
      </button>
       </div>
     </div>
     
 </div>
</section>

</template>

<script>

export default {
    name: "Screenshots"
}

</script>
