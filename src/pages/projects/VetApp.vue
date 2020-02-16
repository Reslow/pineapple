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
        <h1 id="projectTitle">Vet app for rapid test</h1>

        <div class="hiSide">
          <div class="projectDescription">
            <div class="text">
              <p class="title">
                A mobile interface that visualizes the results of rapid test
                in dogs cancer diagnosis
              </p>
            </div>
            <p
              class="text"
            >For 9 weeks me and three other students researched about how vets diagnose cancer in dogs, to design an application which could visualize result from a rapid test. We worked with a company which had a new technique of measuring blood, the new technique makes it possible to catch some types of cancer in an earlier stage.</p>
          </div>

          <div id="timelineCon">
            <p class="subtext">Designprocess</p>
            <Timeline :timelineData="timelineData" />
          </div>
        </div>

        <div class="loSide">
          <div class="solution">
            <g-image src="~/assets/images/vacMouckup.png" alt="icon" class="imagep" />
            <div class="text">
              <p class="subtext">Vet app UI</p>
              <p>
                The vet takes a blood sample and drop blood on the rapid test. Then he/she wait 10 minutes and then they point the mobile camera towards the rapid test. Finally, the screen will show result that can be transferred to the journal.
                Today vets take blood sample and send them to a lab and haft to wait for result. With a rapid test and an app for viewing result the procedure would be faster and more efficient.
              </p>
            </div>
          </div>

          <div class="aha">
            <div class="text">
              <p class="subtext">Findings</p>
              <p>
                According to our research, acceptance is built on the user background and experience and the perceived usefulness and usability of the product.
                The interface needs to be simple and only have the function needed for the vets to reach their goal.
              </p>

              <p>
                <br />
                <br />It is important with specificity in the test, we also found that the image of the company behind the product is important.
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
          headline: "Meeting with stakeholder/ CEO"
        },
        {
          headline: "Literature study about similar products"
        },
        {
          headline: "Interviews with veterinarians"
        },
        {
          headline: "Themantic analysis "
        },
        {
          headline: "Creating concept with design studio "
        },
        {
          headline: "Creation of mockups"
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
  width: 100%;
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