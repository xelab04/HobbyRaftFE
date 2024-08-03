<template>
  <header>
    <nav>
      <ul>
        <li><NuxtLink to="/test">Test</NuxtLink></li>
      </ul>
    </nav>
  </header>
  <n-grid x-gap="0" :cols="3" y-gap="0">
    <n-gi>
      <div class="light-green" />
    </n-gi>
    <n-gi>
      <div class="green">
        <LoginPage />
      </div>
    </n-gi>
    <n-gi>
      <div class="light-green" />
    </n-gi>
  </n-grid>
</template>

<style>
body {
  min-height: 100vh;
}

</style>

<script setup>
  import LoginPage from '@/src/LoginPage.vue';
</script>