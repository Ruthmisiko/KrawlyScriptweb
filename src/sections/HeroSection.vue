<script setup></script>

<template>
  <div class="bg-[#0b1f1a] text-white min-h-screen">
    
    <!-- Hero Section -->
    <section id="home" class="container mx-auto px-6 py-20 grid lg:grid-cols-2 gap-12 items-center">
      <div>
        <h1 class="text-4xl xl:text-5xl font-bold mb-6">
          Krawly Script Agency
        </h1>
        <p class="text-lg text-green-200 leading-relaxed">
          Krawly Script Agency is a professional mechanical engineering firm delivering innovative design, industrial maintenance, 
          and technical solutions for modern engineering challenges. We help organizations improve reliability, performance, 
          and operational efficiency.
        </p>
        <div class="mt-8 flex gap-4">
          <a href="#projects" class="px-6 py-3 bg-green-700 hover:bg-green-600 rounded-md font-semibold">
            View Projects
          </a>
          <a href="#contact" class="px-6 py-3 border border-green-600 hover:bg-green-900 rounded-md font-semibold">
            Contact Us
          </a>
        </div>
      </div>
      <img src="/images/engineering.jpg" class="rounded-xl shadow-lg object-cover w-full h-[350px]" />
    </section>

    <!-- About -->
    <section id="about" class="bg-[#0f2b24] py-20">
      <div class="container mx-auto px-6 grid lg:grid-cols-2 gap-12 items-center">
        <img src="/images/engineering2.jpg" class="rounded-xl shadow-lg object-cover w-full h-[320px]" />
        <div>
          <h2 class="text-3xl font-bold mb-4">About Krawly Script Agency</h2>
          <p class="text-green-200 leading-relaxed">
            We specialize in mechanical system design, preventive maintenance planning, equipment diagnostics, 
            and industrial engineering support. Our team combines engineering expertise with real-world experience 
            to deliver sustainable, cost-effective solutions.
          </p>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section id="services" class="container mx-auto px-6 py-20">
      <h2 class="text-3xl font-bold text-center mb-12">Our Services</h2>
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="bg-[#0f2b24] p-6 rounded-lg border border-green-800">
          <h3 class="text-xl font-semibold mb-2">Mechanical Design</h3>
          <p class="text-green-200">Professional CAD-based design for mechanical components and systems.</p>
        </div>
        <div class="bg-[#0f2b24] p-6 rounded-lg border border-green-800">
          <h3 class="text-xl font-semibold mb-2">Industrial Maintenance</h3>
          <p class="text-green-200">Preventive and corrective maintenance to minimize downtime.</p>
        </div>
        <div class="bg-[#0f2b24] p-6 rounded-lg border border-green-800">
          <h3 class="text-xl font-semibold mb-2">System Optimization</h3>
          <p class="text-green-200">Improving efficiency, safety, and performance of mechanical systems.</p>
        </div>
        <div class="bg-[#0f2b24] p-6 rounded-lg border border-green-800">
          <h3 class="text-xl font-semibold mb-2">Technical Consulting</h3>
          <p class="text-green-200">Engineering assessments, reports, and professional guidance.</p>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="bg-[#0f2b24] py-20">
      <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold text-center mb-12">Featured Projects</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <img src="/images/engineering3.jpg" class="rounded-lg h-60 w-full object-cover" />
          <img src="/images/engineering5.jpg" class="rounded-lg h-60 w-full object-cover" />
          <img src="/images/engineering2.jpg" class="rounded-lg h-60 w-full object-cover" />
        </div>
      </div>
    </section>

    <!-- Why Choose Us -->
    <section id="contact" class="container mx-auto px-6 py-20">
      <h2 class="text-3xl font-bold text-center mb-12">Why Choose Us</h2>
      <div class="grid md:grid-cols-3 gap-8 text-center">
        <div class="p-6 border border-green-800 rounded-lg bg-[#0f2b24]">
          <h3 class="text-xl font-semibold mb-2">Professional Standards</h3>
          <p class="text-green-200">We follow engineering best practices and industry standards.</p>
        </div>
        <div class="p-6 border border-green-800 rounded-lg bg-[#0f2b24]">
          <h3 class="text-xl font-semibold mb-2">Reliable Delivery</h3>
          <p class="text-green-200">On-time project delivery with clear documentation.</p>
        </div>
        <div class="p-6 border border-green-800 rounded-lg bg-[#0f2b24]">
          <h3 class="text-xl font-semibold mb-2">Client-Focused</h3>
          <p class="text-green-200">We tailor solutions to each client’s technical needs.</p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="bg-[#071512] py-20">
      <div class="container mx-auto px-6 text-center max-w-2xl">
        <h2 class="text-3xl font-bold mb-4">Contact Krawly Script Agency</h2>
        <p class="text-green-200 mb-8">
          Let’s discuss how we can support your mechanical engineering project.
        </p>
        <form class="grid gap-4">
          <input type="text" placeholder="Full Name" class="p-3 rounded bg-[#0f2b24] border border-green-800 text-white" />
          <input type="email" placeholder="Email Address" class="p-3 rounded bg-[#0f2b24] border border-green-800 text-white" />
          <textarea rows="4" placeholder="Project Details" class="p-3 rounded bg-[#0f2b24] border border-green-800 text-white"></textarea>
          <button class="bg-green-700 hover:bg-green-600 py-3 rounded font-semibold">
            Send Message
          </button>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-6 text-center text-green-400">
      © 2026 Krawly Script Agency — Mechanical Engineering Solutions
    </footer>

  </div>
</template>
