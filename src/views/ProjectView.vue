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
          <div class="tools-footer">
            <h3 title="Student Health Record Information System">SHIRS</h3>
            <a href="#" @click.prevent="showAlert"><i class='bx bxs-arrow-from-left'></i></a>
          </div>
        </div>
      </div>
      <div class="tools-column">
        <div class="card" id="toContact">
          <div class="img" id="shirs-admin"><span>SHIRS</span></div>
          <div class="details">
            <div class="category">Css</div>
            <div class="category">Laravel</div>
            <div class="category">Nuxt</div>
            <div class="category">MySql</div>
            <div class="category">Bootstrap</div>
            <div class="category">Api</div>
          </div>
          <div class="tools-footer">
            <h3 title="Asset Management System">Asset Management System</h3>
            <a href="#" @click.prevent="showAlert"><i class='bx bxs-arrow-from-left'></i></a>
          </div>
        </div>
      </div>
      <div class="tools-column">
        <div class="card" id="toContact">
          <div class="img" id="shirs-make"><span>SHIRS</span></div>
          <div class="details">
            <div class="category">UI/UX</div>
            <div class="category">Canva</div>
          </div>
          <div class="tools-footer">
            <h3 title="Make-EAT">Make-EAT</h3>
            <a href="https://www.canva.com/design/DAFHU0J1da4/RavCGkXAOzvRt2k_BdbQbw/edit?utm_content=DAFHU0J1da4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank"><i class='bx bxs-arrow-from-left'></i></a>
          </div>
        </div>
      </div>
    </div>
    <br>
    <br>
  </div>
</template>
<script>
export default {
  methods: {
    showAlert() {
      // Show an alert when the link is clicked
      alert('Preview is not yet available, Please Contact the owner to access');
    }
  }
}
</script>
<style scoped>
.tools-footer{
 display: flex;
 justify-content: space-between;
}
.tools-footer i{
 font-size: 35px;
 cursor: pointer;
}
.tools-footer a{
 margin: 3% 6% 2%;
 text-decoration: none;
 color: white;
}
.tools-footer i:hover{
 text-decoration: underline;
 color: #9da0be;
}
.tools-footer h3{
  cursor: pointer;
}
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
  background-image: url('../assets/project-shirs.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
#shirs-admin{
  background-image: url('../assets/project-ams.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
#shirs-make{
  background-image: url('../assets/project-make.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
  