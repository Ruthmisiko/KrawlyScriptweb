<script setup>

import { ref } from "vue";


function handleEmailSubmit() {
 
  const subject = encodeURIComponent(`New Inquiry from ${email.value}`);
  const body = encodeURIComponent(`Email: ${email.value}`);
  const mailtoLink = `mailto:Krawlyscriptagency@gmail.com?subject=${subject}&body=${body}`;

  // Redirect the user to their email client
  window.location.href = mailtoLink;
}


</script>

<template>
    <!-- Newsletter Section Start -->
    <div id="contactus" class="bg-theme-primary mt-10">
        <div class="container w-full lg:w-2/5 mx-auto px-5">
            <section class="py-16">
                <h4 class="text-sm tracking-widest uppercase text-center text-white font-theme-heading">1500+ Satisfied Clients</h4>
                <h2 class="text-3xl md:text-4xl font-medium text-center text-white mt-9 mb-10 font-theme-heading"> Follow us  and stay up-to-date with our latest projects, tips, and news. Never miss an update from KrawlyScript!</h2>

              
                    <div class="relative flex flex-col items-center lg:flex-row justify-center lg:space-x-3">
                        
                     
                    </div>
             
            </section>
        </div>
    </div>
    <!-- Newsletter Section End -->
</template>
