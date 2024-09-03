<script setup lang="ts"></script>

<template>
  <div class="footer">
    <div class="text-section">
      <p class="preview">Preview of Spotify</p>
      <p class="desc">
        Sign up to get unlimited songs and podcasts with occasional ads. No
        credit card needed.
      </p>
    </div>
    <button class="sign-btn">Sign up free</button>
  </div>
</template>

<style scoped>
.footer {
  position: fixed;
  bottom: 0;
  width: 97%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: white;
  background-image: linear-gradient(90deg, #af2896, #509bf5);
  padding: 7px 24px 9px 15px;
  margin-top: 7px;
  cursor: pointer;
  height: 60px;
}

.sign-btn {
  background-color: white;
  border: none;
  padding: 18px 38px;
  border-radius: 9999px;
  font-weight: 600;
  font-size: 15px;
}

.sign-btn:hover {
  transform: scale(1.03);
  cursor: pointer;
  background-color: #f0f0f0;
}

.text-section {
  display: flex;
  flex-direction: column;
  gap: 2px;
}

.preview {
  font-weight: 500;
  font-size: 15px;
}

.desc {
  font-weight: 400;
  font-size: 16px;
}

.footer p {
  margin: 0;
}
</style>
