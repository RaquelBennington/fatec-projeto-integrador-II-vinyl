<template>
  <svg class="shop" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
    <g id="cart">
      <circle cx="45.55" cy="88.68" r="6.49"></circle>
      <circle cx="74.82" cy="88.68" r="6.49"></circle>
      <path
        d="M96.79,22.81a8.45,8.45,0,0,0-8.25-10.3H27.1L25.54,4.84H3v8H19L32,76.75H91.12v-8H38.51l-1.36-6.69H88Z"
      ></path>
    </g>
  </svg>
</template>


<style scoped>
.shop{
  display: flex;
  height: 20px;
}


svg path {
  fill:white;
}

svg:hover path {
  fill:gray;
}

svg circle{
    fill:gray;
}

svg:hover circle {
  fill:gray;
}


</style>