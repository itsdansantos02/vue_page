<template>
  <div class="about">
    <div class="about-container">
      <h1>All Projects</h1>
    </div>
  </div>
  <div class="about-tools">
    <div class="row">
      <div class="tools-column">
        <div class="card" id="toContact">
          <div class="img" id="shirs-user"><span>SHIRS</span></div>
          <div class="details">
            <div class="category">Js</div>
            <div class="category">Css</div>
            <div class="category">Php</div>
            <div class="category">MySql</div>
            <div class="category">Ajax</div>
          </div>
          <h3>SHIRS - User Panel</h3>
        </div>
      </div>
      <div class="tools-column">
        <div class="card" id="toContact">
          <div class="img" id="shirs-admin"><span>SHIRS</span></div>
          <div class="details">
            <div class="category">Js</div>
            <div class="category">Css</div>
            <div class="category">Php</div>
            <div class="category">MySql</div>
            <div class="category">Ajax</div>
          </div>
          <h3>SHIRS - Admin Panel</h3>
        </div>
      </div>
      <div class="tools-column">
        <div class="card" id="toContact">
          <div class="img" id="shirs-admin"><span>SHIRS</span></div>
          <div class="details">
            <div class="category">UI/UX</div>
            <div class="category">Canva</div>
          </div>
          <h3>Make-EAT</h3>
        </div>
      </div>
    </div>
    <br>
    <br>
  </div>
</template>
<script>

</script>
<style scoped>
.about-container {
  padding: 8% 3% 0 3%;
  width: 100%;
  margin: auto;
}

.about-container h1 {
  font-size: 60px;
}

.about-container h4 {
  margin-bottom: 4%;
}

.about-container p {
  font-size: 18px;
  color: rgb(255, 255, 255, .7);
}


.about-tools .row {
  padding: 3% 4% 0 4%;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 20px;
}

.about-tools .card {
  /* background-color: #171821; */
  background-color: #21222d;
  color: white;
  height: 500px;
  border: 1px solid rgb(255, 255, 255, .1);
  border-radius: 10px;
  width: 100%;
}

#toContact {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: left;
}
#toContact .details{
  padding: 5% 6% 1%;
  display: flex;
  gap: 10px;
}
#toContact .details .category{
  padding: 4px 15px;
  /* background-color: #262736; */
  background-color: #21222d;
  border: 1px solid rgb(255, 255, 255, .3);
  border-radius: 3px;
  text-align: center;
  color: rgb(255, 255, 255, .6);
}
#toContact .details p {
  color: rgb(255, 255, 255, .6);
}
#toContact h3{
  margin: 3% 6% 2%;
}
.tools-column{
  padding: 0;
}
/* .about-tools .card:hover {
  background-color: #36384a;
  transition: .3s ease;
} */
.about-tools .img{
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: red;
  height: 355px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  margin-top: -4%;
}
.img span{
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 700;
  color: rgba(23,24,33,.8);
  font-size: 120px;
  display:none;
  transition: 5s ease;
}
/* .card:hover .img span {
    display: block;
    transition: 5s ease;
  } */
#shirs-user{
  background-image: url('../assets/shirs-2.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
#shirs-admin{
  background-image: url('../assets/shirs-4.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
  