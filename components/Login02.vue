<template>
  <section>
    <div class="h-screen font-sans login bg-cover">
      <div
        class="container mx-auto h-full flex flex-1 justify-center items-center"
      >
        <div class="w-full max-w-lg">
          <div class="leading-loose">
            <form
              class="max-w-sm m-4 p-10 bg-white bg-opacity-25 rounded shadow-xl"
            >
              <p class="text-white font-medium text-center text-lg font-bold">
                Bem-vindo de volta ao VINYL.
              </p>

              <div class="mt-2">
                <label class="block text-sm text-white">Senha</label>
                <input
                  class="w-full px-5 py-1 text-gray-700 bg-gray-300 rounded focus:outline-none focus:bg-white"
                  type="password"
                  id="password"
                  placeholder="Digite a sua senha"
                  arial-label="password"
                  required
                />
              </div>

              <div class="mt-4 items-center flex justify-between">
                <button
                  class="px-10 py-1 text-white font-light tracking-wider bg-gray-900 hover:bg-gray-800 rounded"
                  type="submit"
                >
                  Entrar
                </button>
                <a
                  class="inline-block right-0 align-baseline font-bold text-sm text-500 text-white hover:text-red-400"
                  href="#"
                  >Esqueceu a senha ?</a
                >
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.login {
  background-image: url(~/assets/Login/background_login_01.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
</style>