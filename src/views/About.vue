<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        Yo! I'm <strong>Adler Teh</strong>, I use to study computer science before majoring into Game Development.<br/>
        I spend my days playing games, watching anime and occasionally going bouldering or playing volleyball.
      </div>

      <div style="margin-top: 20px;">I've worked on  <router-link to="/game-projects">7th Seal</router-link> and on <router-link to="/game-projects">Rapture Reign</router-link>, and have a few other <router-link to="/game-projects">projects</router-link> as well.</div>

      <div style="margin-top: 40px;">I'm <strong>currently looking for an internship/job</strong> as a gameplay programmer starting January. You can reach me at <a href="mailto:adlertzx@gmail.com">adlertzx@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/SmolImage2.jpg" alt="That's me!'" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: -70px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: right;
    padding: 0px;
    padding-left: 0px;
    padding-right: 0px;
    padding-top: 0px;
  }
}

</style>