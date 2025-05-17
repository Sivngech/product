<template>
    <div>
      <h1>Product Detail Page</h1>
      <p>Product ID: {{ id }}</p>
    </div>
  </template>
  
  <script setup>
  const route = useRoute()
  const id = route.params.id
  </script>
  