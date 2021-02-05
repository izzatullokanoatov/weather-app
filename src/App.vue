<template>
  <div id="app">
    <div id="nav">
      <router-link to="/" class="text-gray text-3xl">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>
