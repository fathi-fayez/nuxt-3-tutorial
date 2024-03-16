/
<template>
  <div>
    <p>product details for {{ id }}</p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit voluptatum
    cupiditate officia odit quia adipisci laboriosam quo dolore illo molestias!
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style></style>
