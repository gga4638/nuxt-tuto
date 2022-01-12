<template>
  <div>
    <Navigation />
    <NuxtLink to="/about" no-prefetch>About page not pre-fetched</NuxtLink>
    <NuxtLink to="/about" :prefetch="false">About page not pre-fetched</NuxtLink>
    <hr />
    <h1>I am the parent view</h1>
    <br />
    <NuxtChild :foobar="123" />
  </div>
</template>


