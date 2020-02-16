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
        <h1 id="projectTitle">Mobile Journalistic Tool</h1>

        <div class="hiSide">
          <div class="projectDescription">
            <div class="text">
              <p class="title">A mobile interface that supports journalits activities and goals.</p>
            </div>
            <p
              class="text"
            >This case study was part of my bachelor thesis work in informatics - interaction design (2019). The case study aimed to understand a journalist activities and how the mobile can support the journalist in their workprocess.</p>
          </div>
          <div id="timelineCon">
            <p class="subtext">Designprocess</p>
            <Timeline :timelineData="timelineData" />
          </div>
        </div>

        <div class="loSide">
          <div class="solution">
            <g-image src="~/assets/images/Mojo.png" alt="icon" class="imagep" />
            <div class="text">
              <p class="subtext">Mobile journalist app UI</p>
              <p>
                This mobile application supports journalists to write, tag and publish news on the go.
                It supports journalist to share material quick and easy with a common file library. This wireframe are based on the company´s existing writing tool and the case study.
              </p>
            </div>
          </div>

          <div class="aha">
            <div class="text">
              <p class="subtext">Findings</p>
              <p>
                The common attitude to work with the mobile as a tool are positiv. But not writing with it
                <br />
                <br />
              </p>

              <p>
                An mobile application could support an journalist on the way toward an assignment or when he or she happen to be at the spot of an event.
                <br />
                <br />
              </p>

              <P>The value of an mobile application is in the quick way of communicating and sharing information</P>
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