<template>
  <div>
    <div class="select-videos-top"></div>
    <div class="select-videos">

      <div class="d-flex justify-content-start align-items center container">


        <div class="videos">
          <div>
            <img class="videos-picture" src="/assets/images/videos-pic.png" alt="videos">
          </div>
          <div class="videos-text">
            <b>Brave New World</b>
            <small class="video-date">2018 . 1h 23m</small>
          </div>
          <div class="video-mouseover-bottom">
            <div>
              <button class="video-mouseover-buttons"><i class="far fa-heart"></i></button>
              <button class="video-mouseover-buttons video-mouseover-button-play"><i class="fab fa-google-play"></i></button>
              <button class="video-mouseover-buttons"><i class="fas fa-heart-broken"></i></button>
            </div>
          </div>
        </div>

        <div class="videos">
          <div>
            <img class="videos-picture" src="/assets/images/videos-pic.png" alt="videos">
          </div>
          <div class="videos-text">
            <b>Vanguard</b>
            <small class="video-date">2018 . 1h 23m</small>
          </div>
          <div class="video-mouseover-bottom">
            <div>
              <button class="video-mouseover-buttons"><i class="far fa-heart"></i></button>
              <button class="video-mouseover-buttons video-mouseover-button-play"><i class="fab fa-google-play"></i></button>
              <button class="video-mouseover-buttons"><i class="fas fa-heart-broken"></i></button>
            </div>
          </div>
        </div>


      </div>
    </div>
  </div>

</template>

<script>
export default {
  data() {
    return {
      active: false
    };
  },
};
</script>

<style scoped>
.select-videos-top {
  position: absolute;
  width: 100%;
  height: 92px;
  top: 270px;
  background: linear-gradient(179.83deg, #1F1F1F 0.14%, rgba(34, 34, 34, 0.369792) 62.97%, rgba(34, 34, 34, 0) 99.84%);
  transform: matrix(1, 0, 0, -1, 0, 0);
}

.select-videos {
  background-color: #1f1f1f;
  bottom: 0;
  min-height: 510px;
  width: 100%;
  position: absolute;
  padding: 10px 20px 10px 20px;
  overflow-x: scroll
}

.videos {
  margin: 0 10px 0 10px;
  width: 297px;
  height: 352px;
  transition: 0.5s;
  border-radius: 6px;
}

.videos:hover {
  transition: 0.5s;
  transform: scale(1.1);

  background: radial-gradient(100% 100% at 0% 0%, rgba(255, 255, 255, 0.4) 0%, rgba(255, 255, 255, 0) 100%);
  box-shadow: inset -2.24404px -2.24404px 112.202px rgba(255, 255, 255, 0.02);
  border-radius: 12px;


  border: 1px solid;

  border-top-color: #43A2B0;
  border-bottom-color: #988BBE;
  border-right-color: #81A1CB;
  border-left-color: #81A1CB;
}

.videos-picture {
  width: 297px;
  height: 170px;
  left: 124px;
  top: 352px;
  transition: 0.5s;
  cursor: pointer;
}

.videos-text {
  color: white;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.video-mouseover-bottom {
  visibility: hidden;
  padding-top: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.video-date {
  visibility: hidden;
}

.videos:hover .video-date {
  visibility: visible;
}

.videos:hover .video-mouseover-bottom {
  visibility: visible;
}


.video-mouseover-buttons {
  margin: 0 3px 0 3px ;
  width: 34px;
  height: 34px;
  color: white;
  border: 1px solid;

  border-top-color: #43A2B0;
  border-bottom-color: #988BBE;
  border-right-color: #81A1CB;
  border-left-color: #81A1CB;

  background: radial-gradient(100% 100% at 0% 0%, rgba(255, 255, 255, 0.4) 0%, rgba(255, 255, 255, 0) 100%);
  box-shadow: inset -2.06203px -2.06203px 103.101px rgba(255, 255, 255, 0.02);
  backdrop-filter: blur(8.52631px);

  border-radius: 34px;
  cursor: pointer;
}


.video-mouseover-button-play {
  width: 42px;
  height: 42px;
  background: radial-gradient(100% 100% at 0% 0%, #0CF9F0 0%, #D686FF 100%);
  box-shadow: inset -2.53935px -2.53935px 126.967px rgba(255, 255, 255, 0.02);
  backdrop-filter: blur(10.5px);

  border-radius: 42px;
}
</style>
