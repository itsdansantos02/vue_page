

<template>
  <div>
    <div class="nav-burger" id="nav-burger" style="padding: 0;">
      <div class="nav-burger-container">
        <div class="burger">
          <i class='bx bx-menu' @click="openNav()"></i>
        </div>
        <div class="nav-burger-group" style="padding: 0;">
          <div class="title-img-center" style="padding-top: 70px;">
            <div class="title-img"></div>
          </div>
          <br>
          <div class="title-name">DANILO SANTOS</div>
          <br>
          <router-link @click="openNav()"  to="/">
            <div class="nav-burger-item"><i class='bx bx-home-alt'></i><span>Home</span></div>
          </router-link>
          <router-link @click="openNav()"  to="/project">
            <div class="nav-burger-item"><i class='bx bx-folder'></i><span>Projects</span></div>
          </router-link>
          <router-link @click="openNav()"  to="/about">
            <div class="nav-burger-item"><i class='bx bx-user'></i><span>About</span></div>
          </router-link>
          <a href="https://www.linkedin.com/in/itsdansantos" target="_blank">
            <div class="nav-burger-item"><i class='bx bx-phone'></i><span>Contact</span></div>
          </a>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row">
        <div class="nav" style="padding: 0;">
          <div class="nav-container">
            <div class="nav-group">
              <div class="title-img-center">
                <div class="title-img"></div>
              </div>
              <div class="title-name">DANILO SANTOS</div>
              <br>
              <router-link to="/" >
                <div class="nav-item"><i class='bx bx-home-alt'></i><span>Home</span></div>
              </router-link>
              <router-link to="/project">
                <div class="nav-item"><i class='bx bx-folder'></i><span>Projects</span></div>
              </router-link>
              <router-link to="/about">
                <div class="nav-item"><i class='bx bx-user'></i><span>About</span></div>
              </router-link>
              <a href="https://www.linkedin.com/in/itsdansantos" target="_blank">
                <div class="nav-item"><i class='bx bx-phone'></i><span>Contact</span></div>
              </a>
            </div>
          </div>
        </div>
        <div class="Rview">
          <div >
            <div class="main">
              <div class="burger-main" style="text-align: left;margin-bottom: -63px;">
                <i class='bx bx-menu' @click="openNav()"></i>
              </div>
              <RouterView />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { ref } from 'vue'
import { RouterLink, RouterView } from 'vue-router'
import 'boxicons'

export default {
  methods: {
    openNav() {
      var myDiv = document.getElementById("nav-burger");
      if (myDiv.style.left === "-110%" || myDiv.style.left === "") {
        myDiv.style.left = "0";
      } else {
        myDiv.style.left = "-110%";
      }
    },
  }
}

</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Kalam:wght@300;400;700&family=Open+Sans:wght@300;400;500;700&family=PT+Sans:wght@400;700&family=Roboto:wght@100;300;400;700&family=Rubik:wght@300;400;500;700&display=swap');

/* 
font-family: 'Bebas Neue', sans-serif;
font-family: 'Kalam', cursive;
font-family: 'Open Sans', sans-serif;
font-family: 'Roboto', sans-serif;
font-family: 'Rubik', sans-serif; 
*/
* {
  color: white;
}

.burger {
  width: 100%;
  text-align: right;
  justify-content: right;
  margin-top: 10px;
}

.burger i {
  text-align: right;
  cursor: pointer;
  font-size: 55px;
}

.burger i:hover {
  color: white;
}
.burger-main {
  width: 100%;
  text-align: right;
  justify-content: right;
  margin-top: 10px;
  display: none;
}

.burger-main i {
  text-align: right;
  cursor: pointer;
  font-size: 55px;
}

.burger-main i:hover {
  color: white;
}

.wrapper {
  height: 100vh;
}

.container-fluid {
  z-index: 0;
}

.row {
  display: grid;
  grid-template-columns: 350px 1fr;
}

/* Start Navigation */
.nav {
  height: 100vh;
  /* background-color: #171821; */
  background-color: #111111;
}


.title-img {
  width: 130px;
  height: 130px;
  background-image: url('../src/assets/me.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  border-radius: 50%;
  border: 2px solid white;
  margin: auto;
}

.title-img-center {}

.title-name {
  margin-top: 5px;
  text-align: center;
  font-size: 27px;
  font-weight: 700;
  font-family: 'PT Sans', sans-serif;
  color: rgb(255, 255, 255, 1);
}

.nav-container {
  width: 100%;
}

.nav-group {
  padding: 25% 20%;
}

.nav-item {
  margin-top: 15%;
  margin-bottom: 35px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 18px;
  text-align: left;
  display: flex;
  color: rgb(255, 255, 255, .1);
}

.nav-item span {
  margin-left: 15px;
  color: rgb(255, 255, 255, .6);
}

/* End Navigation */
.Rview {
  /* background-color: rgba(21, 21, 21, 255); */
  background-color: #171821;
  box-shadow: inset 35px 0px 10px -30px #171821;
  overflow: auto;
  height: 100vh;

}

.bx {
  font-size: 25px;
  font-family: Arial, Helvetica, sans-serif;
  margin-top: -1px;
  color: rgb(255, 255, 255, .6);
}

.nav-group a {
  text-decoration: none;
}

.nav-item:hover .bx,
.nav-item:hover span {
  color: rgb(255, 255, 255);
  transition: 0.3s;
}

.nav-item:hover span {
  text-decoration: underline;
  transition: 0.3s;
}

/* .nav-item:hover.bx,.bx:hover,.nav-item span:hover{
  color: rgb(255, 255, 255,1);
  text-decoration: underline;
  transition: 0.3s;
} */
/* 
.nav-item:hover,.bx:hover,.nav-item span:hover{
  color: rgb(255, 255, 255,1);
  transition: 0.3s;
} */


.nav-burger {
  z-index: 10;
  position: absolute;
  height: 100vh;
  width: 100%;
  background-color: #111111;
  left: -110%;
  transition: .8s ease;
  overflow: auto;
}

.nav-burger-container {
  height: 100vh;
}

.nav-burger-item {
  margin: auto;
  margin-top: 25px;
  margin-bottom: 35px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 18px;
  width: 9%;
  text-align: left;
  display: flex;
  color: rgb(255, 255, 255, .1);

}

.nav-burger-item span {
  margin-left: 15px;
  color: rgb(255, 255, 255, .6);
}

.nav-burger-group a {
  text-decoration: none;
}

.nav-burger-item:hover .bx,
.nav-burger-item:hover span {
  color: rgb(255, 255, 255);
  transition: 0.3s;
}

.nav-burger-item:hover span {
  text-decoration: underline;
  transition: 0.3s;
}
/* MEDIA */
@media screen and (max-width: 1248px) {
  .burger-main{
    display: block;
  }
  .row{
    grid-template-columns: 1fr;
  }
  .nav{
    display: none;
  }
}
@media screen and (max-width: 952px) {
  .Rview{
    padding: 0;
  }
}
</style>
