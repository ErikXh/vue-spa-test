<template>
 <!-- Team section -->
<section class="bg-gray-200 py-6 w-full" id="team">
  <div class="container mx-auto flex flex-col content-center py-10 w-11/12">
    <div class="container max-w-7xl mx-auto flex flex-col text-center w-1/3">
      <div class="py-3">
        <h1 class="font-light text-xl text-gray-600 uppercase">
           ostihr Team
        </h1>
        <p class="text-sm text-gray-500 font-light py-3">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
          Molestiae magni, quas facere nulla nemo aliquid possimus accusantium aperiam vitae quod necessitatibus ex amet.
        </p>
      </div>
    </div>
  </div>

  <div class="container max-w-7xl mx-auto flex flex-col justify-center items-center content-center md:flex-row md:flex-wrap md:items-center md:justify-around lg:content-center">
    <!-- first team member card-->
    <div class="py-4 flex flex items-center content-center justify-center">
        <div class="container w-9/12 md:w-2/3 flex flex-col bg-white">
          <div>
            <img src="./img/team_member.jpeg" alt="image of a team member" class="w-full object-cover">
          </div>
          <div class="text-center">
            <h1 class="text-l font-light text-gray-600 uppercase">
              Jemy secondce
            </h1>
            <p class="text-sm font-light text-gray-300 capitalize">
              co. founder
            </p>
          </div>
        </div>
    </div>

    <!-- second team member card-->
    <div class="py-4 flex items-center content-center justify-center">
      <div class="container w-9/12 md:w-2/3 flex flex-col bg-white">
        <div>
          <img src="./img/team_member.jpeg" alt="image of a team member" class="w-full object-cover">
        </div>
        <div class="text-center">
          <h1 class="text-l font-light text-gray-600 uppercase">
            deborah brown
          </h1>
          <p class="text-sm font-light text-gray-300 capitalize">
            <span class="uppercase">UX</span> designer
          </p>
        </div>
      </div>
    </div>

    <!-- third team member card-->
    <div class="py-4 flex items-center content-center justify-center">
      <div class="container w-9/12 md:w-2/3 flex flex-col bg-white">
        <div>
          <img src="./img/team_member.jpeg" alt="image of a team member" class="w-full object-cover">
        </div>
        <div class="text-center">
          <h1 class="text-l font-light text-gray-600 uppercase">
            harry banks
          </h1>
          <p class="text-sm font-light text-gray-300 capitalize">
            founder
          </p>
        </div>
      </div>
    </div>

    <!-- forth team member card-->
    <div class="py-4 flex items-center content-center justify-center">
      <div class="container w-9/12 md:w-2/3 flex flex-col bg-white">
        <div>
          <img src="./img/team_member.jpeg" alt="image of a team member" class="w-full object-cover">
        </div>
        <div class="text-center">
          <h1 class="text-l font-light text-gray-600 uppercase">
            victoria clark
          </h1>
          <p class="text-sm font-light text-gray-300 capitalize">
            creative director
          </p>
        </div>
      </div>
    </div>

  </div>
</section>
</template>


<script>

export default {
    name: "TeamSection"
}
</script>