<template>
  <div>
    <header>
      <nav>
        <nuxt-link to="/">Nuxt App</nuxt-link>
      </nav>
    </header>

    <!-- output the page content -->
    <div>
      <slot />
    </div>

    <footer>
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/about">about</nuxt-link></li>
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
