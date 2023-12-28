
<template>
  <div class="container">
    <div class="title">
      <h1>Web/Software Development</h1>
      <h4>Danilo C. Santos Jr.</h4>
    </div>
    <div class="row">
      <div class="left">
        <div class="card" id="toContact">
          <h3>Your Vision, Our Code: Excellence</h3>
          <p>
            An aspiring full-stack web developer excels in designing visually appealing and responsive websites. With a
            collaborative mindset and attention to detail.
          </p>
          <a href="">Get in touch</a>
        </div>
      </div>
      <div class="right minicard">
        <div class="small-card" id="mini-cards">
          <h1>3</h1>
          <p>Completed Projects</p>
        </div>
        <div class="small-card" id="mini-cards">
          <h2>Fresh</h2>
          <h2>Graduate</h2>
        </div>
        <div class="small-card" id="mini-cards">
          <h1>BSIT</h1>
        </div>
        <div class="small-card" id="mini-cards">
          <h1>4</h1>
          <p>Programming Languages</p>
        </div>
      </div>
    </div>
    <div class="row" id="row2">
      <div class="card" id="card2">
        <h1>Featured Projects</h1>
        <a href="">See All</a>
        <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/shirs-2.png" class="d-block w-100" alt="../assets/shirs-2.png">
            </div>
            <div class="carousel-item">
              <img src="../assets/shirs-3.png" class="d-block w-100" alt="../assets/shirs-3.png">
            </div>
            <div class="carousel-item">
              <img src="../assets/shirs-4.png" class="d-block w-100" alt="../assets/shirs-4.png">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
    <br>
    <br><br>
  </div>
</template>

<script setup>
</script>

<style scoped>
.container {
  width: 100%;
}

.title {
  padding: 8% 3% 0 3%;
}

.title h1 {
  font-size: 60px;
}

.whole {
  padding: 0;
}

.row .left {
  padding: 0;
}

.row {
  padding: 3% 3% 0 3%;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px;
}

#row2 {
  display: grid;
  grid-template-columns: repeat(1, 1fr);
  gap: 10px;
}

.card {
  /* background-color: #171821; */
  background-color: #21222d;
  color: white;
  height: 400px;
  border: 1px solid rgb(255, 255, 255, .1);
  border-radius: 10px;
}

#card2 {
  height: 600px;
}

.right {
  padding: 0;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px;
  height: 400px;
}

.small-card {
  height: 195px;
  /* background-color: #171821; */
  background-color: #21222d;
  border-radius: 10px;
  border: 1px solid rgb(255, 255, 255, .1);
}

#toContact {
  padding: 3% 6%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: left;
}

#toContact p {
  color: rgb(255, 255, 255, .6);
}

#mini-cards {
  padding: 3% 6%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#mini-cards h1 {
  font-size: 65px;
}

#mini-cards h2 {
  font-size: 35px;
}

#mini-cards span {
  font-size: 25px;
}

#mini-cards p {
  color: rgb(255, 255, 255, .6);
}

.carousel {
  margin: auto;
  width: 70%;
  height: 400px;
}

.carousel-inner {
  border-radius: 25px;
  border: 2px solid rgb(255, 255, 255, .45);
}

#card2 {
  padding: 3% 6%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#card2 h1 {
  font-size: 55px;
}

#card2 h2 {
  font-size: 35px;
}

#card2 span {
  font-size: 25px;
}

#card2 p {
  color: rgb(255, 255, 255, .6);
}</style>
