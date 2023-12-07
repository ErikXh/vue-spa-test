<template>
<!-- Home section -->
<section class=" w-full py-20" id="home">
  <div class="container max-w-7xl mx-auto md:flex md:content-center md:items-center py-6 w-10/12">
    <div class="md:w-full p-4 md:flex md:flex-col md:justify-start"> 
      <div class="p-1">
        <h1 class="text-base font-bold text-4xl text-white">
            It's all about <br>Promoting your Business
        </h1>
      </div>
      <div class="p-1">
        <p class="text-sm text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi quae rerum placeat facilis voluptatem dolor error quasi deserunt ratione fugiat, 
        quaerat minima totam distinctio inventore repudiandae ad aperiam doloribus recusandae tenetur delectus laborum. Fugit, illo?</p>
      </div>
       <button type="button" class=" flex py-5 hover:pointer w-32 justify-center content-center">
          <i class="ri-play-line font-light text-white blue-play-btn p-px"></i> <span class="p-1 text-white text-sm">Watch Video</span>
       </button>
    </div>
    <div class="container mx-auto grid content-center justify-center w-2/6 p-2">
     <img src="./img/vertical_phone.png" alt="image of a smartphone" class=" w-40">
    </div>
  </div>
</section>
<!-- End of Home section-->

</template>

<script>

export default {
    name: "HomeSection"
}
</script>