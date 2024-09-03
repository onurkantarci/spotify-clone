<script setup lang="ts"></script>

<template>
  <div class="sidebar-container">
    <div class="sidebar-top">
      <div class="spotify-logo">
        <img src="/public/spotify-svgrepo-com.svg" alt="spotify" />
        <h1>Spotify</h1>
      </div>
      <ul class="routes">
        <div class="home">
          <img class="home-svg" src="/public/home-svgrepo-com.svg" alt="home" />
          <li class="home-route">Home</li>
        </div>
        <div class="search">
          <img
            class="search-svg"
            src="/public/search-svgrepo-com.svg"
            alt="home"
          />
          <li class="search-route">Search</li>
        </div>
      </ul>
    </div>
    <div class="sidebar-content">
      <div class="space-1">
        <div class="content-header">
          <div class="logo-library">
            <img
              class="library-svg"
              src="/public/library-svgrepo-com.svg"
              alt=""
            />
            <h2>Your Library</h2>
          </div>
          <h1>+</h1>
        </div>
        <div class="scrollable-content">
          <div class="content">
            <p class="create">Create your first playlist</p>
            <p class="easy">It's easy, we'll help you</p>
            <button>Create playlist</button>
          </div>
          <div class="content">
            <p class="create">Let's find some podcasts to follow</p>
            <p class="easy">We'll keep you updated on new episodes</p>
            <button>Browse podcasts</button>
          </div>
        </div>
      </div>
      <div class="space-2">
        <div class="content-footer">
          <p>Legal</p>
          <p>Safety&Privacy Center</p>
          <p>Privacy Policy</p>
          <p>Cookie Settings</p>
          <p>About Ads</p>
          <p>Accessibility</p>
          <p class="cookies">Cookies</p>
        </div>
        <div class="lang-btn">
          <img class="globe-img" src="/public/globe-svgrepo-com.svg" alt="" />
          <p>English</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.content-footer {
  display: flex;
  flex-wrap: wrap;
  width: 250px;
  color: #b3b3b3;
  font-size: 12px;
  margin: 0;
  padding: 0px 24px;
  margin-top: 32px;
  margin-bottom: 32px;
  gap: 10px;
}

.cookies:hover {
  text-decoration: underline;
}

.lang-btn {
  display: flex;
  align-items: center;
  width: 70px;
  height: 18px;
  margin-left: 20px;
  margin-bottom: 32px;
  padding: 4px 8px;
  padding-right: 0px;
  font-size: 12px;
  gap: 3px;
  color: #ffffff;
  background-color: transparent;
  border: 0.8px solid grey;
  border-radius: 16px;
  font-weight: 500;
}

.lang-btn:hover {
  cursor: pointer;
  border-color: rgb(255, 255, 255);
  transform: scale(1.03);
}

.lang-btn img,
p {
  margin: 0;
}

.globe-img {
  width: 18px;
}

.content-footer p {
  margin: 0;
  cursor: pointer;
}

.content {
  display: flex;
  flex-direction: column;
  gap: 8px;
  background-color: #1f1f1f;
  padding: 16px 20px;
  border-radius: 8px;
  margin-top: 0px;
  margin-bottom: 8px;
}

.content button {
  width: 130px;
  border-radius: 50px;
  padding: 8px 12px;
  font-size: 12px;
  border: none;
  margin-top: 8px;
  font-weight: 600;
  cursor: pointer;
}

.content button:hover {
  transform: scale(1.04);
  background-color: #f0f0f0;
}

.content p {
  margin: 0;
}

.create {
  font-weight: 600;
  font-size: 14px;
}

.easy {
  font-size: 12px;
}

.search,
.home {
  display: flex;
  align-items: center;
  gap: 20px;
  padding: 4px 12px;
  cursor: pointer;
  transition: color 300ms;
}

.search {
  color: #b3b3b3;
}

.search:hover {
  color: white;
}

.search-svg {
  width: 20px;
}

.search-svg {
  filter: brightness(0) saturate(100%) invert(74%) sepia(0%) saturate(1%)
    hue-rotate(247deg) brightness(91%) contrast(88%);
  transition: filter 300ms;
}

.search:hover .search-svg {
  filter: brightness(0) saturate(100%) invert(100%) sepia(0%) saturate(1%)
    hue-rotate(360deg) brightness(100%) contrast(100%);
}

.home-svg {
  width: 20px;
}

.sidebar-container {
  position: fixed;
  display: flex;
  flex-direction: column;
  gap: 6px;
  width: 352px;
}

.content-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #b3b3b3;
  max-height: 72px;
  padding: 8px 16px;
  height: 40px;
}

.content-header h1 {
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: 300;
  font-size: 24px;
  width: 25px;
  height: 25px;
  margin: 0;
  cursor: pointer;
  transition: background-color, color 200ms;
}

.content-header h1:hover {
  background-color: #1f1f1f;
  border-radius: 50%;
  color: #ececec;
}

.logo-library {
  display: flex;
  font-size: 10px;
  gap: 8px;
  padding: 4px 8px;
  transition: color 200ms;
  cursor: pointer;
}

.logo-library img {
  width: 20px;
}

.logo-library:hover {
  color: #ececec;
}

.library-svg {
  filter: brightness(0) saturate(100%) invert(74%) sepia(0%) saturate(1%)
    hue-rotate(247deg) brightness(91%) contrast(88%);
  transition: filter 300ms;
}

.logo-library:hover .library-svg {
  filter: brightness(0) saturate(100%) invert(100%) sepia(0%) saturate(1%)
    hue-rotate(360deg) brightness(100%) contrast(100%);
}

.sidebar-content {
  background-color: #121212;
  border-radius: 8px;
  height: 75vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.scrollable-content {
  overflow-y: auto;
  flex-grow: 1;
  color: white;
  padding: 8px 8px;
  max-height: calc(33vh - 40px - 16px);
}

.scrollable-content::-webkit-scrollbar {
  width: 10px;
}

.scrollable-content::-webkit-scrollbar-track {
  background: transparent;
  border-radius: 8px;
}

.scrollable-content::-webkit-scrollbar-thumb {
  background: linear-gradient(45deg, #5a5a5a, #5a5a5a);
  transition: background-color 300ms;
}

.scrollable-content::-webkit-scrollbar-thumb:hover {
  background: linear-gradient(45deg, #898989, #898989);
  width: 12px;
}

.scrollable-content::-webkit-scrollbar-thumb:active {
  background: linear-gradient(45deg, #9e9d9d, #9e9d9d);
}

.sidebar-top {
  background-color: #121212;
  border-radius: 8px;
  max-height: 156px;
  padding-bottom: 8px;
}

.routes {
  display: flex;
  flex-direction: column;
  list-style: none;
  color: white;
  font-weight: 500;
  padding: 8px 12px;
  font-size: 14px;
  margin: 0;
  gap: 8px;
}

.spotify-logo {
  color: white;
  display: flex;
  align-items: center;
  font-size: 10px;
  padding-left: 24px;
  padding-right: 24px;
  bottom: 0;
  height: 24px;
  margin-top: 20px;
  margin-bottom: 8px;
  width: 88px;
  gap: 4px;
  cursor: pointer;
}

.spotify-logo h1 {
  font-size: 16px;
  font-weight: 600;
}

.spotify-logo img {
  width: 22px;
}
</style>
