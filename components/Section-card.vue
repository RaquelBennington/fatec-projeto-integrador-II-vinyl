<template>
  <div
    class="flex items-center w-screen min-h-screen bg-black"
    style="font-family: 'Muli', sans-serif"
  >
    <div class="container ml-auto mr-auto flex flex-wrap items-start py-6">
    <Card
      v-for="product of products"
      :key="product.id"
      :photo="product.photo"
      :artist="product.artist"
      :title="product.title"
      :price="product.price"
    />
  </div>
  </div>
</template>

<script>
import { mapState } from "vuex";
export default {
  name: "Section-card",
  computed: {
    ...mapState({
      products: (state) => state.card.products,
    }),
  },
};
</script>