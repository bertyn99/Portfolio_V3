<template>
  <div
    class="px-0 pt-40 pb-12 leading-6 text-left text-gray-900 bg-blue-875 box-border md:px-0 md:pb-12 md:pt-24"
  >
    <div class="px-4 mx-auto w-full text-left box-border">
      <div class="flex flex-wrap -mx-4 text-gray-900 box-border">
        <div
          class="relative px-4 w-full xl:flex-grow-0 xl:flex-shrink-0 xl:max-w-full box-border"
          style="min-height: 1px"
        >
          <div class="text-center box-border">
            <h3
              class="mt-0 mb-2 font-sans text-5xl font-bold leading:3 md:leading-5 text-white box-border"
            >
              Vous voulez discuter d'un projet
            </h3>
            <p
              class="mt-3 mb-8 font-sans text-sm font-light leading-7 text-white box-border"
            >
              Si vous avez des idée pour des project ou voulez juste échanger
              avec moi.
            </p>
            <nuxt-link
              class="inline-block py-3 px-10 font-sans text-lg font-medium leading-7 text-white no-underline capitalize bg-indigo-600 rounded-none border border-transparent border-solid cursor-pointer box-border hover:bg-transparent hover:border-indigo-600 hover:text-indigo-600 hover:no-underline focus:no-underline"
              to="contact"
              style="transition: all 0.5s ease 0s; outline: none medium"
              >C'est par ici !</nuxt-link
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.bg-blue-875 {
  background-color: rgb(0%, 11%, 22%);
}
</style>
