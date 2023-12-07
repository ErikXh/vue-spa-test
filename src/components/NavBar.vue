<template> 
    <nav class="mx-auto p-6 w-full fixed drop-shadow-md z-10" id="nav">
    <div class="container mx-auto flex items-center justify-between md:px-10 lg:px-20">
        <div class="pt-2 ">
        <h1 class="text-3xl font-bold text-white">
            Appro
        </h1>
        </div>
        <!-- Menu Items -->
        <div class="hidden flex justify-end space-x-6 md:flex">
        <a href="#home" class="text-white font-light text-l hover:text-gray-600 capitalize">home </a>
        <a href="#work" class="text-white font-light text-l hover:text-gray-600 capitalize">work</a>
        <a href="#features" class="text-white font-light text-l hover:text-gray-600 capitalize">features</a>
        <a href="#team" class="text-white font-light text-l hover:text-gray-600 capitalize">team</a>
        <a href="#reviews" class="text-white font-light text-l hover:text-gray-600 capitalize">clients</a>
        <a href="#pricing" class="text-white font-light text-l hover:text-gray-600 capitalize">pricing</a>
        <a href="#blog" class="text-white font-light text-l hover:text-gray-600 capitalize">blog</a>
        <a href="#contact" class="text-white font-light text-l hover:text-gray-600 capitalize">contact</a>
        </div>

        <!-- Hamburger Icon -->
        <button id="menu-btn" class="block hamburger md:hidden focus:outline-none">
        <i class="ri-menu-line text-xl font-light text-white"></i>
        </button>
    </div>

    <!-- Mobile Menu -->
    <div class="md:hidden">
        <div id="side-menu" class="absolute flex flex-col items-center hidden self-end py-8 mt-10 space-y-6 font-bold bg-blue-400 sm:w-auto sm:self-center left-6 right-6 shadow-lg">
        <a href="#home" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">home </a>
        <a href="#work" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">work</a>
        <a href="#features" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">features</a>
        <a href="#team" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">team</a>
        <a href="#reviews" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">clients</a>
        <a href="#pricing" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">pricing</a>
        <a href="#blog" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">blog</a>
        <a href="#contact" class="text-white font-light text-l hover:text-gray-600 capitalize mini-nav-links-js">contact</a>
        </div>
    </div>
    </nav>
</template>

<script>
</script>