<template>
  <nav>
    <nav class="bg-[#1B1C14] p-3">
      <div class="flex justify-between items-center gap-2 px-10">
        <div>
          <h2
            class="text-3xl text-white font-bold uppercase border-white border-b-4 p-2 rounded-full hover:border-b-2"
          >
            Movie<span class="text-red-500">Hub</span>
          </h2>
        </div>
        <div class="flex justify-between items-center gap-2">
          <NuxtLink
            to="/"
            class="px-3 py-2 rounded-md text-sm font-medium text-white hover:bg-red-500 focus:outline-none focus:bg-red-500"
          >
            Home
          </NuxtLink>
          <NuxtLink
            to="/"
            class="px-3 py-2 rounded-md text-sm font-medium text-white hover:bg-red-500 focus:outline-none focus:bg-red-500"
          >
            Login
          </NuxtLink>
          <NuxtLink
            to="/"
            class="px-3 py-2 rounded-md text-sm font-medium text-white hover:bg-red-500 focus:outline-none focus:bg-red-500"
          >
            Registration
          </NuxtLink>
          <NuxtLink
            to="/"
            class="px-3 py-2 rounded-md text-sm font-medium text-white hover:bg-red-500 focus:outline-none focus:bg-red-500"
          >
            Contact
          </NuxtLink>
        </div>
      </div>
    </nav>
  </nav>
</template>

<script setup></script>

<style scoped></style>
