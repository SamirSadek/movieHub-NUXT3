<template>
  <div>
    <Hero />
    <SearchBar @search-movie="searchMovie" :searchError="searchError" />
  </div>
</template>

<script setup>
const searchError = ref(false);
const searchMovie = (searchInput) => {
  console.log("Search Product :", searchInput);
  if (searchInput === "") {
    searchError.value = true;
  }
  if (searchInput !== "") {
    searchError.value = false;
  }
};
</script>

<style lang="scss" scoped></style>
