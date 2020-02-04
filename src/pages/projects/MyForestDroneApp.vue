<template>
  <Layout>
    <div id="breadcrums">
      <h1>
        <g-link class="Back" to="/">Back to homepage</g-link>
      </h1>
      <h1 class="headline">UX Project</h1>
    </div>

    <div class="content">
      <h1 id="projectTitle">My Forest drone application</h1>

      <div class="project">
        <div class="leftSide">
          <div class="projectDescription">
            <div id="title">
              <p
                class="subtext"
              >A project with four other students during the spring 2018 with The swedish forest agency</p>
            </div>
            <p
              class="text"
            >The project was given by The Swedish forest agency. In this project I worked with four other students. We developed a design of an interface for a mobile application that helps forest workers to plan and overview the forest. The Swedish forest agency wanted to motivate more workers to use drones in their workday. It is important to develop an interface that forest workers understand.</p>
          </div>

          <Timeline :timelineData="timelineData" />
        </div>

        <div class="rightSide">
          <div class="solution">

            <g-image src="~/assets/images/forestappCard.png" alt="icon" class="imagep" />
            <div class="textWrap">
              <p class="subtext">My forest drone application UI</p>
              <p class="text">
                My forest drone app is a concept of a mobile application that helps forest workers to plan and overview the forest. With the application the user can control the drone, second is tagging objects for work purposes. The app has only the most critical information needed for flying, such as battery strength, height of drone and direction of the drone. The application has different map layers because the map layers view different information.
                <br />This image has been redesigned after the course
              </p>
            </div>
          </div>

          <div class="aha">

            <div class="ahaText">
              <p>
                When flying a drone it is important to feel in control. A lot of workers in the forest today are not use to new technology
                and needs an application that is easy to use and understand.
              </p>

              <p>
                The owner of the project had a plan of gathering image material
                to train a AI of identifying objects when flying. However there is a fear of feeling watched from users.
                It is an possibility that users could feel less afraid if they had more control over what is happening. One way of giving more control are to be
                more transparent with what images have been taken.
              </p>
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
            "Meeting with stakeholder representing Swedish forest Agency "
        },
        {
          headline:
            "Conducting contextual study with expert of flying drones in forest industry "
        },
        {
          headline: "Affinity diagram"
        },
        {
          headline: "Interface analysis of competitor "
        },
        {
          headline: "Presenting concept for feedback "
        },
        {
          headline: "Paper prototype and formative user test"
        },
        {
          headline: "Redesign and Interactive prototype",
          subtitle: ""
        }
      ]
    };
  }
};
</script>


<style scoped>
.aha {
  margin-left: 200px;
  margin-right: 100px;
  max-width: 50%;
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



#projectTitle {
  margin-left: 40px;
  padding-left: 10px;
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

.back {
  color: #1c2833;
  font-size: 18px;
}

a {
  font-size: 18px;
  color: #1c2833;
  text-decoration: none;
}

a:hover {
  font-size: 18px;
border-bottom: black solid 1px;
}

a:active {
  font-size: 18px;
  color: #1c2833;
}

.headline {
  margin-left: 30px;
  margin-bottom: 0px;
  font-size: 18px;
  color:   #351655d0;
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
  padding-top:100px;
}

#projectTitle {
  font-weight: normal;
  margin-left: 50px;
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
  padding:0px;
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
  margin-left: 0px;
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
  padding-left: 0px;
}


.textWrap {
  display: flex;
  flex-direction: column;
  margin-left: 0px;

}



.headline {
  margin-left: 30px;
  margin-bottom: 0px;
  font-size: 18px;
   color:#292929d0;
}




.projectDescription {
 
  max-width: 100%;
  margin-left: 25px;
  margin-right: 25px;
  padding-right: 0px;
 
}



.solution {
  display: flex;
  flex-direction: column-reverse;
 
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


</style>