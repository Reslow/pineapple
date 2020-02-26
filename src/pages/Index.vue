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
              These case studies are based on user research methods.
            </p>
          </div>

          <div id="cards">
            <g-link to="/projects/mobile-tool">
              <div class="card">
                <div class="container">
                  <g-image src="~/assets/images/mojobw.png" alt="icon" class="imgCard" />
                  <div class="description">
                    <p class="cH">Journalist Tool</p>
                    <p
                      class="cS"
                    >This case study aimed to understand a journalist activities and how the mobile can support the journalist in his/her workprocess.</p>
                    <p class="cY">2019</p>
                  </div>
                </div>
              </div>
            </g-link>

            <g-link to="/projects/my-forest-drone-app">
              <div class="card">
                <div class="container">
                  <g-image src="~/assets/images/dronebw.png" alt="icon" class="imgCard" />
                  <div class="description">
                    <p class="cH">Forest drone app</p>
                    <p
                      class="cS"
                    >A design of a mobile interface that helps forest workers to plan and overview the forest with a drone.</p>
                    <p class="cY">2019</p>
                  </div>

                  <div class="cardtext"></div>
                </div>
              </div>
            </g-link>

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
        <h2 id="FirstLine">Hello</h2>
        <p class="aboutText">
          My name is Fanny and I have a bachelor degree in interaction design from Linneaus University. I currently live in Gothenburg and I am looking for new projects. If you are searching for a driven designer with passion for user research and interface design, lets talk! ;) <br><br>
          I have practiced interaction design through various projects. From defining problems and user needs in context to validate prototype with users.
         <br><br>
          When I have time left, I focus on exploring my design easthetic, new design trends and updating this website. I try to explore new tools, such as Figma.
          I am used to work with Illustrator and adobe XD. I know my way around the adobe suit, UXPin and Axure RP for interactive prototypes.
        </p>
        </div>
        <div class="aboutElements">
        <g-image src="~/assets/images/profile.png" alt="Profile image" class="imageProfile" />
        <p class="email">reslowf@gmail.com</p>
        <a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin">LinkedIn</a>
        </div>
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
  padding-bottom: 300px;
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
  max-width: 40%;
}

.aboutText {
  font-size: 18px;
  line-height: 34px;
  padding-bottom: 0px;
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

.cardHeadline {
  max-width: 50%;
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
  font-size: 100px;
  margin-bottom: 10px;
}


.cS {
  font-size: 18px;
}

.cY {
  font-size: 16px;
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

  font-size: 30px;
  font-weight: lighter;
  text-align: center;
  margin: 0px;
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
  max-width: 100%;
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

.container {
  width:100%;
  margin-left:auto;
  margin-right: auto;
  height: 500px; 
  margin-top: 20px;
  margin-bottom: 20px;
  display: flex;
  flex-direction: row;
  background-color: rgb(245, 245, 245);
  padding:5px;
  
}

.description {
  display: flex;
  flex-direction: column;
  padding-left: 45px;
  color: #ff2e85d0;
}

#cards {
  flex-wrap: wrap;
  display: flex;
  flex-direction: column;

  margin-top: 50px;
  max-width: 100%;
}

#projects {
  display: flex;
  flex-direction: column;
  padding-top: 400px;
}
.cardtext {
  position: absolute;

  left: 50px;
  font-size: 20px;
  letter-spacing: 1px;

  color: rgba(255, 255, 255, 0.966);
  font-weight: bold;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  margin-bottom: 0px;
}



.card {
  max-width: 95%;
  box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.08);
  margin-right: auto;
  margin-left: auto;

}

.card:hover {
  box-shadow: 0 5px 15px 2px rgba(0, 0, 0, 0.322);
 
}



.home-links a {
  margin-right: 3rem;
}

@media (max-width: 800px) {
  #cardwrap {
    width: 100%;
  }
  #projects {
    display: flex;
    flex-direction: column;
    width: 100%;
  }

  .card {
    width: 100%;
    margin: 0px;
    margin-bottom: 15px;
    margin-right: 0px;
  }

  #cards {
    width: 100%;
    align-items: center;
    padding-bottom: 10px;

    display: flex;
    margin: 0px;
  }

  .wrap {
    max-width: 100%;
  }
  #fronttext {
    text-align: left;

    padding-left: 60px;
    padding-right: 20px;
    margin-right: 0px;

    margin-top: 20px;
    margin-bottom: 20px;
    font-size: 18px;
    color: #1c2833;
  }

  #bodyWrap {
    flex-direction: column;
    display: flex;

    max-width: 100%;
  }

  #textwrap {
    justify-content: center;
    max-width: 100%;
  }

  #titleP {
    margin-bottom: 40px;
  }

  #titleT {
    max-width: 90%;
  }

  .cardtext {
    position: absolute;
    bottom: 36px;
    left: 20px;
    font-size: 28px;
    letter-spacing: 1px;
    line-height: 24px;
    color: rgba(255, 255, 255, 0.966);
    font-weight: bold;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    margin-bottom: 0px;
  }
}
</style>
