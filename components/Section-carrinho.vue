<template>
  <div class="flex bg-black" style="font-family: 'Muli', sans-serif">
    <div
      class="container ml-auto mr-auto flex flex-wrap justify-items-center space-x-16"
    >
      <div class="w-full pl-5 lg:pl-2">
        <h1
          class="text-center text-3xl lg:text-4xl text-gray-500 font-extrabold pb-8 py-10"
        >
          {{ $t("titleCart") }}
        </h1>

        <div
          class="bg-white rounded p-2 hover:shadow-xl border-white border border-t border-b border-r"
        >
          <div
            class="rounded-lg p-8 bg-white flex flex-col border-black border border-t border-b border-r"
          >
            <div class="flex flex-col justify-center">
              <p class="text-base text-center text-gray-600 leading-none py-2">
                {{ $t("paragraphCart") }}
              </p>

              <p class="py-2 flex items-center justify-center">
                <nuxt-link
                  to="/"
                  class="bg-white ml-8 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-bold text-black hover:text-gray-500 border-black border-2 border-t border-b border-r"
                  >{{ $t("buy") }}</nuxt-link
                >
              </p>
              <p></p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


 