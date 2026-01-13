<script setup>
// Phải viết đúng tên file bạn đã đặt trong thư mục
import Hearder from './layout/Hearder.vue'
import Footer from './layout/Footer.vue'
import Comtainer from './components/Comtainer.vue'
</script>

<template>
  <div class="app-wrapper"> <Hearder />
    <Comtainer />
    <Footer />
  </div>
</template>

<style>
body {
  margin: 0;
  padding: 0;
  overflow-x: hidden; /* Cấm tràn ngang */
  background-color: #f8f9fa;
}
html {
  scroll-behavior: smooth; /* Cuộn mượt */
}
</style>