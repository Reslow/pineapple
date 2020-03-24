<template>
  <Layout>
    <Header />
    <div id="bodyWrap">
      <div id="projects">
        <div id="contentwrap">
          <div class="headline">
            <p id="titleP">Case Studies</p>
            <p id="titleT">
              These are my selected top three projects.
              They are based on user research methods.
            </p>
          </div>

          <div class="container1">
            <div class="containerContent">
              <g-image src="~/assets/images/mojobw.png" alt="icon" class="imgCard" />
              <div class="description">
                <p class="cH">Journalist's mobile Tool</p>
                <p
                  class="cS"
                >This case study aimed to understand a journalist activities and how the mobile can support the journalist in his/her workprocess.</p>
                <p class="cY">2019</p>
                <g-link to="/projects/mobile-tool" class="buttonView1">View project</g-link>
              </div>
            </div>
          </div>

          <div class="container2">
            <div class="containerContent">
              <g-image src="~/assets/images/dronebw.png" alt="icon" class="imgCard" />
              <div class="description">
                <p class="cH">Forest drone app</p>
                <p
                  class="cS"
                >A design of a mobile interface that helps forest workers to plan and overview the forest with a drone.</p>
                <p class="cY">2019</p>
                <g-link to="/projects/my-forest-drone-app" class="buttonView2">View project</g-link>
              </div>
            </div>
          </div>

        <div class="container3">
          <div class="containerContent">
            <g-image src="~/assets/images/dogbw.png" alt="icon" class="imgCard" />
            <div class="description">
              <p class="cH">Vet diagnostic app</p>
              <p
                class="cS"
              >We aimed to design an application which could visualize result from a rapid test.</p>
              <p class="cY">2019</p>
              <g-link to="/projects/vet-app" class="buttonView3">View project</g-link>
            </div>
          </div>
        </div>
        </div>
      </div>

      <div class="headline">
        <p id="titleP">UI Design</p>
        <p id="titleT">Here are a few UIs :)</p>
      </div>

      <div id="cardwrap">
        <g-link to="/projects/travel-one" class ="card"> 
          <g-image src="~/assets/images/travelonea.png" alt="icon" class="imgUiCard" />
        </g-link>

        <g-link to="/projects/travel-two" class ="card">
          <g-image src="~/assets/images/traveltwoa.png" alt="icon" class="imgUiCard" />
        </g-link>

        <g-link to="/projects/green-page" class ="card">
          <g-image src="~/assets/images/greenfront.png" alt="icon" class="imgUiCard" />
        </g-link>

        <g-link to="/projects/city-event" class ="card">
          <g-image src="~/assets/images/FirstPageBeforeLogin.png" alt="icon" class="imgUiCard" />
        </g-link>
      </div>
    </div>

    <div id="about">
      <div class="aboutTextContainer">
        <div class="aboutElements">
          <g-image src="~/assets/images/profile.png" alt="Profile image" class="imageProfile" />
          <p class="email">reslowf@gmail.com</p>
          <a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin">LinkedIn</a>
        </div>
        <p class="aboutText">
          My name is Fanny and I have a bachelor degree in interaction design from Linneaus University. I currently live in Gothenburg and I am looking for new projects. If you are searching for a driven designer with passion for user research and interface design, lets talk! ;)
          <br />
          <br />When I have time left, I focus on exploring my design easthetic, new design trends and updating this website. I try to explore new tools, such as Figma.
          I am used to work with Illustrator and adobe XD. I know my way around the adobe suit, UXPin and Axure RP for interactive prototypes.
        </p>
      </div>
    </div>
  </Layout>
</template>

<script>
import Header from "../components/Header";

export default {
  components: {
    Header
  },
  metaInfo: {
    title: " Fanny Reslow Portfolio"
  }
};
</script>


<style>
.aboutTextContainer {
  max-width: 60%;
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  align-self: center;
 
}

.aboutElements {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 100px;
  padding-bottom: 0px;
}

.email {
  padding-top: 20px;
  font-size: 18px;
  font-weight: bolder;
}

#linkedin {
  margin-top: 0px;
  padding: 7px;
  padding-left: 8px;
  padding-right: 8px;
  cursor: pointer;
  align-items: center;
  font-weight: normal;
  font-size: 18px;
  color: #c70053d0;

}

#linkedin:hover {
  color: #1c2833;
}


.imageProfile {
  min-width: 120px;
  min-height: 120px;
  max-width: 60%;
}

.aboutText {
  font-size: 18px;
  line-height: 34px;
  padding-top: 10px;
  padding-bottom: 300px;
  margin-bottom: 0px;
  max-width: 45%;
  margin-left: auto;
  margin-right: auto;
}

#about {
  margin-top: 200px;
  padding-bottom: 0px;
  margin-bottom: 0px;
  background-color: rgb(255, 255, 255);
}

