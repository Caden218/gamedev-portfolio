<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        Yo! I'm <strong>Adler Teh</strong>, I used to study computer science before majoring into Game Development.<br/>
        I spend my days playing games, watching anime and occasionally <br />going bouldering or playing volleyball.
      </div>

      <div style="margin-top: 20px;">I'm working on a game currently called <router-link to="/game-projects">The Generational Dream</router-link>, the name is still a working title. But my past works include <router-link to="/game-projects">The 7th Seal</router-link>, and a few other <router-link to="/other-projects">Gamejam projects</router-link> as well.</div>

      <div style="margin-top: 40px;">I'm <strong>currently looking for an internship/job</strong> as a gameplay programmer starting January. You can reach me at <a href="mailto:adlertzx@gmail.com">adlertzx@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/About.jpeg" alt="That's me!'" /> 
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
  margin-top: -470px;
  text-align: center;
}

.photo img {
    height: 512px;
    width: 512px;
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