<template>
  <Layout>
    <div id="breadcrums">
      <h1>
        <g-link class="Back" to="/">Back to homepage</g-link>
      </h1>
      <h1 class="headline">UX Project</h1>
    </div>

    <div class="content">
      <div class="project">
        <h1 id="projectTitle">My forest drone application</h1>

        <div class="hiSide">
          <div class="projectDescription">
            <div class="text">
              <p class="title">
                A project with four other students during the spring 2018 with
                The swedish forest agency
              </p>
            </div>
            <p
              class="text"
            >The project was given by The Swedish forest agency. In this project I worked with four other students. We developed a design of an interface for a mobile application that helps forest workers to plan and overview the forest. The Swedish forest agency wanted to motivate more workers to use drones in their workday. It is important to develop an interface that forest workers understand.</p>
          </div>
          <div id="timelineCon">
            <p class="subtext">Designprocess</p>

            <Timeline :timelineData="timelineData" />
          </div>
        </div>

        <div class="loSide">
          <div class="solution">
            <g-image src="~/assets/images/forestappCard.png" alt="icon" class="imagep" />
            <div class="text">
              <p class="subtext">My forest drone application UI</p>
              <p>
                My forest drone app is a concept of a mobile application that helps forest workers to plan and overview the forest. With the application the user can control the drone, second is tagging objects for work purposes. The app has only the most critical information needed for flying, such as battery strength, height of drone and direction of the drone. The application has different map layers because the map layers view different information.
                <br />This image has been redesigned after the course
              </p>
            </div>
          </div>

          <div class="aha">
            <div class="text">
              <p class="subtext">Findings</p>
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
#timelineCon {
  margin-left: auto;
  margin-right: auto;
  max-width: 65%;
}

.project {
  display: flex;
  flex-direction: column;
  align-content: initial;
  max-width: 45%;
  align-content: center;
  margin-left: auto;
  margin-right: auto;
}

.hiSide {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
}

.loSide {
  display: flex;
  flex-direction: column;

  margin-bottom: 400px;
}

#breadcrums {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-left: 20px;
}
#title {
  max-width: 100%;
  color: #000000;

  margin-right: auto;

  align-self: auto;
}
.textWrap {
  display: flex;
  flex-direction: column;
}

.back {
  color: #000000;
  font-size: 18px;
}

a {
  font-size: 18px;
  color: #c70053d0;
  font-weight: normal;
  text-decoration: none;
}

a:hover {
  color: #1c2833;
}

a:active {
  font-size: 18px;
  color: #1c2833;
}

.headline {
  margin-left: 30px;
  margin-bottom: 0px;
  font-size: 18px;
  color: #292929d0;
  font-weight: normal;
}

#projectTitle {
  font-size: 100px;
  font-weight: lighter;
  max-width: 65%;
  margin-bottom: 0px;
  margin-right: auto;
  margin-left: auto;
}
.text {
  margin-top: 20px;
  font-size: 18px;
  font-style: normal;
  line-height: 28px;

  margin-right: auto;
  margin-left: auto;
  max-width: 65%;
}

.subtext {
  font-size: 24px;
  align-self: inherit;
}

.projectDescription {
  color: #1c2833;

  margin-top: 30px;
  margin-bottom: 50px;
  font-size: 18px;
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
}

.process {
  font-weight: bold;
  margin-top: 200px;
  margin-left: auto;
  margin-right: auto;
}

.solution {
  margin-left: auto;
  margin-right: auto;

  display: flex;
  flex-direction: column;

  padding-top: 100px;
  margin-bottom: 50px;
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
}

.imagep {
  max-width: 65%;
  margin-top: 20px;

  margin-bottom: 30px;

  margin-right: auto;
  margin-left: auto;
}
</style>