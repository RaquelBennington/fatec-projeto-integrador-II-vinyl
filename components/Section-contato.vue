<template>
  <div
    class="flex items-center w-screen min-h-screen bg-black"
    style="font-family: 'Muli', sans-serif"
  >
    <div
      class="container ml-auto mr-auto flex flex-wrap justify-items-center space-x-16"
    >
      <div class="w-full pl-5 lg:pl-2 mb-4 mt-4">
        <h1 class="text-center text-3xl lg:text-4xl text-gray-500 font-extrabold pb-8 mr-20">
          Fale conosco
        </h1>
      </div>

      <div class="w-full md:w-1/2 lg:w-1/4 pl-5 pr-5 mb-5 lg:pl-2 lg:pr-2">
        <div
          class="bg-white rounded m-h-64 p-2 hover:shadow-xl border-white border border-t border-b border-r"
        >
          <figure class="mb-2">
            <img
              src="~/assets/Icon/localizacao.png"
              alt=""
              class="h-64 ml-auto mr-auto"
            />
          </figure>
          <div
            class="rounded-lg p-4 bg-white flex flex-col border-black border border-t border-b border-r"
          >
            <div>
              <h5 class="text-black text-2 font-bold leading-none">
                Nosso endereço:
              </h5>
              <p class="text-base text-gray-600 leading-none py-2">
                  <a href="http://bit.ly/localizacaovinilclub" target="_blank">Av. Colecionador, 1985 - Vila Soul</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/2 lg:w-1/4 pl-5 pr-5 mb-5 lg:pl-2 lg:pr-2">
        <div
          class="bg-white rounded m-h-64 p-2 hover:shadow-xl border-white border border-t border-b border-r"
        >
          <figure class="mb-2">
            <img
              src="~/assets/Icon/whatsapp.png"
              alt=""
              class="h-64 ml-auto mr-auto"
            />
          </figure>
          <div
            class="rounded-lg p-4 bg-white flex flex-col border-black border border-t border-b border-r"
          >
            <div>
              <h5 class="text-black text-2 font-bold leading-none">
                Nosso whatsapp:
              </h5>
              <p class="text-base text-gray-600 leading-none py-2">
                <a href="http://bit.ly/whatsappvinyl" target="_blank">+55 (11) 90000-0000</a>
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/2 lg:w-1/4 pl-5 pr-5 mb-5 lg:pl-2 lg:pr-2">
        <div
          class="bg-white rounded m-h-64 p-2 hover:shadow-xl border-white border border-t border-b border-r"
        >
          <figure class="mb-2">
            <img
              src="~/assets/Icon/email.png"
              alt=""
              class="h-64 ml-auto mr-auto"
            />
          </figure>
          <div
            class="rounded-lg p-4 bg-white flex flex-col border-black border border-t border-b border-r"
          >
            <div>
              <h5 class="text-black text-2 font-bold leading-none">
                Nosso email:
              </h5>
              <p class="text-base text-gray-600 leading-none py-2">
                <a href="mailto:someone@gmail.com?subject=Hello%20again" target="_blank"
                  >vinilclubcontato@gmail.com</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>