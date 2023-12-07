<template>
    <!-- Download app section-->
<section class="bg-blue-400 w-full  p-6" id="download">

<div class="grid justify-center content-center">
  <div class="container mx-auto flex flex-col text-center w-3/6">
   <div class="py-3">
     <h1 class="font-bold text-xl text-white uppercase">
        Download Appro today
     </h1>
     <p class="text-sm text-white font-light py-3">
       Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
       Molestiae magni, quas facere nulla nemo aliquid possimus accusantium aperiam vitae quod necessitatibus ex amet.
     </p>
   </div>
  </div>
</div>

<div class="mx-auto max-w-7xl flex flex-col justify-center items-center md:flex-row md:justify-around w-10/12">

  <!-- first dowload btn -->
  <div class="flex flex-1 flex-col p-4 w-2/12 text-center items-center">
   <button class="download-btn px-2 p2-3">
    <div class="flex justify-between">
      <div class="flex items-center px-2">
        <i class="ri-android-line text-sm text-white"></i>
      </div>
      <div class="text-center">
        <div class="font-light text-sm text-white">available on</div>
        <div class="font-bold text-sm text-white capitalize"> play store</div>
      </div>
    </div>
   </button>
  </div>
  <!-- second dowload btn -->
  <div class="flex flex-1 flex-col p-4 w-2/12 text-center items-center">
        <button class="download-btn px-2 p2-3">
         <div class="flex justify-between">
           <div class="flex items-center px-2">
             <i class="ri-apple-fill text-sm text-white"></i>
           </div>
           <div class="text-center">
             <div class="font-light text-sm text-white">available on</div>
             <div class="font-bold text-sm text-white capitalize"> app store</div>
           </div>
         </div>
        </button>
  </div>
  <!-- third dowload btn -->
  <div class="flex flex-1 flex-col p-4 w-2/12 text-center items-center">
    <button class="download-btn px-2 p2-3">
     <div class="flex justify-between">
       <div class="flex items-center px-2">
         <i class="ri-microsoft-fill text-sm text-white"></i>
       </div>
       <div class="text-center">
         <div class="font-light text-sm text-white">available on</div>
         <div class="font-bold text-sm text-white capitalize"> windows store</div>
       </div>
     </div>
    </button>
  </div>
</div>
</section>
</template>

<script>

export default {
    name: "DownloadSection"
}

</script>