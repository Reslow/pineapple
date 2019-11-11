<template>
  <Layout>
    <div id="tWrap">
      <h1 class="headline">About</h1>
      <div class="profileImg">
        <div class="bildOchText">
          <g-image src="~/assets/images/profil.png" alt="Profile image" class="ImageProfile" />

          <div class="text">
            <p class="presentation">
              Hi,
              <br />
              My journey toward interaction design started when I was a child and the love of creativity started to grow. When I started upper secondary school I found my interest for marketing and communication. Semotics (study of signs) and the power of an image got my attention. After a detour in healthcare I found a way of working with both technology and humans, I found interaction design.
              <br />
              <br />I recently received my bachelor degree in interaction design (2019), When I am not searching for that first job or working part-time, I spend my time redesigning my portfolio and practicing HTML, CSS and JS.
            </p>
          </div>
        </div>
        <a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin">Linkedin</a>
      </div>

      <div class="skills">
        <div class="skillsT">
          <h2>Designer</h2>
          <p class="skillsText">
            I am a good listener and I love working with people. I encourage new way of thinking.
            My curiosity keeps me redesigning and developing my design aesthetics and skills.
          </p>
        </div>
        <div class="skillsT">
          <h2>Interaction design</h2>
          <p class="skillsText">
           As part of the wide UX field, Interaction design focuses on the communication between user and product. With user centered design approach, I collect knowledge about patterns that creates interfaces that makes products useful
          </p>
        </div>
        <div class="skillsT">
          <h2>Toolbox</h2>
          <p class="skillsText">
            Sticky notes, sticky notes and sticky notes is my number one tool, I also have my sketching book. For high-fidelity prototypes I use Adobe Photoshop, Illustrator, InDesign, XD and Axure RP and UXPIn.
          </p>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "About"
  }
};
</script>

<style scoped>
.bildOchText {
  display: flex;
  flex-direction: row;
  align-content: center;
  margin-right: auto;
  margin-left: auto;
  justify-content: center;
  align-items: center;
}

#tWrap {
  
  min-height: calc(100vh - 100px);
}

h2 {
  margin-left: auto;
  margin-right: auto;
}

h1 {
  margin-left: 20px;
  padding-left: 30px;
}

.skillsText {
  margin-left: 15px;
  margin-right: 15px;
  padding: 7px;
  margin-top: 15px;
  margin-bottom: 35px;
}

.skills {
  margin-top: 30px;
  display: flex;
  flex-direction: row;
  max-width: 70%;
  margin-left: auto;
  margin-right: auto;
}

.skillsT {
  display: flex;
  flex-direction: column;
  max-width: 30%;
  margin-left: auto;
  margin-right: auto;
 
  margin-bottom: 40px;

  text-align: left;
  font-size: 16px;
  line-height: 28px;
  border: rgba(13, 13, 13, 0) 1px solid;
  border-radius: 5px;
  box-shadow: 0 5px 8px 0 rgba(116, 116, 116, 0.253);
}

.text {
  color: rgba(13, 13, 13, 0.829);
  font-size: 18px;
  line-height: 24px;
  max-width: 30%;
  padding-bottom: 10px;
  padding-left: 20px;
  justify-content: right;
}

.ImageProfile {
  min-width: 120px;
  min-height: 120px;
  max-width: 35%;
}

.profileImg {
  display: flex;
  justify-content: center;
  align-items: center;

  padding-bottom: 10px;
  margin-bottom: 15px;
  flex-direction: column;
}

p {
  margin-bottom: 25px;
}

.headline {
  margin: 0px;
  font-size: 36px;
  color: rgba(22, 22, 22, 0.829);
  margin-left: 15px;
}

#linkedin {
  margin-left: auto;
  margin-right: auto;
  border: solid rgba(12, 12, 12, 0.829) 3px;
  padding: 7px;
  padding-left: 8px;
  padding-right: 8px;

  cursor: pointer;
  border-radius: 5px;
  color: rgba(24, 23, 23, 0.829);
  font-weight: bold;
}

#linkedin:hover {
  box-shadow: 0 5px 8px 0 rgba(119, 119, 119, 0.473);
}

@media (max-width: 860px) {
  .bildOchText {
    display: flex;
    flex-direction: column;
    align-content: center;
    margin-right: auto;
    margin-left: auto;
    justify-content: center;
  }

  .ImageProfile {
    min-width: 120px;
    min-height: 120px;
    max-width: 100%;
  }

  .text {
    max-width: 100%;
    padding-top: 20px;
    padding-bottom: 10px;
    padding-left: 20px;
    justify-content: right;
    text-justify: justify;
  }

  .skillsText {
    margin-left: 15px;
    margin-right: 15px;
    padding: 7px;
    margin-top: 15px;
    margin-bottom: 35px;
  }

  .skills {
    margin-top: 30px;
    display: flex;
    flex-direction: column;
    max-width: 90%;
    margin-left: auto;
    margin-right: auto;
  }

  .skillsT {
    display: flex;
    flex-direction: column;
    max-width: 100%;
    margin-left: auto;
    margin-right: auto;
    margin-top: 20px;
    text-align: left;
    font-size: 16px;
    line-height: 28px;
    border: rgba(13, 13, 13, 0) 1px solid;
    border-radius: 5px;
    box-shadow: 0 5px 8px 0 rgba(116, 116, 116, 0.253);
  }
}
</style>
