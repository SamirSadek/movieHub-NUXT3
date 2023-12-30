<template>
  <section class="search-section bg-red-200 py-4">
    <div class="container mx-auto md:px-40 px-5">
      <div class="flex">
        <input
          type="text"
          class="border border-red-400 py-2 px-4 w-full rounded-l-full focus:outline-none"
          placeholder="Search Movie ...."
          v-model.lazy="searchInput"
        />
        <button
          class="bg-red-500 hover:bg-red-600 border border-red-400 hover:font-bold text-white py-4 px-8 rounded-r-full"
          type="submit"
          @click="$emit('searchMovie', searchInput)"
        >
          Search
        </button>
      </div>
      <span v-if="searchError" class="text-red-700 px-4 py-3" role="alert">
        This field is required*</span
      >
    </div>
  </section>
</template>

<script setup>
const searchInput = ref("");
defineProps(["searchError"]);
</script>

<style scoped></style>
