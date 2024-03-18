<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4">
        <nuxt-link to="/" class="font-bold">Nuxt App</nuxt-link>
      </nav>
    </header>

    <!-- output the page content -->
    <div class="container mx-auto p-4">
      <slot />
    </div>

    <footer class="container mx-auto p-4 flex justify-between border-t-2">
      <ul class="flex gap-4">
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/about">about</nuxt-link></li>
        <li><nuxt-link to="/products">products</nuxt-link></li>
      </ul>
    </footer>
  </div>
</template>

<script setup></script>

<style>
.router-link-exact-active {
  color: #0de33b;
}
</style>
