<template>
  <div>
    <div class="category-top"></div>
    <div class="category text-white">

      <!-- Top content -->
      <div class="top-content">
        <div class="container-fluid">
          <div id="carousel-example" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner d-flex justify-content-center flex-row" role="listbox">

              <div class="carousel-item col-12 col-sm-6 col-md-4 col-lg-3 active">
                <div class="img-fluid mx-auto d-block">
                  <div class="item clearfix">
                    <div>
                      <img class="item-picture" src="/assets/images/videos-pic.png" alt="videos">
                    </div>
                    <div class="item-text">
                      <b>Brave New World</b>
                      <small class="item-date">2018 . 1h 23m</small>
                    </div>
                    <div class="item-mouseover-bottom">
                      <div>
                        <button class="item-mouseover-buttons"><i class="far fa-heart"></i></button>
                        <button class="item-mouseover-buttons item-mouseover-button-play"><i class="fab fa-google-play"></i></button>
                        <button class="item-mouseover-buttons"><i class="fas fa-heart-broken"></i></button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="carousel-item col-12 col-sm-6 col-md-4 col-lg-3">
                <div class="img-fluid mx-auto d-block">
                  <div class="item clearfix">
                    <div>
                      <img class="item-picture" src="/assets/images/videos-pic.png" alt="videos">
                    </div>
                    <div class="item-text">
                      <b>Vanguard</b>
                      <small class="item-date">2018 . 1h 23m</small>
                    </div>
                    <div class="item-mouseover-bottom">
                      <div>
                        <button class="item-mouseover-buttons"><i class="far fa-heart"></i></button>
                        <button class="item-mouseover-buttons item-mouseover-button-play"><i class="fab fa-google-play"></i></button>
                        <button class="item-mouseover-buttons"><i class="fas fa-heart-broken"></i></button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="carousel-item col-12 col-sm-6 col-md-4 col-lg-3">
                <div class="img-fluid mx-auto d-block">
                  <div class="item clearfix">
                    <div>
                      <img class="item-picture" src="/assets/images/videos-pic.png" alt="videos">
                    </div>
                    <div class="item-text">
                      <b>Bad Times At The El Royale</b>
                      <small class="item-date">2018 . 1h 23m</small>
                    </div>
                    <div class="item-mouseover-bottom">
                      <div>
                        <button class="item-mouseover-buttons"><i class="far fa-heart"></i></button>
                        <button class="item-mouseover-buttons item-mouseover-button-play"><i class="fab fa-google-play"></i></button>
                        <button class="item-mouseover-buttons"><i class="fas fa-heart-broken"></i></button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="carousel-item col-12 col-sm-6 col-md-4 col-lg-3">
                <div class="img-fluid mx-auto d-block">
                  <div class="item clearfix">
                    <div>
                      <img class="item-picture" src="/assets/images/videos-pic.png" alt="videos">
                    </div>
                    <div class="item-text">
                      <b>John Wick 3 Parabellum</b>
                      <small class="item-date">2018 . 1h 23m</small>
                    </div>
                    <div class="item-mouseover-bottom">
                      <div>
                        <button class="item-mouseover-buttons"><i class="far fa-heart"></i></button>
                        <button class="item-mouseover-buttons item-mouseover-button-play"><i class="fab fa-google-play"></i></button>
                        <button class="item-mouseover-buttons"><i class="fas fa-heart-broken"></i></button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="carousel-item col-12 col-sm-6 col-md-4 col-lg-3">
                <div class="img-fluid mx-auto d-block">
                  <div class="item clearfix">
                    <div>
                      <img class="item-picture" src="/assets/images/videos-pic.png" alt="videos">
                    </div>
                    <div class="item-text">
                      <b>John Wick 3 Parabellum</b>
                      <small class="item-date">2018 . 1h 23m</small>
                    </div>
                    <div class="item-mouseover-bottom">
                      <div>
                        <button class="item-mouseover-buttons"><i class="far fa-heart"></i></button>
                        <button class="item-mouseover-buttons item-mouseover-button-play"><i class="fab fa-google-play"></i></button>
                        <button class="item-mouseover-buttons"><i class="fas fa-heart-broken"></i></button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

            </div>

            <a class="carousel-control-next" href="#carousel-example" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>


<style scoped>

