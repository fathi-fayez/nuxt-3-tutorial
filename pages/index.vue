<template>
  <div>
    <div class="grid grid-cols-4 gap-4">
      <div v-for="product in products" :key="product.id">
        <productCard :product="product" />
      </div>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
  layout: "products",
});
//fetch the products
const { data: products } = await useFetch("https://fakestoreapi.com/products");
</script>

<style>
img {
  width: 200px;
}
</style>
