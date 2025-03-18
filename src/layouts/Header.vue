<script setup>
    import { ref } from 'vue';

    let mobileNav = ref(false);

    let toggleMobileNav = () => {
        mobileNav.value = !mobileNav.value
    }
</script>

<template>
    <!-- Navbar Start -->
    <div class="container mx-auto px-5">
        <header class="flex justify-between py-12 items-center">
            <div>
                <h1 style="color:darkblue;"><b>KrawlyScript</b></h1>
            </div>
            
            <nav class="flex justify-end flex-col md:flex-row">
                <!-- Menu Toggler -->
                <button @click="toggleMobileNav()" type="button" class="flex md:hidden focus:outline-none">
                    <svg viewBox="0 0 24 24" class="h-6 w-6 fill-current">
                        <path fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
                    </svg>
                </button>

                <!-- Desktop Menu -->
                <ul class="space-x-10 font-theme-heading font-medium items-center hidden md:flex  flex-col space-y-7 md:space-y-0 md:flex-row">
                    <li class="uppercase hover:text-theme-secondary transition duration-200"><a href="#home" v-smooth-scroll>Home</a></li>
                    <li class="uppercase hover:text-theme-secondary transition duration-200"><a href="#about" v-smooth-scroll>About</a></li>
                    <li class="uppercase hover:text-theme-secondary transition duration-200"><a href="#services" v-smooth-scroll>Services</a></li>
                    <li class="uppercase hover:text-theme-secondary transition duration-200"><a href="#contactus" v-smooth-scroll>Contact Us</a></li>
                    <li class="uppercase hover:text-theme-secondary transition duration-200"><a href="#projects" v-smooth-scroll>Projects</a></li>
                    <!-- <li class="uppercase bg-theme-secondary px-6 py-2 text-white rounded shadow-md hover:bg-white border-2 border-transparent hover:border-theme-secondary hover:text-theme-secondary cursor-pointer transition duration-200">
                        <a href="#download-section" v-smooth-scroll>Download</a>
                    </li> -->
                </ul>
            </nav>
        </header>

        <!-- Mobile Menu Start-->
        <div v-show="mobileNav">
            <div class="absolute px-5 py-12 block z-30 top-0 left-0 w-full h-full bg-gradient-to-b from-theme-dark-blue via-theme-dark-blue-tp to-theme-dark-blue">
                <div class="flex justify-between items-center">
                    <h1 style="color:white;"><b>KrawlyScript</b></h1>
                    <button @click="toggleMobileNav()" type="button" class="focus:outline-none">
                        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-x text-white" viewBox="0 0 16 16">
                            <path d="M4.646 4.646a.5.5 0 0 1 .708 0L8 7.293l2.646-2.647a.5.5 0 0 1 .708.708L8.707 8l2.647 2.646a.5.5 0 0 1-.708.708L8 8.707l-2.646 2.647a.5.5 0 0 1-.708-.708L7.293 8 4.646 5.354a.5.5 0 0 1 0-.708z"/>
                        </svg>
                    </button>
                </div>
                <ul class="uppercase text-white text-md tracking-widest items-center flex flex-col mt-14">
                    <li class="hover:text-theme-secondary transition duration-200 py-4 border-t border-b border-theme-grayish-blue w-full text-center">
                        <a  @click="toggleMobileNav()" href="#home">Home</a>
                    </li>
                    <li class="hover:text-theme-secondary transition duration-200 py-4 border-b border-theme-grayish-blue w-full text-center">
                        <a  @click="toggleMobileNav()" href="#about">About</a>
                    </li>
                    <li class="hover:text-theme-secondary transition duration-200 py-4 border-b border-theme-grayish-blue w-full text-center">
                        <a  @click="toggleMobileNav()" href="#services">Services</a>
                    </li>
                    <li class="hover:text-theme-secondary transition duration-200 py-4 border-b border-theme-grayish-blue w-full text-center">
                        <a  @click="toggleMobileNav()" href="#contactus">Contact Us</a>
                    </li>
                    <li class="hover:text-theme-secondary transition duration-200 py-4 border-b border-theme-grayish-blue w-full text-center">
                        <a  @click="toggleMobileNav()" href="#projects">Projects</a>
                    </li>
                 
                </ul>
               
            </div>
        </div>
        <!-- Mobile Menu End-->
    </div>
    <!-- Navbar End -->
</template>