.category-top {
  position: absolute;
  width: 100%;
  height: 100px;
  top: 250px;
  background: linear-gradient(179.83deg, #1F1F1F 0.14%, rgba(34, 34, 34, 0.369792) 62.97%, rgba(34, 34, 34, 0) 99.84%);
  transform: matrix(1, 0, 0, -1, 0, 0);
}

.category {
  background-color: #1f1f1f;
  bottom: 0;
  min-height: 504px;
  width: 100%;
  padding: 10px 20px 10px 20px;
}

.carousel-inner {
  padding: 50px 0 50px 0;
}


.item {
  width: 300px;
  height: 352px;
  transition: 0.5s;
  border-radius: 6px;
}

.item:hover {
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

.item-picture {
  width: 297px;
  height: 170px;
  transition: 0.5s;
  cursor: pointer;
}


.item-text {
  color: white;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.item-mouseover-bottom {
  visibility: hidden;
  padding-top: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.item-date {
  visibility: hidden;
}

.item:hover .item-date {
  visibility: visible;
}

.item:hover .item-mouseover-bottom {
  visibility: visible;
}


.item-mouseover-buttons {
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


.item-mouseover-button-play {
  width: 42px;
  height: 42px;
  background: radial-gradient(100% 100% at 0% 0%, #0CF9F0 0%, #D686FF 100%);
  box-shadow: inset -2.53935px -2.53935px 126.967px rgba(255, 255, 255, 0.02);
  backdrop-filter: blur(10.5px);

  border-radius: 42px;
}

.carousel-control-next {
  position: absolute;
  width: 76px;
  height: 73px;
  left: auto;
  top: 150px;
  font-size: 36px;
  border-radius: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  background: rgba(0, 0, 0, 0.7);
}



@media (min-width: 768px) and (max-width: 991px) {
  /* Show 4th slide on md if col-md-4*/
  .carousel-inner .active.col-md-4.carousel-item + .carousel-item + .carousel-item + .carousel-item {
    position: absolute;
    top: 0;
    right: -33.3333%;  /*change this with javascript in the future*/
    z-index: -1;
    display: block;
    visibility: visible;
  }

  .item-picture {
    height: 95px;
    width: 165px;
  }

  .item {
    width: 167px;
    height: 300px;
    transition: 0.5s;
    border-radius: 6px;
  }


}
@media (min-width: 576px) and (max-width: 768px) {
  /* Show 3rd slide on sm if col-sm-6*/
  .carousel-inner .active.col-sm-6.carousel-item + .carousel-item + .carousel-item {

    top: 0;
    right: -50%;  /*change this with javascript in the future*/
    z-index: -1;
    display: block;
    visibility: visible;
  }

  .item-picture {
    height: 95px;
    width: 165px;
  }

  .item {
    width: 167px;
    height: 300px;
    transition: 0.5s;
    border-radius: 6px;
  }
}
@media (min-width: 576px) {
  .carousel-item {
    margin-right: 0;
  }
  /* show 2 items */
  .carousel-inner .active + .carousel-item {
    display: block;
  }
  .carousel-inner .carousel-item.active:not(.carousel-item-right):not(.carousel-item-left),
  .carousel-inner .carousel-item.active:not(.carousel-item-right):not(.carousel-item-left) + .carousel-item {
    transition: none;
  }
  .carousel-inner .carousel-item-next {
    position: relative;
    transform: translate3d(0, 0, 0);
  }
  /* left or forward direction */
  .active.carousel-item-left + .carousel-item-next.carousel-item-left,
  .carousel-item-next.carousel-item-left + .carousel-item,
  .carousel-item-next.carousel-item-left + .carousel-item + .carousel-item {
    position: relative;
    transform: translate3d(-100%, 0, 0);
    visibility: visible;
  }
  /* farthest right hidden item must be also positioned for animations */
  .carousel-inner .carousel-item-prev.carousel-item-right {
    top: 0;
    left: 0;
    z-index: -1;
    display: block;
    visibility: visible;
  }
  /* right or prev direction */
  .active.carousel-item-right + .carousel-item-prev.carousel-item-right,
  .carousel-item-prev.carousel-item-right + .carousel-item,
  .carousel-item-prev.carousel-item-right + .carousel-item + .carousel-item {
    position: relative;
    transform: translate3d(100%, 0, 0);
    visibility: visible;
    display: block;
    visibility: visible;
  }
}
/* MD */
@media (min-width: 768px) {
  /* show 3rd of 3 item slide */
  .carousel-inner .active + .carousel-item + .carousel-item {
    display: block;
  }
  .carousel-inner .carousel-item.active:not(.carousel-item-right):not(.carousel-item-left) + .carousel-item + .carousel-item {
    transition: none;
  }
  .carousel-inner .carousel-item-next {
    position: relative;
    transform: translate3d(0, 0, 0);
  }
  /* left or forward direction */
  .carousel-item-next.carousel-item-left + .carousel-item + .carousel-item + .carousel-item {
    position: relative;
    transform: translate3d(-100%, 0, 0);
    visibility: visible;
  }
  /* right or prev direction */
  .carousel-item-prev.carousel-item-right + .carousel-item + .carousel-item + .carousel-item {
    position: relative;
    transform: translate3d(100%, 0, 0);
    visibility: visible;
    display: block;
    visibility: visible;
  }


}

@media (max-width: 380px) {
  .item-picture {
    height: 110px;
    width: 165px;
  }

  .item {
    width: 167px;
    height: 300px;
    transition: 0.5s;
    border-radius: 6px;
  }
}
</style>