.buttonView1{
  background-color: rgb(89, 78, 150);
  color: #f0f0f0d0;
  padding-left: 60px;
  padding-right: 60px;
  padding-top: 20px;
  padding-bottom: 20px;
  font-size: 24px;
  align-self: flex-end;
  box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.08);
  transition: 0.3s ease-in-out;
}

.buttonView2{
   background-color:rgb(52, 129, 95);
  color: #f0f0f0d0;
  padding-left: 60px;
  padding-right: 60px;
  padding-top: 20px;
  padding-bottom: 20px;
  font-size: 24px;
  align-self: flex-end;
  box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.08);
  transition: 0.3s ease-in-out;
}

.buttonView3{
  background-color: rgb(167, 96, 61);
  color: #f0f0f0d0;
  padding-left: 60px;
  padding-right: 60px;
  padding-top: 20px;
  padding-bottom: 20px;
  font-size: 24px;
  align-self: flex-end;
  box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.08);
  transition: 0.3s ease-in-out;
}

.buttonView1:hover, .buttonView2:hover, .buttonView3:hover {
  box-shadow: 0 5px 15px 2px rgba(0, 0, 0, 0.1);
}

.cardHeadline {
  margin-left: auto;
  margin-right: auto;
  align-content: center;
  padding-top: 50px;
  
}

a {
  text-decoration-line: none;
}


.cH {
  
  font-size: 60px;
  margin-bottom: 10px;
  margin-top: 0px;
}

.cS {
  font-size: 18px;
  margin-bottom: 5px;
}

.cY {
  font-size: 18px;
  margin-bottom: 70px;
  font-weight: bold;
}


#titleP {
  color: #202020;
  font-family:sans-serif;
  font-size: 60px;
  margin-bottom: 10px;
  padding-top: 30px;
  text-align: center;
  margin-right: 0px;
  font-weight: bolder;
}

#titleT {
  color: #444444;
  font-size: 24px;
  text-align: left;

  
}

.headline {
  align-self: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  
}
.linkA {
  color: #351655d0;
  text-decoration-line: none;
}

.linkA:hover {
  color: #6087ac;
}

#contentwrap {
  display: flex;
  flex-direction: column;
  
}

#cardwrap {
display:grid;  
grid-template-columns: 1fr 1fr;
grid-template-rows: 1fr 1fr;
column-gap: 15px;
row-gap:15px;
margin-left:250px;
margin-right:250px;
}



.imgUiCard{
  width: 100%;
  height:100%;
   box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);

  
}

.imgUiCard:hover{
   box-shadow: 0 19px 38px rgba(0,0,0,0.30), 0 15px 12px rgba(0,0,0,0.22);
   transform: translate(-2px, -2px);
   transition-duration: 1s;
}


.imgCard {
  margin-right: 100px;
  margin-left: 200px;

}



.container1 {
  margin-top: 20px;
  margin-bottom: 150px;
  background-color: rgb(74, 65, 128);
}
.container2 {
  margin-top: 20px;
  margin-bottom: 150px;
  background-color:rgb(46, 117, 85);
}
.container3 {
  margin-top: 20px;
  margin-bottom: 150px;
  background-color: rgb(148, 84, 52);
}

.containerContent {
  display: flex;
  flex-direction: row;
  padding-top: 150px;
  padding-bottom: 150px;
}

.description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-left: 45px;
  margin-bottom: 0px;
  color: #f0f0f0d0;
  max-width: 40%;
}

#projects {
  display: flex;
  flex-direction: column;
  padding-top: 100px;
}

@media (max-width: 800px) {

  #headText{
    margin-left: 0px;
  }
  
#projects {
  padding-top: 20px;
 
}

#titleT{
  margin-left:auto;
  margin-right: auto;
  width:90%;
  text-align: center;
}

.containerContent{
  width: 100%;
  display: flex;
  flex-direction: column;
  padding-top:10px;
  padding-bottom: 60px;;
}

.imgCard{
width: 100%;
padding:0px;
margin:0px;
}

.imgUiCard{
  margin-bottom: 10px;;
}

.description{
  padding:0px;
  margin-right: auto;
  margin-left: auto;
  max-width: 90%;
}

.buttonView1, .buttonView2, .buttonView3{
  margin-right: auto;
  margin-left: auto;

}

.container1, .container2, .container3{
  margin-bottom: 100px;
}

#cardwrap{
  display: flex;
  flex-direction: column;
  margin-left:0px;
  margin-right: 0px;
}

#about{
  margin-top: 100px;
  max-width: 100%;
}
.aboutElements{
  margin:0px;
  padding:0px;
}
.aboutTextContainer{
  max-width: 100%;
}

.aboutText{
  max-width: 90%;
}
.imageProfile{

  min-width: 100%;
  min-height: 100%;
  max-width: 100%;
}


}
</style>
