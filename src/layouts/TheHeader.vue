<template>
  <div>
    <div class="header">
      <div class="header-left">

        <div>
          <h2>LOGO</h2>
        </div>

        <div class="d-none d-md-block">
          <div class="header-left__menu custom-border">
            <div>
              <h6>Menu 1</h6>
            </div>

            <div>
              <h6>Menu 2</h6>
            </div>

            <div>
              <h6 data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">TR <i class="fas fa-chevron-down"></i></h6>
              <div class="dropdown-menu custom-border">
                <h6 class="dropdown-item">Ar</h6>
                <h6 class="dropdown-item">Tr</h6>
                <h6 class="dropdown-item">Fr</h6>
              </div>
            </div>
          </div>
        </div>
      </div>

     <div class="d-none d-md-block">
       <div class="header-right custom-border">
         <h6>Sign In</h6>
       </div>
     </div>

      <div class="d-md-none d-block">
        <h2><i class="fas fa-bars text-white" @click="leftBar = !leftBar"></i></h2>
      </div>
    </div>

    <div v-if="leftBar">
      <the-left-bar />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      leftBar: false,
    };
  },
  components: {
    TheLeftBar: () => import('@/layouts/TheLeftBar.vue'),
  },
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  position: absolute;
  padding: 50px 50px 0 50px;
}


.header-left {
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}

.header-left__menu {
  background: rgba(255, 255, 255, 0.16);
  min-height: 50px;
  min-width: 250px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-radius: 10px;
  margin-left: 50px;
  padding: 0 15px 0 15px;


  font-weight: bold;
  color: white;
  cursor: pointer;
}

.header-right {
  background: rgba(255, 255, 255, 0.16);
  min-height: 50px;
  min-width: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 10px;
  margin-left: 50px;
  padding: 0 15px 0 15px;


  font-weight: bold;
  color: white;
  cursor: pointer;
}

.dropdown-menu {
  background: rgba(255, 255, 255, 0.16);
  position: absolute;
  border-radius: 10px;

  width: 10px !important;
  text-align: center;
}

.dropdown-item{
  color: white;
}

.dropdown-item:hover {
  background: rgba(255, 255, 255, 0.16);
}


.custom-border {
  border: 2px solid;
  border-top-color: #43A2B0;
  border-bottom-color: #988BBE;
  border-right-color: #81A1CB;
  border-left-color: #81A1CB;
}
</style>
