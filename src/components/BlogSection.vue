<template>
    <!-- blog section -->
<section class="bg-white w-full py-6" id="blog">

<div class="grid justify-center content-center">
  <div class="container mx-auto flex flex-col text-center w-3/6">
   <div class="py-3">
     <h1 class="font-bold text-xl text-gray-600 uppercase">
        latest from our blog
     </h1>
     <p class="text-sm text-gray-600 font-light py-3">
       Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
       Molestiae magni, quas facere nulla nemo aliquid possimus accusantium aperiam vitae quod necessitatibus ex amet.
     </p>
   </div>
  </div>
</div>

<div class="mx-auto max-w-7xl flex flex-col justify-center items-center md:flex-row md:justify-around w-10/12">

  <!-- First blog item-->
  <div class="px-2 py-2 md:w-4/6 w-10/12 max-w-6">
  <div class="container mx-auto shadow-lg">
      <div>
        <img src="./img/blog_image.jpeg" alt="image for the blog" class="w-full object-cover">
      </div>

      <div class="flex justify-center items-center py-1">
        <div class="p-2 flex justify-center">
          <i class="ri-user-3-line text-gray-500 text-md"></i>
          <h3 class="text-gray-500 text-md capitalize">
          by: Admin
          </h3>
        </div>
        <div class="p-2">
          <i class="ri-calendar-line text-gray-500 text-md"></i>
          <time datetime="2017-02-01" class="text-gray-500 text-md">Feb 01, 2017</time>
        </div>
      </div>

      <div class="py-2 text-center px-3">
        <h2 class="color-gray-600 font-bold text-2xl capitalize py-4">
          beautiful place for your great journy
        </h2>
        <p class="text-gray-500">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
          Cum accusantium natus, ratione tempore aliquam illo?
        </p>
      </div>
      <div class="py-4 flex w-full justify-center">
        <button class="price-button">
          read more
        </button>
      </div>
  </div>
  </div>
  
  <!-- second blog item-->
  <div class="px-2 py-2 md:w-4/6 w-10/12 max-w-6">
  <div class="container mx-auto shadow-lg">
        <div>
          <img src="./img/blog_image.jpeg" alt="image for the blog" class="w-full object-cover">
        </div>
    
        <div class="flex justify-center items-center py-1">
          <div class="p-2 flex justify-center">
            <i class="ri-user-3-line text-gray-500 text-md"></i>
            <h3 class="text-gray-500 text-md capitalize">
            by: Admin
            </h3>
          </div>
          <div class="p-2">
            <i class="ri-calendar-line text-gray-500 text-md"></i>
            <time datetime="2017-02-01" class="text-gray-500 text-md">Feb 01, 2017</time>
          </div>
        </div>
    
        <div class="py-2 text-center px-3">
          <h2 class="color-gray-600 font-bold text-2xl capitalize py-4">
            beautiful place for your great journy
          </h2>
          <p class="text-gray-500">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
            Cum accusantium natus, ratione tempore aliquam illo?
          </p>
        </div>
        <div class="py-4 flex w-full justify-center">
          <button class="price-button">
            read more
          </button>
        </div>
  </div>
  </div>
  
  <!-- third blog item-->
  <div class="px-2 py-2 md:w-4/6 w-10/12 max-w-6">
   <div class="container mx-auto shadow-lg">
    <div>
     <img src="./img/blog_image.jpeg" alt="image for the blog" class="w-full object-cover">
    </div>

    <div class="flex justify-center items-center py-1">
     <div class="p-2 flex justify-center">
       <i class="ri-user-3-line text-gray-500 text-md"></i>
       <h3 class="text-gray-500 text-md capitalize">
        by: Admin
       </h3>
     </div>
     <div class="p-2">
       <i class="ri-calendar-line text-gray-500 text-md"></i>
       <time datetime="2017-02-01" class="text-gray-500 text-md">Feb 01, 2017</time>
     </div>
    </div>

    <div class="py-2 text-center px-3">
     <h2 class="color-gray-600 font-bold text-2xl capitalize py-4">
       beautiful place for your great journy
     </h2>
     <p class="text-gray-500">
       Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
       Cum accusantium natus, ratione tempore aliquam illo?
     </p>
    </div>
    <div class="py-4 flex w-full justify-center">
     <button class="price-button">
       read more
     </button>
    </div>
  </div> 
  </div>

</div>
</section>
</template>

<script>

export default {

    name: "BlogSection"
}

</script>