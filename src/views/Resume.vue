<template>
    <div>
        <h1>Resume</h1>

        <div class="paragraph">
            I'm <strong>Adler Teh</strong>, I started out with a background in computer science, making scratch projects remaking Undertale with Vainglory characters and taking part in coding competitions.
            <br />After which going into Uni, I fully committed to the Game Developer lifestyle, and now im here!
            <br />I have made a few projects and even participated in a few gamejams.
            <br />I can work solo, and in teams, as I have experience working in both groups and working alone.
            <br />
            <br /><strong>Personal Info</strong>
            <br />DOB: 10th Novemver 2002
            <br />Email: adlertzx@gmail.com
            <br />Address: Jalan PJU 3/18g, Tropicana Indah Resort Homes, 47410 Petaling Jaya, Selangor
            <br />
            <router-link to="/contact">more contact options here</router-link>
            <br />
            <br /><strong>Language Proficiencies</strong>
            <br />English
            <br />Chinese
            <br />French (2nd Language)
            <br />Japanese (2nd Language)
            <br />
            <br /><strong>Interest & Hobbies</strong>
            <br />Photography some of my photos on the right ->
            <br />Editing Videos/Vlogs
            <br />Volleyball
            <br />Bouldering
            <br />Frisbee
            <br />Video Games
            <br />Anime
            <br />
            <br /><strong>Core Competencies</strong>
            <br />Eager to learn
            <br />Ability to perform under pressure
            <br />
            <br /><strong>Education</strong>
            <br />KDU UOW Malaysia
            <br />Bachelor of Game Development (Honours)
            <br />

            <div style="margin-top:20px; margin-bottom:20px;">
                <a class="download-link" href="d/Adler's Resume.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF </a>
                <div style="clear:both"></div>
            </div>
        </div>
        <div class="photo">
            <img src="img/Resume.jpeg" alt="It's me" />
        </div>
        <div class="photo">
            <img src="img/Scotland.jpeg" alt="Nice pic" />
        </div>

        <div style="clear:both"></div>

        <div class="full-content">
            <!--<h2>Work experience</h2>

            <h3>Operation Classified - Delta Force</h3>
            <h4>2018-2019</h4>

            <div>It's classified so I can't speak about it.</div>

            <div class="tech-stack">Firearms, knives, grenades, Hummer vehicle, parachute,...</div>

            <h3>Operation Classified - Delta Force</h3>
            <h4>2015-2017</h4>

            <div>It's classified so I can't speak about it.</div>

            <div class="tech-stack">Even more Firearms, knives, grenades, Hummer vehicle, parachute,...</div>

            <h3>Operation Classified - Delta Force</h3>
            <h4>2012-2015</h4>

            <div>It's classified so I can't speak about it.</div>

            <div class="tech-stack">Firearms, knives, grenades, Hummer vehicle, parachute,...</div>-->

            <h2>Skills</h2>

            <div class="skill-set">
                <!--<h3>Coding</h3>-->
                <SkillRate name="Unity" :rate="4" />
                <SkillRate name="C++" :rate="4" />
                <SkillRate name="Godot" :rate="2" />
                <SkillRate name="Unreal" :rate="2" />
                <SkillRate name="Sense of Humor" :rate="4" />


            </div>
            <div class="photo">
                <img src="img/Japan.jpeg" alt="Nice pic 2" />
            </div>
            <!--<div class="skill-set">
                <h3>Non-lethal</h3>
                <SkillRate name="Sneaking" :rate="1" />
                <SkillRate name="Negotiation" :rate="1" />
                <SkillRate name="Seduction" :rate="1" />
                <SkillRate name="Sense of humor" :rate="2" />
            </div>-->
            <div style="clear:both" />

            <!--<h2>Education</h2>

            <h3>Kindergarten - 1985</h3>
            <h4>Kindergarten degree</h4>
            <div>Specialty in bullying and fighting (58 wins, 58 K-O, 0 losses)</div>

            <h2>Languages</h2>

            <h3>American</h3>
            <div>Basic knowledge but I know lots of one-liners</div>

            <h3>That's it</h3>
            <div>Who needs another language when you speak American?</div>


            <h2>Besides...</h2>
            <div>
                <h3>I ❤️ Violence</h3>
                <div>I find it really soothing to just shoot at bad guys</div>

                <h3>I 🧡 Sports</h3>
                <div>I used to be thin but then I ingested 10 kilos of steroids and proteins a day while doing 1000 push-ups.</div>

                <h3>I 💛 Politics</h3>
                <div>I hope I can have a career here someday but I might have temper issues.</div>

                <h3>I 💚 Flowers</h3>
                <div>Especially the big ones, with the trunk and leaves.</div>

            </div>-->
        </div>
    </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    SkillRate,
  },
});
</script>

<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo img {
  height: 600px;
  width: 450px;
}

.tech-stack {
  font-style: italic;
}

.photo {
  margin-top: 5px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: right;
    padding: 0px;
    padding-left: 50px;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>