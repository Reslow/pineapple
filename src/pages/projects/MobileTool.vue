<template>
  <Layout>
    <div id="breadcrums">
      <h1>
        <g-link class="Back" to="/">back to homepage</g-link>
      </h1>
      <h1 class="headline">UX Project</h1>
    </div>

    <div class="content">
      <h1 id="projectTitle">Mobile Journalistic Tool</h1>

      <div class="project">
        <div class="leftSide">
          <div class="projectDescription">
            <g-image src="~/assets/images/projectIcon.png" alt="icon" class="iconProblem" />
            <div id="title">
              <p class="subtext">A mobile interface that supports journalits activities and goals.</p>
            </div>
            <p
              class="text"
            >This case study was part of my bachelor thesis work in informatics - interaction design (2019). The case study aimed to understand a journalist activities and how the mobile can support the journalist in their workprocess.</p>
          </div>

          <g-image src="~/assets/images/why.png" alt="icon" class="iconWhy" />
          <Timeline :timelineData="timelineData" />
        </div>

        <div class="rightSide">
          <div class="solution">
            <g-image src="~/assets/images/solution.png" alt="icon" class="iconSolution" />

            <g-image src="~/assets/images/Mojo.png" alt="icon" class="imagep" />
            <div class="textWrap">
              <p class="subtext">Mobile journalist app UI</p>
              <p class="text">
                This mobile application supports journalists to write, tag and publish news on the go.
                It supports journalist to share material quick and easy with a common file library. This wireframe are based on the company´s existing writing tool and the case study.
              </p>
            </div>
          </div>

          <div class="aha">
            <g-image src="~/assets/images/aha.png" alt="icon" class="iconAha" />

            <div class="ahaText">
              <p>
                The common attitude to work with the mobile as a tool are positiv. But not writing with it
              </p>

              <p>
                 An mobile application could support an journalist on the way toward an assignment or when he or she happen to be at the spot of an event.
              </p>

              <P>The value of an mobile application is in the quick way of communicating and sharing information </P>

            
            </div>
          </div>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
import Timeline from "../../components/Timeline";
export default {
  components: {
    Timeline
  },
  data() {
    return {
      timelineData: [
        {
          headline:
            "A walk through of computer-based journalistic writing tool. "
        },
        {
          headline:
            "9 Interviews focusing on utility and usability and work process with journalits"
        },
        {
          headline: "Transcription of interview material"
        },
        {
          headline: "Coding transriptions"
        },
        {
          headline: "Analysing coding of  transcription"
        },
        {
          headline: "Creating Sketches and wireframes"
        }
      ]
    };
  }
};
</script>


<style scoped>
.aha {
  max-width: 50%;
  margin-left: 200px;
  margin-right: 100px;
}

.ahaText p {
  margin-top: 50px;
}

.ahaText {
  font-size: 18px;
  font-weight: lighter;
  font-style: italic;
  color: #351655;
  align-items: center;
}

.iconAha {
  margin-left: 50px;
  margin-right: 10px;
  margin-top: 300px;
  margin-bottom: 10px;
}

#projectTitle {
  margin-left: 40px;
  padding-left: 10px;
}

.iconProblem {
  margin-right: 10px;
  margin-top: 10px;
  margin-bottom: 10px;
}

.iconSolution {
  margin-left: 10px;
  margin-right: 10px;
  margin-top: 10px;
  margin-bottom: 10px;
}

.iconWhy {
  margin-left: 10px;
  margin-right: 10px;
  margin-top: 50px;
  margin-bottom: 10px;
}

.project {
  display: flex;
  flex-direction: row;
  margin-left: 45px;
  margin-right: 15px;
}

.leftSide {
  display: flex;
  flex-direction: column;
  max-width: 45%;
}

.rightSide {
  display: flex;
  flex-direction: column;
  max-width: 55%;
}

