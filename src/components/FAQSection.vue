<template>

<!-- FAQ section-->
<section class="bg-white w-full py-6" id="faq">

<div class="grid justify-center content-center">
  <div class="container mx-auto flex flex-col text-center w-3/6">
   <div class="py-3">
     <h1 class="font-bold text-xl text-black uppercase">
        frequently asked questions
     </h1>
     <p class="text-sm text-black font-light py-3">
       Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
       Molestiae magni, quas facere nulla nemo aliquid possimus accusantium aperiam vitae quod necessitatibus ex amet.
     </p>
   </div>
  </div>
</div>

<div id="faq_container" class="container mx-auto max-w-6 flex flex-col justify-center md:flex-row md:justify-around items-center">

  <div class="container mx-auto w-9/12 md:w-4/6 py-4">
    <!-- first FAQ -->
    <div class="p-2 faq-tab shadow-lg w-full">
      <div class="flex justify-between items-center p-4">
        <h1 class="font-semibold text-l text-black">
          Lorem ipsum dolor sit amet consectetur?
        </h1>
        <div id="faq-arrow">
          <i class="ri-arrow-up-s-line font-light text-l"></i>
        </div>
      </div>
      <div class="p-4 hidden" id="hide-p">
        <p class="text-gray-500 text-sm">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          Reprehenderit sed ab illum distinctio sint voluptatum eaque quo laborum,
          dolorum error amet suscipit consequatur provident ut.
        </p>
      </div>
    </div>
    <!-- second FAQ -->
    <div class="p-2 faq-tab shadow-lg w-full">
      <div class="flex justify-between p-4">
        <h1 class="font-semibold text-l text-black">
          Lorem ipsum dolor sit amet consectetur?
        </h1>
        <div id="faq-arrow-2">
          <i class="ri-arrow-up-s-line font-light text-l" ></i>
        </div>
      </div>
      <div class="p-4 hidden" id="hide-p2">
        <p class="text-gray-500 text-sm">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          Reprehenderit sed ab illum distinctio sint voluptatum eaque quo laborum,
          dolorum error amet suscipit consequatur provident ut.
        </p>
      </div>
    </div>
    <!-- third FAQ -->
    <div class="p-2 faq-tab shadow-lg w-full">
      <div class="flex justify-between p-4">
        <h1 class="font-semibold text-l text-black">
          Lorem ipsum dolor sit amet consectetur?
        </h1>
        <div id="faq-arrow-3">
          <i class="ri-arrow-up-s-line font-light text-l" ></i>
        </div>
      </div>
      <div class="p-4 hidden" id="hide-p3">
        <p class="text-gray-500 text-sm" >
          Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          Reprehenderit sed ab illum distinctio sint voluptatum eaque quo laborum,
          dolorum error amet suscipit consequatur provident ut.
        </p>
      </div>
    </div>
    <!-- forth FAQ -->
    <div class="p-2 faq-tab shadow-lg w-full">
      <div class="flex justify-between p-4">
        <h1 class="font-semibold text-l text-black">
          Lorem ipsum dolor sit amet consectetur?
        </h1>
        <div id="faq-arrow-4">
          <i class="ri-arrow-up-s-line font-light text-l" ></i>
        </div>
      </div>
      <div class="p-4 hidden" id="hide-p4">
        <p class="text-gray-500 text-sm" >
          Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          Reprehenderit sed ab illum distinctio sint voluptatum eaque quo laborum,
          dolorum error amet suscipit consequatur provident ut.
        </p>
      </div>
    </div>

  </div>

  <div class="container mx-auto flex items-center justify-center w-3/6 md:w-1/6 py-4">
      <img src="./img/vertical_phone.png" alt="" class="w-10/12 object-contain">
  </div>

</div>

</section>

</template>

<script>
export default {

    name: "FAQSection"
}

</script>