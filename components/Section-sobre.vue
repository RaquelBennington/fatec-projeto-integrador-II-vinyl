<template>
  <section class="px-24 bg-black flex-col items-center justify-center ">
    <article>
      <div class="bg-black rounded m-h-54 p-2 border-white py-4 px-60">
        <div class="px-6 bg-black">
          <div class="rounded-md p-8 bg-black flex flex-col p-8">
            <h1 class="text-center text-3xl lg:text-4xl text-gray-500 font-extrabold pb-8 mr-5">{{ $t("who") }}</h1>
            <p class="text-white ">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Soluta
              perferendis eius esse ad quo? Placeat explicabo corporis vero!
              Neque, obcaecati eaque doloribus aspernatur sunt pariatur
              explicabo doloremque molestiae eligendi repellendus? Dolore iusto
              nobis doloribus error hic quia blanditiis debitis earum, possimus
              quidem delectus reiciendis eos veritatis sunt accusamus,
              recusandae minus.
            </p>
          </div>
          <div class="rounded-md p-4 bg-black space-x-16 flex items-center justify-center">
            <div
              class="rounded-md p-4 bg-black flex flex-col border-white border border-t border-b border-r"
            >
              <img
                class="w-80 ml-auto mr-auto rounded-md"
                src="~/assets/Equipe/equipe_001.jpeg"
                alt=""
              />
              <div class="flex-col py-2">
                <h2 class="text-white font-bold text-center">Fernando Dias</h2>
                <p class="text-white font-bold text-center">{{ $t("Owner") }}</p>
              </div>
            </div>

            <div
              class="rounded-md p-4 bg-black flex flex-col border-white border border-t border-b border-r"
            >
              <img
                class="w-80 ml-auto mr-auto rounded-md"
                src="~/assets/Equipe/equipe_002.jpeg"
                alt=""
              />
              <div class="flex-col py-2">
                <h2 class="text-white font-bold text-center">Carlos Antonio</h2>
                <p class="text-white font-bold text-center">{{ $t("seller") }}</p>
              </div>
            </div>

            <div
              class="rounded-md p-4 bg-black flex flex-col border-white border border-t border-b border-r"
            >
              <img
                class="w-80 ml-auto mr-auto rounded-md"
                src="~/assets/Equipe/equipe_003.jpeg"
                alt=""
              />
              <div class="flex-col py-2">
                <h2 class="text-white font-bold text-center">João Freitas</h2>
                <p class="text-white font-bold text-center">{{ $t("Researcher") }}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </article>

    <article>
      <div class="bg-black rounded m-h-54 p-2 border-white">
        <div class="px-6 bg-black flex-col items-center justify-center">
          <div class="rounded-md p-8 bg-black flex flex-col  px-60">
            <h1 class="text-center text-3xl lg:text-4xl text-gray-500 font-extrabold pb-8 mr-5">{{ $t("where") }}</h1>
            <p class="text-white py-8">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Soluta
              perferendis eius esse ad quo? Placeat explicabo corporis vero!
              Neque, obcaecati eaque doloribus aspernatur sunt pariatur
              explicabo doloremque molestiae eligendi repellendus? Dolore iusto
              nobis doloribus error hic quia blanditiis debitis earum, possimus
              quidem delectus reiciendis eos veritatis sunt accusamus,
              recusandae minus.
            </p>

            <p class="text-white">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Soluta
              perferendis eius esse ad quo? Placeat explicabo corporis vero!
              Neque, obcaecati eaque doloribus aspernatur sunt pariatur
              explicabo doloremque molestiae eligendi repellendus? Dolore iusto
              nobis doloribus error hic quia blanditiis debitis earum. possimus quidem delectus reiciendis eos veritatis sunt accusamus, recusandae minus. 
            </p>
            <p class="text-white text-bold py-2" >
              Rua: Colecionador, 1985 - Vila Soul
              <br>São Paulo - Brasil<br>
            </p>
          </div>
          <div class="rounded-md p-4 bg-black flex items-center justify-center space-x-16">
            <div
              class="rounded-md p-4 bg-black flex flex-col border-white border border-t border-b border-r"
            >
              <img
                class="w-80 ml-auto mr-auto rounded-md"
                src="~/assets/Sobre/sobre-loja-03.jpg"
                alt=""
              />
            </div>

            <div
              class="rounded-md p-4 bg-black flex flex-col border-white border border-t border-b border-r"
            >
              <img
                class="w-80 ml-auto mr-auto rounded-md"
                src="~/assets/Sobre/sobre-loja-10.jpg"
                alt=""
              />
            </div>

            <div
              class="rounded-md p-4 bg-black flex flex-col border-white border border-t border-b border-r"
            >
              <img
                class="w-80 ml-auto mr-auto rounded-md"
                src="~/assets/Sobre/sobre-loja-02.jpg"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </article>
  </section>
</template>