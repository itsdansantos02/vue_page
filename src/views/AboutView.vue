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
          <div class="small-card" id="mini-cards" data-bs-toggle="modal" data-bs-target="#SkillModal">
            <div class="technical"></div>
            <p>Technical Skills</p>
          </div>
          <div class="small-card" id="mini-cards" data-bs-toggle="modal" data-bs-target="#SoftModal">
            <div class="soft"></div>
            <p>Soft Skills</p>
          </div>
          <div class="small-card" id="mini-cards" data-bs-toggle="modal" data-bs-target="#InternModal">
            <div class="internship"></div>
            <p>Intership Experience</p>
          </div>
          <div class="small-card" id="mini-cards" data-bs-toggle="modal" data-bs-target="#LeadModal">
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
              A lightweight, open-source code editor developed by Microsoft. It is designed to be highly customizable and
              efficient for various programming and scripting languages.
            </p>
          </div>
        </div>
        <div class="tools-column">
          <div class="card" id="toContact">
            <img src="../assets/github.png" alt="">
            <h3>GitHub</h3>
            <p>
              A web-based platform and service that provides a centralized location for version control and collaborative
              software development.
            </p>
          </div>
        </div>
        <div class="tools-column">
          <div class="card" id="toContact">
            <img src="../assets/canva.png" alt="">
            <h3>Canva</h3>
            <p>
              An online graphic design platform that allows users to create a wide range of visual content easily and
              without the need for advanced design skills.
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
  <!-- Skill Modal Start -->
  <div class="modal fade" id="SkillModal" tabindex="-1" aria-labelledby="SkillModalLabel" aria-hidden="true">
    <div class="modal-dialog" >
      <div class="modal-content">
        <div class="modal-header">
          <h3 class="modal-title" id="SkillModalLabel">Soft Skills</h3>
        </div>
        <div class="modal-body">
          <ul>
            <li>Programming Languages</li>
            <span>&nbsp;(Java, PHP, Javascript, Phyton)</span>
            <li>Front-End</li>
            <span>&nbsp;(HTML, CSS, Bootstrap, Vue.js, Nuxt.js)</span>
            <li>Back-End</li>
            <span>&nbsp;(PHP, Laravel, MySQL)</span>
            <li>Programming Tools</li>
            <span>&nbsp;(Visual Studio Code, MySQL Workbench, Git)</span>
            <li>API</li>
            <span>&nbsp;(Axios)</span>
            <li>State Management</li>
            <span style="color:rgba(255, 255, 255, .8)">&nbsp;(Vuex, Pinia)</span>
            <li>IDEs</li>
            <span>&nbsp;(Visual Studio Code, Apache NetBeans, Atom)</span>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- Skill Modal End -->
  <!-- Soft Modal Start -->
  <div class="modal fade" id="SoftModal" tabindex="-1" aria-labelledby="SoftModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg" style="width: 50%;">
      <div class="modal-content">
        <div class="modal-header">
          <h3 class="modal-title" id="SoftModalLabel">Technical Skills</h3>
        </div>
        <div class="modal-body">
          <ul>
            <li>Excellent communication skills in order to work effectively with team members.</li>
            <li>Project management abilities to effectively plan, organize, and prioritize tasks.</li>
            <li>Excellent time management and prioritization skills to meet project deadlines.</li>
            <li>Ability to work independently and as a part of a team.</li>
            <li>Effective problem-solving skills, adapting to challenges, and making informed decisions under pressure.</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- Soft Modal End -->
  <!-- Intern Modal Start -->
  <div class="modal fade" id="InternModal" tabindex="-1" aria-labelledby="InternModalLabel" aria-hidden="true">
    <div class="modal-dialog" >
      <div class="modal-content">
        <div class="modal-header">
          <h3 class="modal-title" id="InternModalLabel">Internship Experience</h3>
        </div>
        <div class="modal-body">
          <h5>Web Developer Intern - Qpax Traffic Systems Inc.</h5>
          <span>&nbsp;&nbsp;- Designed and implemented an asset management system to optimize the tracking and organization of company resources.</span>
        </div>
      </div>
    </div>
  </div>
  <!-- Intern Modal End -->
  <!-- Lead Modal Start -->
  <div class="modal fade" id="LeadModal" tabindex="-1" aria-labelledby="LeadModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg" >
      <div class="modal-content">
        <div class="modal-header">
          <h3 class="modal-title" id="LeadModalLabel">Leadership Experience</h3>
        </div>
        <div class="modal-body">
          <h5>Explorers in Communication and Information Technology - Secretary (2020-2022)</h5>
          <ul>
            <li><span>&nbsp;Managed comprehensive organizational documentation, encompassing certifications, letters of invitation, and letters of approval.</span></li>
            <li><span>&nbsp;Compiled and submitted a detailed accomplishment report, meticulously documenting all organizational activities and events.</span></li>
          </ul>
          <h5>Explorers in Communication and Information Technology - External Information Officer (2022-2023)</h5>
          <ul>
            <li><span>&nbsp;Proactively engaged with alumni and distinguished IT professionals to establish connections and secure their participation as guest speakers for upcoming events. Demonstrated effective communication skills in coordinating and confirming their involvement</span></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- Lead Modal End -->
</template>
<script>

</script>
<style scoped>
::-webkit-scrollbar {
  width: 5px;
}

/* Track */
::-webkit-scrollbar-track {
  background: rgb(255, 255, 255, .9); 
}
 
/* Handle */
::-webkit-scrollbar-thumb {
  background: #888; 
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555; 
}
.about-container {
  padding: 8% 3% 0 3%;
  width: 100%;
  margin: auto;
}
.modal-dialog{
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  margin: auto;
}
.modal-content{
  width: 100%;
  background-color: #171821;
  max-height: 500px;
  overflow: auto;
}
.modal-content li{
  font-size: 19px;
}
#SoftModal .modal-content li{
  font-size: 18px;
}
.modal-content span{
  font-size: 16px;
  color: rgb(255, 255, 255, .7);
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

img {
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

.tools-column {
  padding: 0;
}

.about-tools .card:hover {
  background-color: #36384a;
  transition: .3s ease;
}
</style>
