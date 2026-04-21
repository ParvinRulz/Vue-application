<script setup></script>

<template>
  <div>
    <header class="header">
      <h3>ParkEase</h3>
      <nav class="nav">
        <RouterLink to="/">Home</RouterLink> 
        <RouterLink to="/about">About Us</RouterLink>
      </nav>
    </header>
    <main>
      <RouterView />
    </main>
  </div>
</template>

<style scoped></style>