<template>
  <Layout>
    <Header />
    <div id="bodyWrap">
      <div id="projects">
        <div id="cardwrap">
          <div class="cardHeadline">
            <p id="titleP">UX Projects</p>
            <p id="titleT">
              These are my selected top three projects.
              They are based on user research methods.
            </p>
          </div>

          
            <div class="container">
                  <div class="containerContent">
                  <g-image src="~/assets/images/mojobw.png" alt="icon" class="imgCard" />
                  <div class="description">
                    <p class="cH">Journalist's mobile Tool</p>
                    <p
                    class="cS"
                    >This case study aimed to understand a journalist activities and how the mobile can support the journalist in his/her workprocess.</p>
                    <p class="cY">2019</p>
            <g-link to="/projects/mobile-tool" class="buttonView">View project </g-link>
                </div>
                  </div>
              </div>

            <div class="container">
              <div class="containerContent">
                  <g-image src="~/assets/images/dronebw.png" alt="icon" class="imgCard" />
                  <div class="description">
                    <p class="cH">Forest drone app</p>
                    <p
                      class="cS"
                    >A design of a mobile interface that helps forest workers to plan and overview the forest with a drone.</p>
                    <p class="cY">2019</p>
            <g-link to="/projects/my-forest-drone-app" class="buttonView">View project  </g-link>
                  </div>
                  <div class="cardtext"></div>
                </div>
              </div>
           

            <g-link to="/projects/vet-app">
              <div class="card">
                <div class="container">
                  <g-image src="~/assets/images/dogbw.png" alt="icon" class="imgCard" />
                  <div class="description">
                    <p class="cH">Vet diagnostic app</p>
                    <p
                      class="cS"
                    > We aimed to design an application which could visualize result from a rapid test. </p>
                    <p class="cY">2019</p>
                  </div>

                  <div class="cardtext"></div>
                </div>
              </div>
            </g-link>
          </div>
        </div>

        <div id="cardwrap">
          <div class="cardHeadline">
            <p id="titleP">UI Design</p>
            <p id="titleT">Here are a few UIs :)</p>
          </div>

          <div class="UiHeadline">
            <p class="cH">TravelSite</p>
           
          </div>
          <div id="cards">
            <g-link to="/projects/travel-one">
              <div class="card">
                <div class="container">
                  <g-image
                     src="~/assets/images/travelonea.png"
                    alt="icon"
                  
                    class="imgUiCard"
                  />
                </div>
              </div>
            </g-link>

              <div class="UiHeadline">
            <p class="cH">TravelSite 2</p>
            
          </div>
          <div id="cards">
            <g-link to="/projects/travel-two">
              <div class="card">
                <div class="container">
                  <g-image
                     src="~/assets/images/traveltwoa.png"
                    alt="icon"
                  
                    class="imgUiCard"
                  />
                </div>
              </div>
            </g-link>

            <div class="UiHeadline">
              <p class="cH">TeamGreen</p>
            
            </div>
            <g-link to="/projects/green-page">
              <div class="card">
                <div class="container">
                  <g-image
                    src="~/assets/images/greenfront.png"
                    alt="icon"
                    
                    class="imgUiCard"
                  />
                </div>
              </div>
            </g-link>
            <div class="UiHeadline">
              <p class="cH">CityEvent</p>
             
            </div>
            <g-link to="/projects/city-event">
              <div class="card">
                <div class="container">
                  <g-image
                     src="~/assets/images/FirstPageBeforeLogin.png"
                    alt="icon"
                    
                    class="imgUiCard"
                  />
                </div>
              </div>
            </g-link>
          </div>
        </div>
      </div>
      <div id="about">
        <div class ="aboutTextContainer">
        <div class="aboutElements">
        <g-image src="~/assets/images/profile.png" alt="Profile image" class="imageProfile" />
        <p class="email">reslowf@gmail.com</p>
        <a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin">LinkedIn</a>
        </div>
        <p class="aboutText">
          My name is Fanny and I have a bachelor degree in interaction design from Linneaus University. I currently live in Gothenburg and I am looking for new projects. If you are searching for a driven designer with passion for user research and interface design, lets talk! ;) <br><br>
          I have practiced interaction design through various projects. From defining problems and user needs in context to validate prototype with users.
         <br><br>
          When I have time left, I focus on exploring my design easthetic, new design trends and updating this website. I try to explore new tools, such as Figma.
          I am used to work with Illustrator and adobe XD. I know my way around the adobe suit, UXPin and Axure RP for interactive prototypes.
        </p>
        </div>
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
.aboutTextContainer{
  max-width: 60%;
  display: flex;
 flex-direction: column;
margin-left:auto;
margin-right: auto;
align-self: center;
}

