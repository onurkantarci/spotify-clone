<script setup lang="ts"></script>

<template>
  <div class="main-content">
    <div class="header">
      <div class="arrows">
        <img
          class="left-arrow"
          src="/public/left-arrow-svgrepo-com.svg"
          alt=""
        />
        <img
          class="right-arrow"
          src="/public/left-arrow-svgrepo-com.svg"
          alt=""
        />
      </div>
      <div class="buttons">
        <button class="sign-up">Sign up</button>
        <button class="log-in">Log in</button>
      </div>
    </div>
    <div class="content">
      <div class="flex-header">
        <p class="popular">Popular artists</p>
        <p class="show-all">Show all</p>
      </div>
      <div class="flex-item-container">
        <div class="flex-item">
          <div class="image-container">
            <img
              src="/public/ab676161000051744f7f5c04098374eefedfc864.jpeg"
              alt=""
            />
            <button class="play-btn">▶</button>
          </div>
          <h3 class="artist-name">Semicenk</h3>
          <h4 class="artist">Artist</h4>
        </div>
        <div class="flex-item">
          <div class="image-container">
            <img src="/public/sezenaksu.jpeg" alt="" />
            <button class="play-btn">▶</button>
          </div>
          <h3 class="artist-name">Sezen Aksu</h3>
          <h4 class="artist">Artist</h4>
        </div>
        <div class="flex-item">
          <div class="image-container">
            <img src="/public/lblc5.jpeg" alt="" />
            <button class="play-btn">▶</button>
          </div>
          <h3 class="artist-name">Lvbel C5</h3>
          <h4 class="artist">Artist</h4>
        </div>
        <div class="flex-item">
          <div class="image-container">
            <img src="/public/hande.jpeg" alt="" />
            <button class="play-btn">▶</button>
          </div>
          <h3 class="artist-name">Hande Yener</h3>
          <h4 class="artist">Artist</h4>
        </div>
        <div class="flex-item">
          <div class="image-container">
            <img src="/public/simge.jpeg" alt="" />
            <button class="play-btn">▶</button>
          </div>
          <h3 class="artist-name">Simge</h3>
          <h4 class="artist">Artist</h4>
        </div>
        <div class="flex-item">
          <div class="image-container">
            <img src="/public/mabel.jpeg" alt="" />
            <button class="play-btn">▶</button>
          </div>
          <h3 class="artist-name">Mabel Matiz</h3>
          <h4 class="artist">Artist</h4>
        </div>
        <div class="flex-item">
          <div class="image-container">
            <img src="/public/gulsen.jpeg" alt="" />
            <button class="play-btn">▶</button>
          </div>
          <h3 class="artist-name">Gülşen</h3>
          <h4 class="artist">Artist</h4>
        </div>
      </div>
      <div class="flex-header">
        <p class="popular">Popular albums</p>
        <p class="show-all">Show all</p>
      </div>
      <div class="flex-album-container">
        <div class="flex-album">
          <div class="image-container">
            <img src="/public/geciyor.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h3 class="artist-name">Geçiyor Zaman</h3>
          <h4 class="artist">Semicenk</h4>
        </div>
        <div class="flex-album">
          <div class="image-container">
            <img src="/public/1.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h3 class="artist-name">#1</h3>
          <h4 class="artist">Lvbel C5</h4>
        </div>
        <div class="flex-album">
          <div class="image-container">
            <img src="/public/7edi.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h3 class="artist-name">7EDI</h3>
          <h4 class="artist">Era7capone</h4>
        </div>
        <div class="flex-album">
          <div class="image-container">
            <img src="/public/cistak.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h3 class="artist-name">CISTAK</h3>
          <h4 class="artist">Era7capone,Batuflex,Narco</h4>
        </div>
        <div class="flex-album">
          <div class="image-container">
            <img src="/public/simge.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h3 class="artist-name">Önümüz Yaz</h3>
          <h4 class="artist">Simge</h4>
        </div>
        <div class="flex-album">
          <div class="image-container">
            <img src="/public/kule.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h3 class="artist-name">Küle Dönmüşsün</h3>
          <h4 class="artist">Semicenk,Doğu Swag</h4>
        </div>
        <div class="flex-album">
          <div class="image-container">
            <img src="/public/dale.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h3 class="artist-name">Dale Don Dale</h3>
          <h4 class="artist">ElMusto</h4>
        </div>
      </div>
      <div class="flex-header">
        <p class="popular">Popular radio</p>
        <p class="show-all">Show all</p>
      </div>
      <div class="flex-radio-container">
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/sezenradio.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">With Sertab Erener,Göksel,Yıldız Tilbe and..</h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/melekradio.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            With Melek Mosso, Eda Baba, Ceylan Ertem and more
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/ahmetradio.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            With Kâzım Koyuncu, Selda Bağcan, Neşet Ertaş and more
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/semicenkradio.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            With Kubilay Karça, Burak Bulut, Doğu Swag and more
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/lvbelradio.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">With AKDO, Batuflex, cakal and more</h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/blokeradio.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">With Muti, AKDO, Lvbel C5 and more</h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/mabelradio.jpeg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">With Melike Şahin, KÖFN, Mehmet Erdem and more</h4>
        </div>
      </div>
      <div class="flex-header">
        <p class="popular">Featured Charts</p>
        <p class="show-all">Show all</p>
      </div>
      <div class="flex-radio-container">
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/region_global_default (2).jpg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            Your weekly update of the most played tracks right...
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/region_us_default (2).jpg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            Your weekly update of the most played tracks right...
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/region_global_default (1).jpg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            Your weekly update of the most played tracks right...
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/region_us_default (1).jpg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            Your weekly update of the most played tracks right...
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/region_global_default.jpg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            Your weekly update of the most viral tracks right...
          </h4>
        </div>
        <div class="flex-radio">
          <div class="image-container">
            <img src="/public/region_us_default.jpg" alt="" />
            <button class="play-btn-album">▶</button>
          </div>
          <h4 class="artist">
            Your weekly update of the most viral tracks right...
          </h4>
        </div>
      </div>
      <div class="content-footer">
        <div class="info-container">
          <p class="title">Company</p>
          <p>About</p>
          <p>Jobs</p>
          <p>For the Record</p>
        </div>
        <div class="info-container">
          <p class="title">Communities</p>
          <p>For Artists</p>
          <p>Developers</p>
          <p>Advertising</p>
          <p>Investors</p>
          <p>Vendors</p>
        </div>
        <div class="info-container">
          <p class="title">Useful links</p>
          <p>Support</p>
          <p>Free Mobile App</p>
        </div>
        <div class="info-container">
          <p class="title">Spotify Plans</p>
          <p>Premium Individual</p>
          <p>Premium Duo</p>
          <p>Premium Family</p>
          <p>Premium Student</p>
          <p>Spotify Free</p>
        </div>
        <div class="social-container">
          <img src="/public/instagram-svgrepo-com.svg" alt="" />
          <img src="/public/twitter-154-svgrepo-com.svg" alt="" />
          <img src="/public/facebook-svgrepo-com.svg" alt="" />
        </div>
      </div>
      <p class="copyright">© 2024 Spotify AB</p>
    </div>
  </div>
