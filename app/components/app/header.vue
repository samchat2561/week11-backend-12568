<template>
  <div class="font-[sans-serif] bg-gray-200 max-h-screen">
    <!-- Start Header -->
    <div class="text-gray-600 bg-[#AC1CE3]">
      <nav class="container px-6 py-[0.4rem] mx-auto md:flex md:justify-between md:items-center shadow-xl pl-5 md:px-30 z-0 cursor-pointer">
        <div class="flex items-center justify-between">
          <NuxtLink to="/" class="flex justify-center items-center text-white text-md md:text-2xl font-bold hover:text-blue-200">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8">
              <path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.438 60.438 0 0 0-.491 6.347A48.62 48.62 0 0 1 12 20.904a48.62 48.62 0 0 1 8.232-4.41 60.46 60.46 0 0 0-.491-6.347m-15.482 0a50.636 50.636 0 0 0-2.658-.813A59.906 59.906 0 0 1 12 3.493a59.903 59.903 0 0 1 10.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.717 50.717 0 0 1 12 13.489a50.702 50.702 0 0 1 7.74-3.342M6.75 15a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm0 0v-3.675A55.378 55.378 0 0 1 12 8.443m-7.007 11.55A5.981 5.981 0 0 0 6.75 15.75v-1.5" />
            </svg>
            <span class="text-center ml-2">Dev</span>
          </NuxtLink>

          <!-- Start mobile menu button -->
          <div class="flex md:hidden">
            <button type="button" class="text-white hover:text-gray-400 focus:text-gray-300 focus:outline-none">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
              </svg>
            </button>
          </div>
          <!-- End mobile menu button -->
          
        </div>
      </nav>
    </div>
    <!-- End Header -->
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
