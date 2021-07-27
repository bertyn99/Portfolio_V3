<template>
  <section class="w-full relative">
    <div
      class="
        flex
        banner
        top-0
        right-0
        items-center
        leading-6
        text-left text-gray-900
        bg-no-repeat
        box-border
        w-full
        bg-indigo-500
      "
    >
      <div
        class="hidden absolute bottom-0 text-left lg:block box-border"
        style="right: 20%"
      >
        <img
          src="background/grid.png"
          alt=""
          class="
            text-gray-900
            align-middle
            border-none
            animate-fade-in-up
            box-border
          "
        />
      </div>
      <div
        class="
          absolute
          text-left
          box-border
          hidden
          md:block
          right-20
          top-1/3
          z-36
        "
      >
        <ul class="p-0 m-0 text-gray-900 box-border">
          <li class="block mb-4 box-border" style="list-style: none">
            <a
              href="https://www.facebook.com/helenbertyn.boulikoudamours"
              class="
                inline-block
                overflow-hidden
                relative
                w-10
                h-10
                text-sm
                leading-10
                text-center text-white
                no-underline
                bg-transparent
                border border-white border-opacity-25 border-solid
                cursor-pointer
                box-border
                hover:bg-gray-100 hover:bg-opacity-30
                hover:text-indigo-700
                hover:no-underline
                focus:no-underline
                rounded-full
                focus:outline-none
                z-2
                transition-all
                duration-300
                ease-in
              "
              style="list-style: outside none none"
            >
              <fa-icon :icon="['fab', 'facebook-f']" />
            </a>
          </li>
          <li class="block mb-4 box-border" style="list-style: none">
            <a
              href="https://www.twitter.com/boulibear"
              class="
                inline-block
                overflow-hidden
                relative
                w-10
                h-10
                text-sm
                leading-10
                text-center text-white
                no-underline
                bg-transparent
                border border-white border-opacity-25 border-solid
                cursor-pointer
                box-border
                hover:bg-gray-100 hover:bg-opacity-30
                hover:text-indigo-700
                hover:no-underline
                focus:no-underline
                rounded-full
                focus:outline-none
                z-10
                transition-all
                duration-300
                ease-in
              "
              style="list-style: outside none none"
            >
              <fa-icon :icon="['fab', 'twitter']" />
            </a>
          </li>
          <li class="block mb-4 box-border" style="list-style: none">
            <a
              href="https://www.instagram.com/bertyn.blk/"
              class="
                inline-block
                overflow-hidden
                relative
                w-10
                h-10
                text-sm
                leading-10
                text-center text-white
                no-underline
                bg-transparent
                border border-white border-opacity-25 border-solid
                cursor-pointer
                box-border
                hover:bg-gray-100 hover:bg-opacity-30
                hover:text-indigo-700
                hover:no-underline
                focus:no-underline
                rounded-full
                focus:outline-none
                z-10
                transition-all
                duration-300
                ease-in
              "
              style="transition: all 0.3s ease 0s"
            >
              <fa-icon :icon="['fab', 'instagram']" />
            </a>
          </li>
          <li class="block mb-0 box-border" style="list-style: none">
            <a
              href="https://www.linkedin.com/in/bertyn-boulikou/"
              class="
                inline-block
                overflow-hidden
                relative
                w-10
                h-10
                text-sm
                leading-10
                text-center text-white
                no-underline
                bg-transparent
                border border-white border-opacity-25 border-solid
                cursor-pointer
                box-border
                hover:bg-gray-100 hover:bg-opacity-30
                hover:text-indigo-700
                hover:no-underline
                focus:no-underline
                rounded-full
                focus:outline-none
                z-10
                transition-all
                duration-300
                ease-in
              "
              style="list-style: outside none none"
            >
              <fa-icon :icon="['fab', 'linkedin']" />
            </a>
          </li>
        </ul>
      </div>
      <div class="px-4 mx-auto w-full text-left box-border">
        <div class="flex flex-wrap items-center -mx-4 text-gray-900 box-border">
          <div
            class="
              relative
              px-4
              w-full
              xl:flex-grow-0 xl:flex-shrink-0
              xl:max-w-full
              box-border
            "
            style="min-height: 1px"
          >
            <div class="text-center box-border">
              <h3
                class="
                  mt-0
                  mb-2
                  font-sans
                  text-5xl
                  font-bold
                  text-white
                  capitalize
                  box-border
                  md:text-6xl
                  md:leading-9
                  lg:text-6xl
                  animate-fade-in-down
                "
                style="line-height: 82px"
              >
                Bertyn Boulikou
              </h3>
              <div
                class="
                  text-2xl
                  md:text-4xl
                  font-normal
                  text-white
                  box-border
                  lg:text-base
                  animate-fade-in-up
                "
                style="z-index: 1; line-height: 40px"
              >
                Etudiant en web developpement
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
.banner {
  background-image: url("~@/static/background/circle.png"),
    url("@/static/logo/banner.png");
  z-index: -2;
  height: 840px;
  background-size: 500px 500px, cover;
  background-position: right top, center center;
  content: "";
}
</style>