.aboutElements{
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top:100px;
  padding-bottom: 0px;
}

.email {
  padding-top: 20px;
  font-size: 18px;
  font-weight: lighter;
}

#linkedin {
  margin-top: 0px;
  letter-spacing: 1px;
  padding: 7px;
  padding-left: 8px;
  padding-right: 8px;
  cursor: pointer;
  align-items: center;
  font-weight: normal;
  font-size: 18px;
  font-kerning: initial;
 color:#c70053d0;
}

#linkedin:hover {
  color: #1c2833;
}

#FirstLine {
  text-align: center;
  color: #34079c;
  font-size: 44px;
  font-weight: lighter;
}

.imageProfile {
  min-width: 120px;
  min-height: 120px;
  max-width: 60%;
}

.aboutText {
  font-size: 18px;
  line-height: 34px;
  padding-top:10px;
  padding-bottom: 300px;
  margin-bottom: 0px;
  justify-content: right;
  max-width: 45%;
  margin-left:auto;
  margin-right: auto;
}  
 
#about {
  margin-top: 200px;
  padding-bottom: 0px;
  margin-bottom: 0px;
}

.buttonView{
 background-color: rgb(55, 136, 110);
 color:white;
 padding-left:60px;
 padding-right:60px;
 padding-top:20px;
 padding-bottom: 20px;
 font-size: 24px;
 align-self: flex-end;
 box-shadow: 0 3px 5px 0 rgba(0, 0, 0, 0.08);
transition:  0.3s ease-in-out;
}
.buttonView:hover{
  box-shadow: 0 5px 15px 2px rgba(0, 0, 0, 0.1);
}

.cardHeadline {
  margin-left: auto;
  margin-right: auto;
  align-content: center;
  padding-top:50px;
}

a {
  text-decoration-line: none;
}

.UiHeadline {
  align-self: center;
  color: #34079c;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.cH {
  font-weight: lighter;
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

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 100px;
}

#titleP {
  color: #34079c;
  font-size: 36px;
  margin-bottom: 20px;
  padding-top: 30px;
  text-align: center;
  font-weight: lighter;
  margin-right: 0px;
}

#titleT {
  color: #34079c;
  font-size: 24px;
  font-weight: lighter;
  text-align: left;
  margin-bottom: 40px;
}

.linkA {
  color: #351655d0;
  text-decoration-line: none;
}

.linkA:hover {
  color: #6087ac;
}

#cardwrap {
  display: flex;
  flex-direction: column;
 
}

.imgUiCard{
width:40%;
height:100%;
align-self: center;
margin-left:auto;
margin-right: auto;
margin-top:100px;
margin-bottom:100px;
}

.imgCard{
  margin-right:100px;
  margin-left:200px;

 
}

.container {
  width: 100vw;
  margin-top: 20px;
  margin-bottom: 500px;
  background-color: rgb(48, 122, 99);
}

.containerContent{
  display: flex;
  flex-direction: row;
  padding-top:150px;
   padding-bottom:150px;
 
  


}

.description {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-left: 45px;
  margin-bottom:0px;;
  color: #ffffffd0;
  max-width: 40%;
}



#projects {
  display: flex;
  flex-direction: column;
  padding-top: 100px;
}
.cardtext {

  left: 50px;
  font-size: 20px;
  letter-spacing: 1px;

  color: rgba(255, 255, 255, 0.966);
  font-weight: bold;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  margin-bottom: 0px;
}


@media (max-width: 800px) {
  
}
</style>
