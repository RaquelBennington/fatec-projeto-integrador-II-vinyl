<template>
  <div class="relative bg-black">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
      <div class="flex justify-between items-center py-6 md:justify-between md:space-x-10 bg-black">
        
        <div class="max-w-7xl px-2 sm:px-2">
          <nuxt-link to="/index"><Logo /></nuxt-link>
        </div>
        
        <div class="-mr-2 -my-2 md:hidden">
          <button
            type="button"
            class="rounded-md p-1 inline-flex items-center justify-center text-white border-black border-2  "
            aria-expanded="false"
          >
            <span class="sr-only">Open menu</span>
            
            <svg
              class="h-6 w-6"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              aria-hidden="true"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16"
              />
            </svg>
          </button>
        </div>
 
        <nav class="hidden md:flex space-x-10 text-white bg-black"> 
          <nuxt-link to="/sobre" class="text-base font-medium text-white hover:text-gray-500">Sobre</nuxt-link>
          <nuxt-link to="/cultura" class="text-base font-medium text-white hover:text-gray-500">Disco é cultura</nuxt-link>
          <nuxt-link to="/contato" class="text-base font-medium text-white hover:text-gray-500">Contato</nuxt-link> 
          <nuxt-link to="/login" class="text-base font-medium text-white hover:text-gray-500"><Icon-login/></nuxt-link> 
          <nuxt-link to="/carrinho" class="text-base font-medium text-white hover:text-gray-500"><Icon-shop/></nuxt-link>       
        </nav>

      </div>
    </div>
  </div>
</template>


<style scoped>


</style>