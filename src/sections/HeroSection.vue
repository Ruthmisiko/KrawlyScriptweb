<script setup></script>

<template>
    <!-- Hero Section Start -->
    <div class="container mx-auto px-5 overflow-x-hidden lg:overflow-x-visible">
        <section class="grid grid-cols-none lg:grid-cols-2 pb-16 pt-8 items-center">
            <div class="lg:w-5/6 order-2 lg:order-none">
                <h1 class="text-4xl xl:text-5xl font-bold font-theme-heading text-center lg:text-left">Welcome to KrawlyScript
                    Agency</h1>
                <p class="lg:text-xl mt-10 font-theme-content text-theme-grayish-blue text-center lg:text-left">We deliver high quality academic writing, including research papers, essays and reports,tailored to meet your specific needs. Additionally, we offer compelling copywriting and insightful articles that help elevate your brand and engage your audience effectively.</p>
                <div class="flex justify-center lg:justify-start mt-10">
                    <LinkButton btn-type="primary" link="#projects">View Our Work</LinkButton>
                    <LinkButton btn-type="muted" link="#contactus">Contact Us</LinkButton>
                </div>
            </div>
            <div class="relative order-1 lg:order-none mb-20 lg:mt-0 lg:mb-0 lg:-mr-10">
                <img class="z-10 w-full" src="/images/illustration-hero.svg" />
                <div class="-z-10 bg-theme-primary h-52 w-full sm:h-80 sm:w-full rounded-l-full absolute -right-28 md:-right-48 -bottom-8"></div>
            </div>
        </section>
    </div>
    <!-- Hero Section End -->
</template>
