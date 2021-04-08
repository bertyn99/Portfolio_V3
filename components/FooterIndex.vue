<template>
  <div
    class="py-24 leading-6 text-left text-gray-900 bg-blue-875 box-border md:pt-12 md:pb-16"
  >
    <div class="px-4 mx-auto w-full text-left box-border">
      <div
        class="flex flex-col md:flex-wrap items-center -mx-4 text-gray-900 box-border"
      >
        <div
          class="relative px-4 w-full md:w-1/2 xl:flex-grow-0 xl:flex-shrink-0 md:flex-grow-0 md:flex-shrink-0 box-border"
          style="min-height: 1px"
        >
          <div class="box-border">
            <ul class="p-0 m-0 box-border">
              <li
                class="inline-block mr-12 box-border"
                style="list-style: none"
              >
                <nuxt-link
                  to="#"
                  class="text-sm font-medium text-white no-underline bg-transparent cursor-pointer box-border hover:text-indigo-600 hover:no-underline focus:no-underline"
                  style="
                    transition: all 0.3s ease 0s;
                    outline: none medium;
                    list-style: outside none none;
                  "
                  >About</nuxt-link
                >
              </li>
              <li
                class="inline-block mr-12 box-border"
                style="list-style: none"
              >
                <nuxt-link
                  to="#"
                  class="text-sm font-medium text-white no-underline bg-transparent cursor-pointer box-border hover:text-indigo-600 hover:no-underline focus:no-underline"
                  style="
                    transition: all 0.3s ease 0s;
                    outline: none medium;
                    list-style: outside none none;
                  "
                  >Services</nuxt-link
                >
              </li>
              <li
                class="inline-block mr-12 box-border"
                style="list-style: none"
              >
                <nuxt-link
                  to="#"
                  class="text-sm font-medium text-white no-underline bg-transparent cursor-pointer box-border hover:text-indigo-600 hover:no-underline focus:no-underline"
                  style="
                    transition: all 0.3s ease 0s;
                    outline: none medium;
                    list-style: outside none none;
                  "
                  >Portfolio</nuxt-link
                >
              </li>
            </ul>
          </div>
        </div>
        <div
          class="relative px-4 w-full md:w-1/2 xl:flex- grow-0 xl:flex-shrink-0 md:flex-grow-0 md:flex-shrink-0 box-border"
          style="min-height: 1px"
        >
          <div class="text-right box-border">
            <ul class="p-0 m-0 box-border">
              <li class="inline-block box-border" style="list-style: none">
                <nuxt-link
                  to="https://www.facebook.com/helenbertyn.boulikoudamours"
                  class="inline-block mr-2 w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-blue-900 border-solid cursor-pointer box-border hover:bg-indigo-600 hover:border-indigo-600 hover:text-white hover:no-underline focus:no-underline"
                  style="
                    transition: all 0.3s ease 0s;
                    outline: none medium;
                    border-radius: 50%;
                    list-style: outside none none;
                  "
                >
                  <fa-icon :icon="['fab', 'facebook-f']" />
                </nuxt-link>
              </li>
              <li class="inline-block box-border" style="list-style: none">
                <nuxt-link
                  to="https://www.twitter.com/boulibear"
                  class="inline-block mr-2 w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-blue-900 border-solid cursor-pointer box-border hover:bg-indigo-600 hover:border-indigo-600 hover:text-white hover:no-underline focus:no-underline"
                  style="
                    transition: all 0.3s ease 0s;
                    outline: none medium;
                    border-radius: 50%;
                    list-style: outside none none;
                  "
                >
                  <fa-icon :icon="['fab', 'twitter']" />
                </nuxt-link>
              </li>
              <li class="inline-block box-border" style="list-style: none">
                <nuxt-link
                  to="https://www.instagram.com/bertyn.blk/"
                  class="inline-block mr-2 w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-blue-900 border-solid cursor-pointer box-border hover:bg-indigo-600 hover:border-indigo-600 hover:text-white hover:no-underline focus:no-underline"
                  style="
                    transition: all 0.3s ease 0s;
                    outline: none medium;
                    border-radius: 50%;
                    list-style: outside none none;
                  "
                >
                  <fa-icon :icon="['fab', 'instagram']" />
                </nuxt-link>
              </li>
              <li class="inline-block box-border" style="list-style: none">
                <nuxt-link
                  to="https://www.linkedin.com/in/bertyn-boulikou/"
                  class="inline-block mr-2 w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-blue-900 border-solid cursor-pointer box-border hover:bg-indigo-600 hover:border-indigo-600 hover:text-white hover:no-underline focus:no-underline"
                  style="
                    transition: all 0.3s ease 0s;
                    outline: none medium;
                    border-radius: 50%;
                    list-style: outside none none;
                  "
                >
                  <fa-icon :icon="['fab', 'linkedin']" />
                </nuxt-link>
              </li>
            </ul>
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
