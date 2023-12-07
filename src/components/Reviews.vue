<template>
<!-- Reviews section / "Clients" -->
<section class="bg-white py-6 w-full" id="reviews">
   <div class="container mx-auto grid content-center max-w-6/12">
    <!-- review container-->
    <div class="container mx-auto w-8/12 flex flex-col justify-center content-center text-center border-gray-100 shadow-lg p-6">
      <h1 class="text-gray-600 font-semibold text-l uppercase py-3" id="name-js">
      </h1>
      <h3 class="text-gray-400 font-light text-sm capitalize py-2" id="position-js"> 
      </h3>
        <blockquote class="text-gray-400 font-light text-xsm" id="quote-js">
        </blockquote>
    </div>
    <!-- profile -->
      <div class="container flex mx-auto w-8/12 py-6 items-center justify-between">
        <div class="px-2" id="quote_arrow_left-js">
          <i class="ri-arrow-left-s-line text-l text-black font-bold right-click-js"></i>
        </div>
        <div class="px-2">
          <img src="./img/avatar.png" alt="avatar image of a person" class="w-full shadow-lg object-cover border-circle opacity-25">
        </div>
        <div class="px-2">
          <img src="./img/avatar.png" alt="avatar image of a person" class="w-full shadow-lg object-cover border-circle">
        </div>
        <div class="px-2">
          <img src="./img/avatar.png" alt="avatar image of a person" class="w-full shadow-lg object-cover border-circle opacity-25">
        </div>
        <div class="px-2" id="quote_arrow_right-js"> 
          <i class="ri-arrow-right-s-line text-l text-black font-bold"></i>
        </div>
      </div>
   </div>
</section>
</template>

<script>

export default {
    name: "ReviewsSection"
}
</script>