<template>
  <nav>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/parent">Parent</NuxtLink>
    <NuxtLink to="/parent/child">Child</NuxtLink>
    <NuxtLink to="/about">About</NuxtLink>
    <NuxtLink to=""
  </nav>
</template>

<style>
  nav {
    background-color: #afeae5;
    padding: 5px;
    margin: 5px 0px;
    border: 1px solid lightseagreen;
  }

  .nuxt-link-active:hover {
    color: red;
  }
  .nuxt-link-exact-active {
    color: coral;
    font-weight: bold;
  }
</style>