</template>

<style scoped>
* {
  color: white;
}

.content-footer p {
  color: #9c9b9b;
  font-weight: 500;
  font-size: 16px;
}

.content-footer p:hover {
  cursor: pointer;
  text-decoration: underline;
  color: #ffffff;
}

.title {
  color: white !important;
  text-decoration: none !important;
  cursor: text !important;
}

.social-container img {
  width: 20px;
  margin-left: 25px;
  background-color: #292929;
  padding: 10px;
  border-radius: 50%;
}

.copyright {
  color: #9c9b9b;
  padding-left: 20px;
  font-size: 14px;
  margin-top: 35px;
  margin-bottom: 60px;
}

.social-container img:hover {
  background-color: #727272;
}

.content-footer {
  display: flex;
  justify-content: space-between;
  padding: 8px 32px 40px 32px;
  margin-top: 40px;
  border-bottom: 1px solid #1e1e1e;
}

.buttons {
  display: flex;
  align-items: center;
  gap: 10px;
}

.sign-up {
  border: none;
  background-color: transparent;
  color: #aaaaaa;
  font-weight: 600;
  font-size: 15px;
}

.log-in {
  color: black;
  border: none;
  background-color: #ffffff;
  padding: 10px 24px 10px 24px;
  font-weight: 700;
  font-size: 16px;
  border-radius: 9999px;
}

.log-in:hover {
  cursor: pointer;
  transform: scale(1.05);
}

.sign-up:hover {
  color: #ffffff;
  transform: scale(1.05);
  cursor: pointer;
}

.arrows {
  display: flex;
  align-items: center;
  gap: 10px;
  cursor: not-allowed;
}

.left-arrow {
  background-color: #0a0a0a;
  border-radius: 50%;
  width: 30px;
}

.right-arrow {
  width: 30px;
  border-radius: 50%;
  background-color: #0a0a0a;
  transform: rotate(180deg);
}

.main-content {
  display: flex;
  flex-direction: column;
  height: 100%;
  overflow: hidden;
}

.header {
  display: flex;
  justify-content: space-between;
  height: 30px;
  position: fixed;
  border-top-left-radius: 8px;
  border-top-right-radius: 8px;
  background-color: #101010;
  padding: 1rem;
  width: 78.7%;
  z-index: 1;
}

.flex-item {
  padding: 7.9px;
  border-radius: 4px;
}

.flex-item:hover {
  cursor: pointer;
  background-color: #1f1f1f;
}

