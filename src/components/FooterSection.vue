<template>
    <footer class="bg-indigo-900 w-full" id="contact">
  <div class="g-map">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5339.801352215102!2d19.81937083590852!3d41.31671919345483!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x135031d53942bf4b%3A0xc29b959022f4c53!2sAir%20Albania%20Stadium!5e0!3m2!1sen!2s!4v1688833301569!5m2!1sen!2s" width="100%" height="350px" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>
  <section class="container mx-auto max-w-10/12">
   <div class="container flex flex-col content-center justify-center items-center md:relative md:bottom-20 md:flex md:flex-row md:items-center md:justify-around">
    <div class="py-4 w-9/12 md:w-5/12 md:py-0 flex justify-center">
      <div class="shadow-lg bg-white w-full p-6 py-4" id="form">
      <!--contact form-->
      <form action="#" method="post" id="contact_form">
        <div class="w-full flex flex-col items-center justify-between md:flex-row py-2">
          <div class="py-2 w-full">
            <label for="name">
              <input type="text" name="name" id="name" placeholder="name" class="p-2 w-full shadow-lg">
            </label>
          </div>

          <div class="py-2 w-full">
            <label for="email">
              <input type="email" name="email" id="email" placeholder="email" class="p-2 w-full shadow-lg">
            </label>
          </div>

        </div>
        <div class="py-2">
          <label for="subject">
            <input type="text" name="subject" id="subject" placeholder="subject" class="p-2 shadow-lg w-full">
          </label>
        </div>

        <div class="py-2">
          <label for="textarea">
            <textarea name="txtarea" id="txtarea" cols="15" rows="5" placeholder="Message" class="p-2 shadow-lg w-full" ></textarea>
          </label>
        </div>

        <div class="py-2">
          <button type="submit" class="form-btn">Send Mesasge</button>
        </div>
      </form>
      </div>
    </div>


    <!--contact-->
    <div class="w-9/12 md:w-5/12 bg-white p-6 py-4">
      <h1 class="text-gray-500 capitalize font-bold text-xl py-2">
        address
      </h1>
      <p class="text-gray-400 text-sm font-light py-2">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. 
        Laudantium nesciunt, sapiente nulla, distinctio sunt eos adipisci 
        dolor laboriosam blanditiis minus quas necessitatibus iste, est eveniet.
      </p>

      <div class="py-2 flex flex-col">

        <div class="py-1 flex justify-even items-center">
          <div class="green-circle">
            <i class="ri-customer-service-line text-green-300 font-bold"></i>
          </div>
          <a href="tel:+44545989626" class="text-gray-400 text-sm font-light">+44545989626</a>
        </div>

        <div class="py-1 flex items-center">
          <div class="green-circle">
            <i class="ri-mail-line text-green-300 font-bold"></i>
          </div>
          <a href="mailto:marveltheme@gmail.com" class="text-gray-400 text-sm font-light">marveltheme@gmail.com</a>
        </div>

        <div class="py-1 flex items-center">
          <div class="green-circle">
            <i class="ri-map-pin-line text-green-300 font-bold"></i>
          </div>
          <a href="#address" class="text-gray-400 text-sm font-light"> 28 Green Tower, Street Name New York City, USA</a>
        </div>
      </div>
    </div>
   </div>

   <div class="p-3 flex flex-col items-center content-center">
     <!-- newsletter subscription-->

    <div class="py-2 w-4/6 md:w-2/6">
      <h2 class="text-white font-semibold text-l uppercase text-center py-3">
        subscribe to our newsletter
      </h2>
      <div class="newsltr">
        <input type="email" name="news-email" id="newsletter" class="rounded-sm" placeholder="Your email address here ...">
        <button class="sub-btn capitalize">subscribe</button>    
      </div>
      
    </div>
       <div class="py-3 flex flex-col w-4/6 md:w-2/6 justify-center">

        <div class="p-2 w-full flex justify-center content-center items-center">
          
          <div class="flex w-full justify-around">
            <div class="rounded-full w-10 h-10 flex items-center text-center justify-center bg-white p-3">
            <i class="ri-facebook-fill text-green-300 font-light "></i>
          </div>
          <div class="rounded-full w-10 h-10 flex items-center text-center justify-center bg-white p-3">
            <i class="ri-twitter-fill text-green-300 font-light "></i>
          </div>
          <div class="rounded-full w-10 h-10 flex items-center text-center justify-center bg-white p-3">
            <i class="ri-linkedin-fill text-green-300 font-light "></i>
          </div>
          <div class="rounded-full w-10 h-10 flex items-center text-center justify-center bg-white p-3">
            <i class="ri-pinterest-fill text-green-300 font-light "></i>
          </div>
          </div>
          

        </div>

        <div class="py-3 text-center">
          <h4 class="text-sm text-white">
            &#169; 2017 Erik all rights reserved.
          </h4>
        </div>
          
       </div>
   </div>
  </section>
</footer>
</template>

<script>

export default {

  name: "FooterSection"
}

</script>