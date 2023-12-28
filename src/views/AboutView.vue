<template>
  <div class="about">
    <div class="about-container">
      <h1>Website and Software Developer</h1>
      <h4>Danilo C. Santos Jr.</h4>
      <p>As a recent graduate holding a Bachelor of Science in Information Technology, I am enthusiastic about commencing my journey in the dynamic field of technology, with a specific focus on web and software development. Equipped with a robust foundation in Information Technology, I am ready to apply both my theoretical knowledge and practical skills to make meaningful contributions to the constantly evolving landscape of digital innovation.</p>
      <p>My academic experience has provided me with a comprehensive understanding of essential aspects such as programming languages, database management, and system analysis. These skills not only serve as the pillars of effective software development but also reflect my commitment to mastering the core competencies required in the industry. Throughout my studies, I've embraced challenges and cultivated a versatile skill set that positions me as a proactive and adaptable professional ready to thrive in the exciting world of technology.</p>
    </div>
    <div class="about-tools">
      <div class="img"></div>
      <div class="tools"></div>
    </div>
  </div>
</template>

<style>
.about-container{
  padding: 8% 3% 0 3%;
  width: 100%;
  margin: auto;
}
.about-container h1{
  font-size: 60px;
}
.about-container h4{
  margin-bottom: 4%;
}

.about-container p{
  font-size: 18px;
  color: rgb(255, 255, 255, .7);
}
.about-tools{
  padding: 0 3% 0 3%;
  width: 100%;
  margin: auto;
  display: grid;
  grid-template-columns: 40% 60%;
  grid-gap: 10px;
}
.about-tools .img{
  background-color: red;
  width: 100%;
  height: 600px;
  background-image: url('../assets/grad.JPG');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
