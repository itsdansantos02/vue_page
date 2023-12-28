<template>
  <div class="about">
    <div class="about-container">
      <h1>Website and Software Developer</h1>
      <h4>Danilo C. Santos Jr.</h4>
      <p>As a recent graduate holding a Bachelor of Science in Information Technology, I am enthusiastic about commencing
        my journey in the dynamic field of technology, with a specific focus on web and software development. Equipped
        with a robust foundation in Information Technology, I am ready to apply both my theoretical knowledge and
        practical skills to make meaningful contributions to the constantly evolving landscape of digital innovation.</p>
      <p>My academic experience has provided me with a comprehensive understanding of essential aspects such as
        programming languages, database management, and system analysis. These skills not only serve as the pillars of
        effective software development but also reflect my commitment to mastering the core competencies required in the
        industry. Throughout my studies, I've embraced challenges and cultivated a versatile skill set that positions me
        as a proactive and adaptable professional ready to thrive in the exciting world of technology.</p>
    </div>
    <div class="about-skill">
      <div class="img"></div>
      <div class="tools">
        <h1>Skills and Experiences</h1>
        <div class="right minicard">
          <div class="small-card" id="mini-cards">
            <div class="technical"></div>
            <p>Technical Skills</p>
          </div>
          <div class="small-card" id="mini-cards">
            <div class="soft"></div>
            <p>Soft Skills</p>
          </div>
          <div class="small-card" id="mini-cards">
            <div class="internship"></div>
            <p>Intership Experience</p>
          </div>
          <div class="small-card" id="mini-cards">
            <div class="leadership"></div>
            <p>Leadership Experiences</p>
          </div>
        </div>
      </div>
    </div>
    <div class="about-tools">
      <div class="row">
        <div class="tools-column">
          <div class="card" id="toContact">
            <img src="../assets/vscode.png" alt="">
            <h3>Visual Studio Code</h3>
            <p>
              A lightweight, open-source code editor developed by Microsoft. It is designed to be highly customizable and efficient for various programming and scripting languages.
            </p>
          </div>
        </div>
        <div class="tools-column">
          <div class="card" id="toContact">
            <img src="../assets/github.png" alt="">
            <h3>GitHub</h3>
            <p>
              A web-based platform and service that provides a centralized location for version control and collaborative software development.
            </p>
          </div>
        </div>
        <div class="tools-column">
          <div class="card" id="toContact">
            <img src="../assets/canva.png" alt="">
            <h3>Canva</h3>
            <p>
              An online graphic design platform that allows users to create a wide range of visual content easily and without the need for advanced design skills. 
            </p>
          </div>
        </div>
      </div>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
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
img{
  height: 50px;
  width: 50px;
  margin-top: -20px;
  margin-bottom: 10px;
}

.about-skill {
  padding: 0 3% 0 3%;
  width: 100%;
  margin: auto;
  display: grid;
  grid-template-columns: 40% 60%;
  grid-gap: 10px;
}

.about-skill .img {
  width: 100%;
  height: 570px;
  background-image: url('../assets/grad.JPG');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.about-skill h1 {
  text-align: center;
}

.right {
  padding: 5%;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 40px;
  height: 400px;
}

.small-card {
  cursor: pointer;
  height: 210px;
  /* background-color: #171821; */
  background-color: #21222d;
  border-radius: 10px;
  border: 1px solid rgb(255, 255, 255, .1);
  padding: 25px 20px 20px 20px;
}

.small-card .technical {
  width: 100px;
  height: 100px;
  background-image: url('../assets/gear.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.small-card .soft {
  width: 100px;
  height: 100px;
  background-image: url('../assets/thinking.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.small-card .internship {
  width: 100px;
  height: 100px;
  background-image: url('../assets/internship.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.small-card .leadership {
  width: 100px;
  height: 100px;
  background-image: url('../assets/leadership.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

#mini-cards {
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
  margin-top: 6px;
  font-size: 20px;
  color: rgb(255, 255, 255, .6);
}

#mini-cards:hover {
  box-shadow: 0 0 10px 0 white;
  transition: 0.1s ease-in;
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
  height: 300px;
  border: 1px solid rgb(255, 255, 255, .1);
  border-radius: 10px;
  width: 100%;
}

#toContact {
  padding: 1% 6%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: left;
}

#toContact p {
  color: rgb(255, 255, 255, .6);
}
.tools-column{
  padding: 0;
}
.about-tools .card:hover {
  background-color: #36384a;
  transition: .3s ease;
}
</style>
