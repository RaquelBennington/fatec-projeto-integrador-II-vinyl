<template>
  <!-- This is an example component -->
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
              Criar conta
            </p>

            <div class="mt-4">
              <label class="block text-sm text-white" for="nome">Nome</label>
              <input
                class="w-full px-5 py-1 text-gray-700 bg-gray-300 rounded focus:outline-none focus:bg-white"
                type="nome"
                id="nome"
                placeholder="Digite seu nome"
                aria-label="Nome"
                required
              />

              <label class="mt-4 block text-sm text-white" for="nome">Sobrenome</label>
              <input
                class="w-full px-5 py-1 text-gray-700 bg-gray-300 rounded focus:outline-none focus:bg-white"
                type="sobrenome"
                id="sobrenome"
                placeholder="Digite seu sobrenome"
                aria-label="Sobrenome"
                required
              />
            </div>

            <div class="mt-4">
              <label class="block text-sm text-white" for="email">E-mail</label>
              <input
                class="w-full px-5 py-1 text-gray-700 bg-gray-300 rounded focus:outline-none focus:bg-white"
                type="email"
                id="email"
                placeholder="Digite o e-mail"
                aria-label="email"
                required
              />
            </div>

            <div class="mt-4">
              <label class="block text-sm text-white" for="email">Confirme seu e-mail</label>
              <input
                class="w-full px-5 py-1 text-gray-700 bg-gray-300 rounded focus:outline-none focus:bg-white"
                type="email"
                id="email"
                placeholder="Digite o seu e-mail"
                aria-label="email"
                required
              />
            </div>

            <div class="mt-4">
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

            <div class="mt-5 items-center flex justify-center">
              <button
                class="px-20 py-1 text-white font-light tracking-wider bg-gray-900 hover:bg-gray-800 rounded"
                type="submit"
              >
                Entrar
              </button>
            </div>

          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.login {
  background-image: url(~/assets/Login/background_login_01.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
</style>