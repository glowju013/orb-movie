<script setup lang="ts"></script>

<template>
  <div class="page">
    <h1>Orb movie</h1>
    <button class="primary-btn">리뷰 쓰기</button>
    <button class="primary-btn">리뷰 보기</button>
  </div>
</template>

<style scoped>
.page {
  background-color: #111;
  color: #eee;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.primary-btn {
   width: min(90%, 418px);
  height: 100px;
  background: #eee;
  border: none;
  font-size: 20px;
  color: #000;
  margin-top: 24px;
  cursor: pointer;
}
</style>
