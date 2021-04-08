<template>
  <div
    class="relative z-0 py-32 px-0 leading-6 text-left text-gray-900 bg-cover box-border"
    style="
      background-image: url('background/banner.png');
      background-position: center center;
    "
  >
    <div class="px-4 mx-auto w-full text-left box-border">
      <div class="flex flex-wrap -mx-4 text-gray-900 box-border">
        <div
          class="relative px-4 w-full xl:flex-grow-0 xl:flex-shrink-0 xl:max-w-full box-border"
          style="min-height: 1px"
        >
          <div class="block relative w-full box-border" style="z-index: 1">
            <div
              class="overflow-hidden relative box-border"
              style="transform: translate3d(0px, 0px, 0px)"
            >
              <div
                class="block clear-both relative w-64 h-0 box-border"
                style="
                  transform: translate3d(-2220px, 0px, 0px);
                  transition: all 0s ease 0s;
                  width: 6660px;
                  content: '.';
                  line-height: 0px;
                "
              >
                <div
                  class="float-left relative w-64 select-none box-border"
                  style="
                    width: 1110px;
                    transform: translate3d(0px, 0px, 0px);
                    min-height: 1px;
                  "
                >
                  <div class="box-border">
                    <div class="text-center box-border">
                      <div class="box-border">
                        <img
                          src="quote.svg"
                          alt=""
                          class="inline-block w-auto align-middle border-none box-border"
                        />
                      </div>
                      <p
                        class="my-8 mx-0 font-sans text-xl font-normal leading-8 text-white box-border"
                      >
                        Pour gagner votre vie, apprenez à l’école. Pour gagner
                        une fortune, apprenez par vous-même
                      </p>
                      <div class="box-border">
                        <div
                          class="mx-auto mt-auto mb-4 w-10 h-10 box-border"
                          style="border-radius: 50%"
                        >
                          <img
                            class="inline-block mx-auto mt-auto mb-4 w-10 h-10 align-middle border-none box-border"
                            src="img/testmonial/brian-tracy.jpg"
                            alt=""
                            style="border-radius: 50%"
                          />
                        </div>
                        <h3
                          class="mt-0 mb-1 text-sm font-medium text-white box-border"
                          style="line-height: 1.2"
                        >
                          Brian Tracy
                        </h3>
                        <span
                          class="text-xs font-normal leading-5 text-white box-border"
                          >Chef d'entreprise</span
                        >
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="box-border">
              <div
                class="absolute left-0 w-12 h-12 text-sm text-center text-white bg-transparent border border-gray-600 border-solid cursor-pointer select-none box-border hover:bg-indigo-600 hover:border-transparent hover:opacity-100 hover:text-white"
                style="
                  top: 50%;
                  transform: translateY(-50%);
                  transition: all 0.3s ease 0s;
                  border-radius: 50%;
                  line-height: 50px;
                "
              >
                <fa-icon
                  icon="facebook"
                  class="relative left-0 not-italic leading-none normal-case box-border"
                  style="
                    font-family: themify;
                    font-weight: normal;
                    font-variant: normal;
                  "
                />
              </div>
              <div
                class="absolute inset-x-0 w-12 h-12 text-sm text-center text-white bg-transparent border border-gray-600 border-solid cursor-pointer select-none box-border hover:bg-indigo-600 hover:border-transparent hover:opacity-100 hover:text-white"
                style="
                  top: 50%;
                  transform: translateY(-50%);
                  transition: all 0.3s ease 0s;
                  border-radius: 50%;
                  line-height: 50px;
                "
              >
                <fa-icon :icon="['fas', ' chevron-left']"></fa-icon>
              </div>
            </div>
            <div class="hidden box-border"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
