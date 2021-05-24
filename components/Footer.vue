<template>
  <footer>
    <div class="bg-black flex justify-center mx-auto px-4 sm:px-4">
      <div>
        <div
          class="flex-col items-center space-x-5 text-white m-4 px-4 sm:px-4"
        >
          <nuxt-link
            to="/sobre"
            class="text-base font-medium text-white hover:text-gray-500"
            >Sobre</nuxt-link
          >
          <nuxt-link
            to="/cultura"
            class="text-base font-medium text-white hover:text-gray-500"
            >Disco é Cultura</nuxt-link
          >
          <nuxt-link
            to="/contato"
            class="text-base font-medium text-white hover:text-gray-500"
            >Contato</nuxt-link
          >
          <nuxt-link
            to="/login"
            class="text-base font-medium text-white hover:text-gray-500"
            >Login</nuxt-link
          >
        </div>
      </div>
    </div>
    <div class="bg-black flex justify-center mx-auto px-6 sm:px-4">
      <div class="flex justify-center m-6">
        <nuxt-link to="/index"><Logo /></nuxt-link>
      </div>
    </div>

    <!-- Footer copyright -->
    <div
      class="bg-black flex justify-center space-x-10 text-white py-5 border-t border-gray-400"
    >
      <p>
        <small>&copy; VINYL. 1985 - 2021. All&nbsp;rights&nbsp;reserved.</small>
      </p>
    </div>
  </footer>
</template>