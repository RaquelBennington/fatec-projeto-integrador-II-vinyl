<template>
  <div
    class="flex items-center w-screen min-h-screen bg-black"
    style="font-family: 'Muli', sans-serif"
  >
    <div class="container ml-auto mr-auto flex flex-wrap items-start">
      <div class="w-full pl-5 lg:pl-2 mb-4 mt-4">
        <h1 class="text-3xl lg:text-4xl text-gray-700 font-extrabold py-4">
          Destaque
        </h1>
      </div>

      <div>
        <ProductCard
          v-for="product of produts"
          :key="product.id"
          :url='product.url'
          :title="product.title"
          :description="product.description"
          :price="product.price"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Produtos",

  data() {
    return {
      products: [
        {
          id: 1,
          photo: '~/assets/Discos/stevie-wonder-innervisions-1973.jpg',
          title: "Artista 1",
          description: "Nome do Disco 1",
          price: "200,00",
        },
        {
          id: 2,
          photo: '~/assets/Discos/stevie-wonder-innervisions-1973.jpg',
          title: "Artista 2",
          description: "Nome do Disco 1",
          price: "200,00",
        },
        {
          id: 3,
          photo: '~/assets/Discos/stevie-wonder-innervisions-1973.jpg',
          title: "Artista 3",
          description: "Nome do Disco 1",
          price: "200,00",
        },
        {
          id: 4,
          photo: '~/assets/Discos/stevie-wonder-innervisions-1973.jpg',
          title: "Artista 4",
          description: "Nome do Disco 1",
          price: "200,00",
        },
      ],
    };
  },
};
</script>