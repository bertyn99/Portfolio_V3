<template>
  <!-- header-start -->
  <header class="bg-gray-900">
    <div class="container mx-auto">
      <div class="sm:flex sm:justify-center sm:items-center sm:px-4 sm:py-3">
        <div
          class="flex items-center sm:w-16 md:24 justify-between px-4 py-3 sm:p-0 sm:mr-4"
        >
          <div class="">
            <img class="h-8" src="logo/BBg.png" alt="Bertyn Boulikou logo" />
          </div>

          <div class="sm:hidden">
            <button
              type="button"
              class="text-gray-200 focus:text-white focus:outline-none"
              @click="isOpen = !isOpen"
            >
              <fa-icon v-if="!isOpen" :icon="['fas', 'bars']" />
              <fa-icon v-if="isOpen" :icon="['fas', 'times']" />
            </button>
          </div>
        </div>
        <div
          :class="isOpen ? 'block bg-white' : 'hidden '"
          class="px-3 pt-2 pb-4 font-sans sm:flex sm:p-0 sm:place-self-center"
        >
          <nuxt-link
            to="/"
            class="block font-thin text-black sm:text-white rounded px-2 py-1 mt-1 hover:text-blue-400 hover:bg-gray-100 sm:hover:bg-transparent"
          >
            Home</nuxt-link
          >
          <nuxt-link
            to="#about"
            class="block font-thin text-black sm:text-white rounded px-2 py-1 mt-1 hover:text-blue-400 hover:bg-gray-100 sm:hover:bg-transparent"
          >
            A propos</nuxt-link
          >
          <nuxt-link
            to="Blog"
            class="block font-thin text-black sm:text-white rounded px-2 py-1 mt-1 hover:text-blue-400 hover:bg-gray-100 sm:hover:bg-transparent"
          >
            Blog</nuxt-link
          >
          <nuxt-link
            to="#portfolio"
            class="block font-thin text-black sm:text-white rounded px-2 py-1 mt-1 hover:text-blue-400 hover:bg-gray-100 sm:hover:bg-transparent"
            >Portfolio</nuxt-link
          >
          <nuxt-link
            to="#contact"
            class="block font-thin text-black sm:text-white rounded px-2 py-1 mt-1 hover:text-blue-400 hover:bg-gray-100 sm:hover:bg-transparent"
            >Contact</nuxt-link
          >
        </div>
      </div>
    </div>
  </header>
  <!-- header-end -->
</template>
<script>
export default {
  name: "Header",
  data() {
    return {
      isOpen: false,
    };
  },
};
</script>

<style lang="postcss" scoped></style>
