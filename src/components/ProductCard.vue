<template>
  <div class="product-card">
    <div class="box-url">
      <img :src="img" alt="" />
    </div>
    <h4>{{ series }}</h4>

    <div class="overlay-card">
      <h3>
        <!-- price -->
        {{ price }}
      </h3>
      <h4>
        <!-- type -->
        {{ type }}
      </h4>
    </div>
  </div>
</template>
<script>
export default {
  name: "ProductCard",
  props: ["img", "series", "price", "type"],
};
</script>
