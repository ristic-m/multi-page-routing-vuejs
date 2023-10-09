<template>
  <div>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/contact">Contact</router-link>
    <router-link to="/blog">Blog</router-link>
    <router-link to="/post/:id">Post</router-link>
    <router-view></router-view>
  </div>
</template>