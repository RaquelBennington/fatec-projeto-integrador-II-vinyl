<template>
  <div class="w-full md:w-1/2 lg:w-1/4 pl-5 pr-5 mb-5 lg:pl-2 lg:pr-2">
    <div
      class="bg-black rounded m-h-64 p-2 transform hover:translate-y-2 hover:shadow-xl transition duration-100 border-white border border-t border-b border-r"
    >
      <figure class="mb-2 py-2">
        <img
          src="~/assets/Discos/stevie-wonder-innervisions-1973.jpg"
          alt=""
          class="h-64 ml-auto mr-auto"
        />
      </figure>
      <div
        class="rounded-lg p-4 bg-white flex flex-col border-black border border-t border-b border-r"
      >
        <div>
          <h5 class="text-black text-2 font-bold leading-none py-2">{{ title }}</h5>
          <p class="text-base text-gray-600 leading-none">{{ description }}</p>
        </div>
        <div class="flex items-center">
          <div class="text-gray-600 font-bold">{{ price }}</div>
          <button
            href="javascript:;"
            class="rounded-full bg-black text-white hover:bg-white hover:text-black hover:shadow-xl focus:outline-none w-10 h-10 flex ml-auto transition duration-200"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="stroke-current m-auto"
            >
              <line x1="12" y1="5" x2="12" y2="19"></line>
              <line x1="5" y1="12" x2="19" y2="12"></line>
            </svg>
          </button>
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

    title: {
      type: String,
      default: ''
    },

    description: {
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