#breadcrums {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-left: 20px;
}
#title {
  color: #1c2833;
  margin-bottom: 20px;
}
.textWrap {
  display: flex;
  flex-direction: column;
  margin-left: 20px;
}



a {
  font-size: 18px;
  color: #1c2833;
  text-decoration: none;
}

a:hover {
  color:  #fe7849;
}

a:active {
  font-size: 18px;
  color: #1c2833;
}

.headline {
  margin-left: 30px;
  margin-bottom: 0px;
  font-size: 18px;
  color: #351655a1;
}

.text {
  margin: auto;
  padding-right: 10px;
  margin-top: 30px;

  max-width: 100%;
  font-size: 18px;
  font-style: normal;
  line-height: 28px;
}

h2 {
  padding-top: 5px;
  margin-top: 0px;
  text-align: left;
}

h3 {
  padding-left: 15px;
  margin-top: 0px;
  font-size: 18px;
}
.subtext {
  text-align: left;
  font-size: 24px;
}
p {
  margin: 0px;
  font-size: 18px;
  text-align: justify;
}

.projectDescription {
  color: #1c2833;
  max-width: 70%;
  margin-top: 30px;
  margin-left: 40px;
  padding-right: 20px;
  font-size: 18px;
  display: flex;
  flex-direction: column;
}

.process {
  padding-left: 40px;
  padding-right: 40px;
  font-weight: bold;
  margin-top: 200px;
}

.solution {
  display: flex;
  flex-direction: row;
  align-items: flex-end;
  margin-right: 50px;
}

#projectTitle {
  font-weight: normal;
  padding-left: 30px;
}

.content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
}
.textCon {
  display: flex;
  margin: auto;
  max-width: 100%;
}

.imagep {
  max-width: 50%;
  margin-top: 20px;
}
@media (max-width: 860px) {
  a {
    font-size: 18px;
  }

  .headline {
    font-size: 24px;
    margin-right: 10px;
  }

  .imagep {
    max-width: 100%;
    margin-left: 13px;
  }

  #title {
    padding-left: 10px;
    align-items: center;
  }

  h3 {
    padding-left: 10px;
  }

  .content {
    display: flex;
    flex-direction: column;
  }

  .textCon {
    display: flex;
    margin: auto;
    max-width: 50%;
  }

  .text {
    padding-left: 10px;
    padding-right: 10px;
    max-width: 100%;
    font-size: 16px;
    line-height: 28px;
  }

  @media (max-width: 860px) {

  .text{
    margin-top:20px;
    margin-left:0px;
    margin-right: 0px;
  }

  .content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  }

  .ahaText{
 
 text-align: center;
 
  
}

.iconAha{
  margin-top: 50px;
}

.iconSolution{
  margin-top: 50px;
}

  .aha{
  
  margin-left: 25px;
  margin-right: 25px;
  margin-top: 0px;
 
  max-width: 90%
}

#projectTitle {
  margin-left: 40px;
  margin-bottom: 0px;
  
}

.project {
  display: flex;
  flex-direction: column;
  margin-left:auto;
  margin-right: auto;
  
  
}

.leftSide {
  display: flex;
  flex-direction: column;
  max-width: 100%;
}

.rightSide {
  display: flex;
  flex-direction: column;
  max-width: 100%;
}


.textWrap {
  display: flex;
  flex-direction: column;
  margin-left: 20px;
}



.headline {
  margin-left: 30px;
  margin-bottom: 0px;
  font-size: 18px;
  color: #351655a1;
}




.projectDescription {
 
  max-width: 100%;
  margin-left: 25px;
  margin-right: 25px;
  padding-right: 0px;
 
}



.solution {
  display: flex;
  flex-direction: column;
 
  margin:20px;
}



.textCon {
  display: flex;
  
  max-width: 100%;
}

.imagep {
  max-width: 100%;
  margin-top: 20px;
  margin-bottom: 50px;
}
 }


}
</style>