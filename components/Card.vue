<template>
  <div class="w-full md:w-1/2 lg:w-1/4 pl-5 pr-5 mb-5 lg:pl-2 lg:pr-2">
    <div
      class="bg-black rounded m-h-64 p-2 transform hover:translate-x-1 hover:shadow-xl transition duration-5 border-white border border-t border-b border-r"
    >
      <figure class="mb-2 py-2">
        <img :src="photo" :alt="title" class="h-64 ml-auto mr-auto"
        />
      </figure>
      <div
        class="rounded-lg p-4 bg-white flex flex-col border-black border border-t border-b border-r"
      >
        <div>
          <h5 class="text-black text-2 font-bold leading-none py-2">{{ artist }}</h5>
          <p class="text-base text-gray-600 leading-none">{{ title }}</p>
        </div>
        <div class="flex items-center">
          <div class="text-gray-600 font-bold">{{ price }}</div>

           <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0 py-2">
    <a
      href="#"
      class="ml-8 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-bold text-black hover:text-gray-500 border-black border-2 border-t border-b border-r"
      >comprar
    </a>
  </div>

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProductCard',

  props: {

     photo: {
      type: String,
      default: ''
    },

   artist: {
      type: String,
      default: ''
    },

    title: {
      type: String,
      default: ''
    },

    price: {
      type: String,
      default: ''
    }
  }

}
</script>
