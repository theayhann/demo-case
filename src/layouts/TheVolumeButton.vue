<template>
  <div class="volume-button custom-border">
    <i class="fas fa-volume-up"></i>
  </div>
</template>


<style scoped>
.volume-button {
  background: rgba(255, 255, 255, 0.16);

  position: absolute;
  width: 41.64px;
  height: 41.64px;
  right: 150px;
  top: 190px;
  font-size: 16px;
  border-radius: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  cursor: pointer;
}

.custom-border {
  border: 2px solid;
  border-top-color: #43A2B0;
  border-bottom-color: #988BBE;
  border-right-color: #81A1CB;
  border-left-color: #81A1CB;
}

@media screen and (max-width: 990px) {
  .volume-button {
    right: 50px;
    top: 190px;
  }

}
</style>
