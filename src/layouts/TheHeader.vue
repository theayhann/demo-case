<template>
  <div>
    <div class="navbar navbar-expand-lg navbar-light w-100">

        <h2 class="text-white">LOGO</h2>

        <button class="d-lg-none btn" data-toggle="collapse" data-target="#headerShow" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <i class="fas fa-align-justify"></i>
        </button>

      <div class="collapse navbar-collapse" id="headerShow">
        <div class="navbar-nav navbar-nav-left custom-border mr-auto">
          <div class="navbar-item">
            <h6>Menu 1</h6>
          </div>

          <div class="navbar-item">
            <h6>Menu 2</h6>
          </div>

          <div class="navbar-item">
            <div class="btn-group  select-language">
              <h6 data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">TR <i class="fas fa-chevron-down"></i></h6>
              <div class="dropdown-menu custom-border">
                <h6 class="dropdown-item">Ar</h6>
                <h6 class="dropdown-item">Tr</h6>
                <h6 class="dropdown-item">Fr</h6>
              </div>
            </div>


          </div>

        </div>

        <div class="navbar-nav navbar-nav-right custom-border">
          <h6>Sign In</h6>
        </div>

      </div>

    </div>
  </div>
</template>


<style scoped>

.navbar {
  position: absolute;
   padding: 50px 130px 0 250px;
}

.custom-border {
  border: 2px solid;
  border-top-color: #43A2B0;
  border-bottom-color: #988BBE;
  border-right-color: #81A1CB;
  border-left-color: #81A1CB;
}

.navbar-nav {
  background: rgba(255, 255, 255, 0.16);
  min-height: 50px;
  display: flex;
  align-items: center;
  border-radius: 10px;
  margin-left: 50px;
  padding: 0 15px 0 15px;

  font-weight: bold;
  color: white;
  cursor: pointer;
}

.navbar-nav-left {
  min-width: 300px;
  justify-content: space-between;
}

@media screen and (max-width: 990px) {
  .navbar {
    padding: 50px;
  }

  .navbar-nav-left {
    min-width: 200px;
  }
}

.navbar-nav-right {
  min-width: 120px;
  justify-content: center;
}

.navbar-item:hover {
  height: 40px;
  display: flex;
  align-items: center;
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
</style>