.flex-item-container {
  display: flex;
  align-items: center;
  padding-right: 0px;
  padding-left: 10px;
  flex-wrap: wrap;
  width: 100%;
  box-sizing: border-box;
  overflow: hidden;
  margin-bottom: 15px;
}

.flex-item h4 {
  margin: 0;
}

.flex-item h3 {
  margin-bottom: 5px;
  margin-top: 6px;
}

.image-container {
  position: relative;
}

.flex-item img {
  width: 201px;
  height: 201px;
  border-radius: 50%;
  object-fit: cover;
  display: block;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); /* Add shadow here */
}

.play-btn {
  background-color: #1ed760;
  border: none;
  padding-left: 10px;
  padding-bottom: 3px;
  font-size: 22px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  color: black;
  position: absolute;
  bottom: 5px;
  right: 5px;
  display: none;
  cursor: pointer;
}

.play-btn-album {
  background-color: #1ed760;
  border: none;
  padding-left: 10px;
  padding-bottom: 3px;
  font-size: 22px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  color: black;
  position: absolute;
  bottom: 10px;
  right: 5px;
  display: none;
  cursor: pointer;
}

.play-btn:hover {
  background-color: #3ae075 !important;
  width: 51px;
  height: 51px;
}

.play-btn-album:hover {
  background-color: #3ae075 !important;
  width: 51px;
  height: 51px;
}

@keyframes jump {
  0% {
    transform: translateY(0);
    opacity: 0;
  }
  100% {
    transform: translateY(-5px);
    opacity: 1;
  }
}

.flex-item:hover .play-btn {
  display: block;
  animation: jump 0.4s forwards;
}

.flex-album:hover .play-btn-album {
  display: block;
  animation: jump 0.4s forwards;
}

.flex-radio:hover .play-btn-album {
  display: block;
  animation: jump 0.4s forwards;
}

.artist-name {
  font-size: 15px;
  font-weight: 400;
}

.artist {
  font-size: 13px;
  font-weight: 300;
}

.flex-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0px 20px;
}

.show-all {
  color: #ababab;
  font-size: 14px;
  font-weight: 500;
}

.show-all:hover {
  text-decoration: underline;
  cursor: pointer;
}

.popular {
  margin-bottom: 5px;
  font-weight: 600;
  font-size: 22px;
}

.popular:hover {
  text-decoration: underline;
  cursor: pointer;
}

.flex-album-container {
  display: flex;
  align-items: center;
  padding-right: 0px;
  padding-left: 10px;
  flex-wrap: wrap;
  max-width: 100%;
  box-sizing: border-box;
  overflow: hidden;
  margin-bottom: 15px;
}

.flex-album img {
  width: 201px;
  height: 201px;
  border-radius: 6px;
  object-fit: cover;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

.flex-album h4 {
  margin: 0;
}

.flex-album h3 {
  margin-bottom: 5px;
  margin-top: 6px;
}

.flex-album {
  padding: 7.9px;
  border-radius: 4px;
}

.flex-album:hover {
  cursor: pointer;
  background-color: #1f1f1f;
}

.flex-radio-container {
  display: flex;
  align-items: center;
  padding-right: 0px;
  padding-left: 10px;
  flex-wrap: wrap;
  max-width: 100%;
  box-sizing: border-box;
  overflow: hidden;
  margin-bottom: 15px;
}

.flex-radio {
  padding: 7.9px;
  width: 201px;
  border-radius: 4px;
}

.flex-radio img {
  width: 201px;
  height: 201px;
  border-radius: 6px;
  object-fit: cover;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

.flex-radio h4 {
  margin: 0;
  margin-top: 6px;
  font-size: 13px;
  word-wrap: break-word;
  overflow-wrap: break-word;
  white-space: normal;
  color: #a8a9b2;
  font-weight: 400;
}

.flex-radio:hover {
  cursor: pointer;
  background-color: #1f1f1f;
}

.content {
  padding-top: 80px;
  background-image: linear-gradient(170deg, #1e1e1e, #000000);
  border-bottom-left-radius: 8px;
  border-bottom-right-radius: 8px;
  border-top-left-radius: 8px;
  border-top-right-radius: 8px;
  overflow-y: auto;
  height: 97%;
}

.content::-webkit-scrollbar {
  width: 14px;
}

.content::-webkit-scrollbar-thumb {
  background-color: #666;
  border: 3px solid #121212;
}

.content::-webkit-scrollbar-track {
  background: transparent;
  border-radius: 8px;
}

.content::-webkit-scrollbar-thumb {
  background: linear-gradient(45deg, #5a5a5a, #5a5a5a);
  transition: background-color 300ms;
}

.content::-webkit-scrollbar-thumb:hover {
  background: linear-gradient(45deg, #898989, #898989);
  width: 12px;
}

.main-content::-webkit-scrollbar-thumb:active {
  background: linear-gradient(45deg, #9e9d9d, #9e9d9d);
}
</style>
