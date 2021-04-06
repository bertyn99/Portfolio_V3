<template>
  <section class="w-full relative">
    <div
      class="flex top-0 right-0 items-center leading-6 text-left text-gray-900 bg-no-repeat bg-cover box-border md:bg-cover w-full bg-indigo-500"
      style="
        background-image: url('background/circle.png'), url('logo/banner.png');
        z-index: -2;
        height: 840px;
        background-size: 500px 500px, cover;
        background-position: right top, center center;
        content: '';
      "
    >
      <div
        class="hidden absolute bottom-0 text-left lg:block box-border"
        style="right: 20%"
      >
        <img
          src="background/grid.png"
          alt=""
          class="text-gray-900 align-middle border-none box-border"
        />
      </div>
      <div
        class="absolute text-left box-border hidden md:block"
        style="
          right: 100px;
          top: 50%;
          transform: translateY(-50%);
          z-index: 999;
        "
      >
        <ul class="p-0 m-0 text-gray-900 box-border">
          <li class="block mb-4 box-border" style="list-style: none">
            <a
              href="https://www.facebook.com/helenbertyn.boulikoudamours"
              class="inline-block overflow-hidden relative w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-white border-opacity-25 border-solid cursor-pointer box-border hover:text-blue-700 hover:no-underline focus:no-underline"
              style="
                transition: all 0.3s ease 0s;
                outline: none medium;
                border-radius: 50%;
                z-index: 2;
                list-style: outside none none;
              "
            >
              <!-- <i
                class="inline-block not-italic leading-none box-border"
                style="
                  font-variant: normal;
                  font-weight: normal;
                  font-stretch: normal;
                  font-family: FontAwesome;
                  text-rendering: auto;
                  list-style: outside none none;
                "
              ></i> -->
              <fa-icon :icon="['fab', 'facebook-f']" />
            </a>
          </li>
          <li class="block mb-4 box-border" style="list-style: none">
            <a
              href="https://www.twitter.com/boulibear"
              class="inline-block overflow-hidden relative w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-white border-opacity-25 border-solid cursor-pointer box-border hover:text-blue-700 hover:no-underline focus:no-underline"
              style="
                transition: all 0.3s ease 0s;
                outline: none medium;
                border-radius: 50%;
                z-index: 2;
                list-style: outside none none;
              "
            >
              <fa-icon :icon="['fab', 'twitter']" />
            </a>
          </li>
          <li class="block mb-4 box-border" style="list-style: none">
            <a
              href="https://www.instagram.com/bertyn.blk/"
              class="inline-block overflow-hidden relative w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-white border-opacity-25 border-solid cursor-pointer box-border hover:text-blue-700 hover:no-underline focus:no-underline"
              style="
                transition: all 0.3s ease 0s;
                outline: none medium;
                border-radius: 50%;
                z-index: 2;
                list-style: outside none none;
              "
            >
              <fa-icon :icon="['fab', 'instagram']" />
            </a>
          </li>
          <li class="block mb-0 box-border" style="list-style: none">
            <a
              href="https://www.linkedin.com/in/bertyn-boulikou/"
              class="inline-block overflow-hidden relative w-10 h-10 text-sm leading-10 text-center text-white no-underline bg-transparent border border-white border-opacity-25 border-solid cursor-pointer box-border hover:text-blue-700 hover:no-underline focus:no-underline"
              style="
                transition: all 0.3s ease 0s;
                outline: none medium;
                border-radius: 50%;
                z-index: 2;
                list-style: outside none none;
              "
            >
              <fa-icon :icon="['fab', 'linkedin']" />
            </a>
          </li>
        </ul>
      </div>
      <div class="px-4 mx-auto w-full text-left box-border">
        <div class="flex flex-wrap items-center -mx-4 text-gray-900 box-border">
          <div
            class="relative px-4 w-full xl:flex-grow-0 xl:flex-shrink-0 xl:max-w-full box-border"
            style="min-height: 1px"
          >
            <div class="text-center box-border">
              <h3
                class="mt-0 mb-2 font-sans text-5xl font-bold text-white capitalize box-border md:text-6xl md:leading-9 lg:text-6xl"
                style="line-height: 82px"
              >
                Bertyn Boulikou
              </h3>
              <span
                class="relative md:text-4xl font-normal text-white box-border lg:text-base"
                style="z-index: 1; line-height: 60px"
                >Etudiant en web developpement</span
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
