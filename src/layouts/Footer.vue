<script setup></script>

<template>
    <!-- Footer Start -->
    <footer class="bg-theme-dark-blue py-10">
        <div class="container mx-auto px-5">
            <div class="grid md:grid-cols-2">
                <div class="flex flex-col md:flex-row md:space-x-12 items-center">
                    <div class="mb-10 md:mb-0">
                        
                    </div>
                    <ul class="flex flex-col md:flex-row space-y-5 md:space-y-0 md:space-x-8 text-xs text-center md:text-left font-theme-heading">
                        <li class="uppercase text-white hover:text-theme-secondary transition duration-200">
                            <a href="#about" v-smooth-scroll>About</a>
                        </li>
                        <li class="uppercase text-white hover:text-theme-secondary transition duration-200">
                            <a href="#services" v-smooth-scroll>Services</a>
                        </li>
                        <li class="uppercase text-white hover:text-theme-secondary transition duration-200">
                            <a href="#projects" v-smooth-scroll>Projects</a>
                        </li>
                    </ul>
                </div>
                <div class="md:place-self-end place-self-center mt-10 md:mt-0">
                    <ul class="flex space-x-8 items-center">
                         <li>
              <a
                href="https://facebook.com"
                target="_blank"
                rel="noopener noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="26"
                  height="26"
                  fill="currentColor"
                  class="bi bi-facebook text-white hover:text-theme-secondary transition duration-200 cursor-pointer"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"
                  />
                </svg>
              </a>
            </li>
            <!-- Twitter -->
            <li>
              <a
                href="https://x.com/krawlyscript?t=NWoEfyQT-BcUwzZOyxpYyg&s=09"
                target="_blank"
                rel="noopener noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="26"
                  height="26"
                  fill="currentColor"
                  class="bi bi-twitter text-white hover:text-theme-secondary transition duration-200 cursor-pointer"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382 3.323 3.323 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"
                  />
                </svg>
              </a>
            </li>
            <!-- Instagram -->
            <li>
              <a
                href="https://www.instagram.com/krawlyscript_agency?igsh=OTU0MzhnZTVvaWo2"
                target="_blank"
                rel="noopener noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="26"
                  height="26"
                  fill="currentColor"
                  class="bi bi-instagram text-white hover:text-theme-secondary transition duration-200 cursor-pointer"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M8 0c2.137 0 2.404.008 3.25.047.847.04 1.418.176 1.951.37a3.928 3.928 0 0 1 1.435.938 3.928 3.928 0 0 1 .938 1.435c.194.533.33 1.104.37 1.951.039.846.047 1.113.047 3.25s-.008 2.404-.047 3.25c-.04.847-.176 1.418-.37 1.951a3.928 3.928 0 0 1-.938 1.435 3.928 3.928 0 0 1-1.435.938c-.533.194-1.104.33-1.951.37-.846.039-1.113.047-3.25.047s-2.404-.008-3.25-.047c-.847-.04-1.418-.176-1.951-.37a3.928 3.928 0 0 1-1.435-.938 3.928 3.928 0 0 1-.938-1.435c-.194-.533-.33-1.104-.37-1.951C.008 10.404 0 10.137 0 8s.008-2.404.047-3.25c.04-.847.176-1.418.37-1.951A3.928 3.928 0 0 1 1.355.364 3.928 3.928 0 0 1 2.79-.574c.533-.194 1.104-.33 1.951-.37C5.596.008 5.863 0 8 0zm0 1.446c-2.12 0-2.367.007-3.197.046-.77.035-1.185.166-1.462.277-.367.142-.63.311-.907.588-.277.277-.446.54-.588.907-.111.277-.242.692-.277 1.462-.039.83-.046 1.076-.046 3.197s.007 2.367.046 3.197c.035.77.166 1.185.277 1.462.142.367.311.63.588.907.277.277.54.446.907.588.277.111.692.242 1.462.277.83.039 1.076.046 3.197.046s2.367-.007 3.197-.046c.77-.035 1.185-.166 1.462-.277.367-.142.63-.311.907-.588.277-.277.446-.54.588-.907.111-.277.242-.692.277-1.462.039-.83.046-1.076.046-3.197s-.007-2.367-.046-3.197c-.035-.77-.166-1.185-.277-1.462a2.42 2.42 0 0 0-.588-.907 2.42 2.42 0 0 0-.907-.588c-.277-.111-.692-.242-1.462-.277C10.367 1.453 10.12 1.446 8 1.446zM8 3.89a4.11 4.11 0 1 0 0 8.22 4.11 4.11 0 0 0 0-8.22zm0 6.774a2.663 2.663 0 1 1 0-5.326 2.663 2.663 0 0 1 0 5.326zm5.2-6.845a.96.96 0 1 1-1.92 0 .96.96 0 0 1 1.92 0z"
                  />
                </svg>
              </a>
            </li>
            <!-- WhatsApp -->
            <li>
              <a
                href="https://wa.me/+254713147072"
                target="_blank"
                rel="noopener noreferrer"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="26"
                  height="26"
                  fill="currentColor"
                  class="bi bi-whatsapp text-white hover:text-theme-secondary transition duration-200 cursor-pointer"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M13.601 2.326a7.83 7.83 0 0 0-5.539-2.326h-.001c-4.336 0-7.866 3.53-7.866 7.865 0 1.386.367 2.737 1.063 3.93l-1.108 4.057 4.162-1.094a7.844 7.844 0 0 0 3.749.957h.001c4.336 0 7.866-3.53 7.866-7.865a7.82 7.82 0 0 0-2.327-5.524Zm-5.539 12.37a6.66 6.66 0 0 1-3.394-.93l-.24-.143-2.469.65.65-2.403-.156-.247a6.666 6.666 0 1 1 5.61 3.073ZM10.7 10.11c-.225-.112-1.328-.657-1.535-.733-.207-.076-.358-.112-.51.113-.15.224-.585.733-.717.88-.132.15-.263.169-.488.056-.225-.113-.95-.348-1.81-1.108-.67-.598-1.122-1.34-1.253-1.566-.132-.224-.014-.345.099-.457.102-.101.225-.263.337-.394.113-.132.15-.225.225-.375.075-.15.037-.281-.018-.394-.056-.112-.51-1.234-.698-1.69-.184-.448-.371-.387-.51-.387-.132 0-.263-.008-.394-.008a.764.764 0 0 0-.56.262c-.19.224-.747.73-.747 1.77s.765 2.053.87 2.195c.105.15 1.507 2.3 3.66 3.224.512.221.91.354 1.22.453.512.162.98.14 1.35.084.412-.061 1.328-.545 1.52-1.07.188-.525.188-.976.131-1.07-.056-.094-.203-.15-.43-.263Z"
                  />
                </svg>
              </a>
            </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
    <!-- Footer End -->
</template>
