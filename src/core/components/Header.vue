<script setup lang="ts"></script>
<template>
  <header>
    <div class="main-container inner">
      <RouterLink to="/">
        <img src="/logo.svg" width="132px" height="40px" />
      </RouterLink>

      <nav>
        <RouterLink to="/" class="nav-link is-home" exactActiveClass="is-active">Home</RouterLink>
        <p>Seach Modal</p>
        <RouterLink to="/coins" class="nav-link" exactActiveClass="is-active">All Coins</RouterLink>
      </nav>
    </div>
  </header>
</template>
