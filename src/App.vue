<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
// import HelloWorld from './components/HelloWorld.vue'
import FooterComponent from "./components/Footer.component.vue";
import NavbarComponentVue from "./components/Navbar.component.vue";
import SliderComponentVue from "./components/Slider.component.vue";
</script>

<template>
  <NavbarComponentVue />
  <!-- Video Background -->
  <div
    class="video-docker absolute top-0 left-0 w-full h-full2 overflow-hidden mt-16"
  >
    <video
      autoplay
      loop
      muted
      class="min-w-full min-h-full absolute object-cover blur-sm"
    >
      <source src="./assets/videos/video-1.mp4" type="video/mp4" />
    </video>
  </div>
  <!-- End Video Background -->
  <br />
  <br />
  <br />
  <div class="mx-auto max-w-5xl relative z-30">
    <!-- Texto descriptivo -->
    <div class="mb-8">
      <div role="status" class="my-7 bg-purple-300 bg-opacity-50 rounded-xl">
        <h1 class="text-5xl text-white text-center">
          Hello I'm Joshua Morin and actually a ERP developer and web developer
        </h1>
      </div>
      <div role="status" class="mb-7 max-w-5xl animate-pulse">
        <div
          class="flex justify-center items-center w-full h-48 bg-gray-300 rounded dark:bg-gray-700"
        >
          <svg
            class="w-12 h-12 text-gray-200"
            xmlns="http://www.w3.org/2000/svg"
            aria-hidden="true"
            fill="currentColor"
            viewBox="0 0 640 512"
          >
            <path
              d="M480 80C480 35.82 515.8 0 560 0C604.2 0 640 35.82 640 80C640 124.2 604.2 160 560 160C515.8 160 480 124.2 480 80zM0 456.1C0 445.6 2.964 435.3 8.551 426.4L225.3 81.01C231.9 70.42 243.5 64 256 64C268.5 64 280.1 70.42 286.8 81.01L412.7 281.7L460.9 202.7C464.1 196.1 472.2 192 480 192C487.8 192 495 196.1 499.1 202.7L631.1 419.1C636.9 428.6 640 439.7 640 450.9C640 484.6 612.6 512 578.9 512H55.91C25.03 512 .0006 486.1 .0006 456.1L0 456.1z"
            ></path>
          </svg>
        </div>
        <span class="sr-only">Loading...</span>
      </div>
      <!-- <div role="status" class="my-6 animate-pulse">
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[450px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[500px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[450px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[380px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px]"
        ></div>
        <span class="sr-only">Loading...</span>
      </div>
      <div role="status" class="my-6 animate-pulse">
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[450px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[500px] mb-2.5"
        ></div>
        <span class="sr-only">Loading...</span>
      </div>
      <div role="status" class="mt-7 mb-6 animate-pulse">
        <div
          class="h-2.5 bg-gray-300 rounded-full dark:bg-gray-700 w-48 mb-4"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[450px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[500px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[450px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[380px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[500px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px]"
        ></div>
        <span class="sr-only">Loading...</span>
      </div>
      <div role="status" class="my-6 animate-pulse">
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[460px] mb-2.5"
        ></div>
        <div
          class="h-2 bg-gray-200 rounded-full dark:bg-gray-700 max-w-[450px] mb-2.5"
        ></div>
        <span class="sr-only">Loading...</span>
      </div> -->
    </div>
    <!-- End Texto descriptivo -->
    <!-- Slider -->
    <div class="mb-8">
      <SliderComponentVue />
    </div>
    <!-- End Slider -->
    <!-- Works and services -->
    <div
      class="w-full bg-white rounded-lg border shadow-md dark:bg-gray-800 dark:border-gray-700 mb-8"
    >
      <div class="sm:hidden">
        <label for="tabs" class="sr-only">Select tab</label>
        <select
          id="tabs"
          class="bg-gray-50 border-0 border-b border-gray-200 text-gray-900 sm:text-sm rounded-t-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
        >
          <option>Statistics</option>
          <option>Services</option>
          <option>FAQ</option>
        </select>
      </div>
      <ul
        class="hidden text-sm font-medium text-center text-gray-500 rounded-lg divide-x divide-gray-200 sm:flex dark:divide-gray-600 dark:text-gray-400"
        id="fullWidthTab"
        data-tabs-toggle="#fullWidthTabContent"
        role="tablist"
      >
        <li class="w-full">
          <button
            id="stats-tab"
            data-tabs-target="#stats"
            type="button"
            role="tab"
            aria-controls="stats"
            aria-selected="true"
            class="inline-block p-4 w-full bg-gray-50 rounded-tl-lg hover:bg-gray-100 focus:outline-none dark:bg-gray-700 dark:hover:bg-gray-600 text-blue-600 hover:text-blue-600 dark:text-blue-500 dark:hover:text-blue-500 border-blue-600 dark:border-blue-500"
          >
            Statistics
          </button>
        </li>
        <li class="w-full">
          <button
            id="about-tab"
            data-tabs-target="#about"
            type="button"
            role="tab"
            aria-controls="about"
            aria-selected="false"
            class="inline-block p-4 w-full bg-gray-50 hover:bg-gray-100 focus:outline-none dark:bg-gray-700 dark:hover:bg-gray-600 dark:border-transparent text-gray-500 hover:text-gray-600 dark:text-gray-400 border-gray-100 hover:border-gray-300 dark:border-gray-700 dark:hover:text-gray-300"
          >
            Services
          </button>
        </li>
        <li class="w-full">
          <button
            id="faq-tab"
            data-tabs-target="#faq"
            type="button"
            role="tab"
            aria-controls="faq"
            aria-selected="false"
            class="inline-block p-4 w-full bg-gray-50 rounded-tr-lg hover:bg-gray-100 focus:outline-none dark:bg-gray-700 dark:hover:bg-gray-600 dark:border-transparent text-gray-500 hover:text-gray-600 dark:text-gray-400 border-gray-100 hover:border-gray-300 dark:border-gray-700 dark:hover:text-gray-300"
          >
            FAQ
          </button>
        </li>
      </ul>
      <div
        id="fullWidthTabContent"
        class="border-t border-gray-200 dark:border-gray-600"
      >
        <div
          class="p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800"
          id="stats"
          role="tabpanel"
          aria-labelledby="stats-tab"
        >
          <dl
            class="grid grid-cols-2 gap-8 p-4 mx-auto max-w-screen-xl text-gray-900 sm:grid-cols-3 xl:grid-cols-6 dark:text-white sm:p-8"
          >
            <div class="flex flex-col justify-center items-center">
              <dt class="mb-2 text-3xl font-extrabold">73M+</dt>
              <dd class="font-light text-gray-500 dark:text-gray-400">
                Developers
              </dd>
            </div>
            <div class="flex flex-col justify-center items-center">
              <dt class="mb-2 text-3xl font-extrabold">100M+</dt>
              <dd class="font-light text-gray-500 dark:text-gray-400">
                Public repositories
              </dd>
            </div>
            <div class="flex flex-col justify-center items-center">
              <dt class="mb-2 text-3xl font-extrabold">1000s</dt>
              <dd class="font-light text-gray-500 dark:text-gray-400">
                Open source projects
              </dd>
            </div>
            <div class="flex flex-col justify-center items-center">
              <dt class="mb-2 text-3xl font-extrabold">1B+</dt>
              <dd class="font-light text-gray-500 dark:text-gray-400">
                Contributors
              </dd>
            </div>
            <div class="flex flex-col justify-center items-center">
              <dt class="mb-2 text-3xl font-extrabold">90+</dt>
              <dd class="font-light text-gray-500 dark:text-gray-400">
                Top Forbes companies
              </dd>
            </div>
            <div class="flex flex-col justify-center items-center">
              <dt class="mb-2 text-3xl font-extrabold">4M+</dt>
              <dd class="font-light text-gray-500 dark:text-gray-400">
                Organizations
              </dd>
            </div>
          </dl>
        </div>
        <div
          class="hidden p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800"
          id="about"
          role="tabpanel"
          aria-labelledby="about-tab"
        >
          <h2
            class="mb-5 text-2xl font-extrabold tracking-tight text-gray-900 dark:text-white"
          >
            We invest in the world’s potential
          </h2>
          <!-- List -->
          <ul role="list" class="space-y-4 text-gray-500 dark:text-gray-400">
            <li class="flex space-x-2">
              <!-- Icon -->
              <svg
                class="flex-shrink-0 w-4 h-4 text-blue-600 dark:text-blue-500"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="font-light leading-tight"
                >Dynamic reports and dashboards</span
              >
            </li>
            <li class="flex space-x-2">
              <!-- Icon -->
              <svg
                class="flex-shrink-0 w-4 h-4 text-blue-600 dark:text-blue-500"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="font-light leading-tight"
                >Templates for everyone</span
              >
            </li>
            <li class="flex space-x-2">
              <!-- Icon -->
              <svg
                class="flex-shrink-0 w-4 h-4 text-blue-600 dark:text-blue-500"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="font-light leading-tight">Development workflow</span>
            </li>
            <li class="flex space-x-2">
              <!-- Icon -->
              <svg
                class="flex-shrink-0 w-4 h-4 text-blue-600 dark:text-blue-500"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                  clip-rule="evenodd"
                ></path>
              </svg>
              <span class="font-light leading-tight"
                >Limitless business automation</span
              >
            </li>
          </ul>
        </div>
        <div
          class="hidden p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800"
          id="faq"
          role="tabpanel"
          aria-labelledby="faq-tab"
        >
          <div
            id="accordion-flush"
            data-accordion="collapse"
            data-active-classes="bg-white dark:bg-gray-800 text-gray-900 dark:text-white"
            data-inactive-classes="text-gray-500 dark:text-gray-400"
          >
            <h2 id="accordion-flush-heading-1">
              <button
                type="button"
                class="flex justify-between items-center py-5 w-full font-medium text-left border-b border-gray-200 dark:border-gray-700 bg-white dark:bg-gray-800 text-gray-900 dark:text-white"
                data-accordion-target="#accordion-flush-body-1"
                aria-expanded="true"
                aria-controls="accordion-flush-body-1"
              >
                <span>What is Flowbite?</span>
                <svg
                  data-accordion-icon=""
                  class="w-6 h-6 rotate-180 shrink-0"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
              </button>
            </h2>
            <div
              id="accordion-flush-body-1"
              class=""
              aria-labelledby="accordion-flush-heading-1"
            >
              <div
                class="py-5 font-light border-b border-gray-200 dark:border-gray-700"
              >
                <p class="mb-2 text-gray-500 dark:text-gray-400">
                  Flowbite is an open-source library of interactive components
                  built on top of Tailwind CSS including buttons, dropdowns,
                  modals, navbars, and more.
                </p>
                <p class="text-gray-500 dark:text-gray-400">
                  Check out this guide to learn how to
                  <a
                    href="/docs/getting-started/introduction/"
                    class="text-blue-600 dark:text-blue-500 hover:underline"
                    >get started</a
                  >
                  and start developing websites even faster with components on
                  top of Tailwind CSS.
                </p>
              </div>
            </div>
            <h2 id="accordion-flush-heading-2">
              <button
                type="button"
                class="flex justify-between items-center py-5 w-full font-medium text-left text-gray-500 border-b border-gray-200 dark:border-gray-700 dark:text-gray-400"
                data-accordion-target="#accordion-flush-body-2"
                aria-expanded="false"
                aria-controls="accordion-flush-body-2"
              >
                <span>Is there a Figma file available?</span>
                <svg
                  data-accordion-icon=""
                  class="w-6 h-6 shrink-0"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
              </button>
            </h2>
            <div
              id="accordion-flush-body-2"
              class="hidden"
              aria-labelledby="accordion-flush-heading-2"
            >
              <div
                class="py-5 font-light border-b border-gray-200 dark:border-gray-700"
              >
                <p class="mb-2 text-gray-500 dark:text-gray-400">
                  Flowbite is first conceptualized and designed using the Figma
                  software so everything you see in the library has a design
                  equivalent in our Figma file.
                </p>
                <p class="text-gray-500 dark:text-gray-400">
                  Check out the
                  <a
                    href="https://flowbite.com/figma/"
                    class="text-blue-600 dark:text-blue-500 hover:underline"
                    >Figma design system</a
                  >
                  based on the utility classes from Tailwind CSS and components
                  from Flowbite.
                </p>
              </div>
            </div>
            <h2 id="accordion-flush-heading-3">
              <button
                type="button"
                class="flex justify-between items-center py-5 w-full font-medium text-left text-gray-500 border-b border-gray-200 dark:border-gray-700 dark:text-gray-400"
                data-accordion-target="#accordion-flush-body-3"
                aria-expanded="false"
                aria-controls="accordion-flush-body-3"
              >
                <span
                  >What are the differences between Flowbite and Tailwind
                  UI?</span
                >
                <svg
                  data-accordion-icon=""
                  class="w-6 h-6 shrink-0"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
              </button>
            </h2>
            <div
              id="accordion-flush-body-3"
              class="hidden"
              aria-labelledby="accordion-flush-heading-3"
            >
              <div
                class="py-5 font-light border-b border-gray-200 dark:border-gray-700"
              >
                <p class="mb-2 text-gray-500 dark:text-gray-400">
                  The main difference is that the core components from Flowbite
                  are open source under the MIT license, whereas Tailwind UI is
                  a paid product. Another difference is that Flowbite relies on
                  smaller and standalone components, whereas Tailwind UI offers
                  sections of pages.
                </p>
                <p class="mb-2 text-gray-500 dark:text-gray-400">
                  However, we actually recommend using both Flowbite, Flowbite
                  Pro, and even Tailwind UI as there is no technical reason
                  stopping you from using the best of two worlds.
                </p>
                <p class="mb-2 text-gray-500 dark:text-gray-400">
                  Learn more about these technologies:
                </p>
                <ul class="pl-5 list-disc text-gray-500 dark:text-gray-400">
                  <li>
                    <a
                      href="https://flowbite.com/pro/"
                      class="text-blue-600 dark:text-blue-500 hover:underline"
                      >Flowbite Pro</a
                    >
                  </li>
                  <li>
                    <a
                      href="https://tailwindui.com/"
                      rel="nofollow"
                      class="text-blue-600 dark:text-blue-500 hover:underline"
                      >Tailwind UI</a
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End Works and services -->
  </div>
  <FooterComponent class="mt-24" />
</template>
<style lang="css">
.h-full2 {
  height: 120vh;
}
.video-docker video {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.video-docker::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: rgba(0, 0, 0, 0.6);
  z-index: 1;
}

.video-content {
  z-index: 2;
}
</style>
