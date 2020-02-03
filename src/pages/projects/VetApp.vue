<template>
  <Layout>
    <div id="breadcrums">
      <h1>
        <g-link class="Back" to="/">Back to homepage</g-link>
      </h1>
      <h1 class="headline">UX Project</h1>
    </div>

    <div class="content">
      <h1 id="projectTitle">Vet app for rapid test</h1>

      <div class="project">
        <div class="leftSide">
          <div class="projectDescription">
            <g-image src="~/assets/images/projectIcon.png" alt="icon" class="iconProblem" />
            <div id="title">
              <p
                class="subtext"
              >A mobile interface that visualizes the results of rapid test in dogs cancer diagnosis</p>
            </div>
            <p
              class="text"
            >For 9 weeks me and three other students researched about how vets diagnose cancer in dogs, to design an application which could visualize result from a rapid test. We worked with a company which had a new technique of measuring blood, the new technique makes it possible to catch some types of cancer in an earlier stage.</p>
          </div>

          <g-image src="~/assets/images/why.png" alt="icon" class="iconWhy" />
          <Timeline :timelineData="timelineData" />
        </div>

        <div class="rightSide">
          <div class="solution">
            <g-image src="~/assets/images/solution.png" alt="icon" class="iconSolution" />

            <g-image src="~/assets/images/vacMouckup.png" alt="icon" class="imagep" />
            <div class="textWrap">
              <p class="subtext">Vet app UI</p>
              <p class="text">
                The vet takes a blood sample and drop blood on the rapid test. Then he/she wait 10 minutes and then they point the mobile camera towards the rapid test. Finally, the screen will show result that can be transferred to the journal.
                Today vets take blood sample and send them to a lab and haft to wait for result. With a rapid test and an app for viewing result the procedure would be faster and more efficient.
              </p>
            </div>
          </div>

          <div class="aha">
            <g-image src="~/assets/images/aha.png" alt="icon" class="iconAha" />

            <div class="ahaText">
              <p>
                According to our research, acceptance is built on the user background and experience and the perceived usefulness and usability of the product.
                The interface needs to be simple and only have the function needed for the vets to reach their goal.
               
                 
              </p>

              <p>
              It is important with specificity in the test, we also found that the image of the company behind the product is important.
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
.aha {
  margin-left: 200px;
  margin-right: 100px;
  max-width: 50%
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
  margin-top: 200px;
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
  color: #000000;
  margin-bottom: 20px;
}
.textWrap {
  display: flex;
  flex-direction: column;
  margin-left: 20px;
}

.back {
  color: #000000;
  font-size: 18px;
}

a {
  font-size: 18px;
  color: #1c2833;
  text-decoration: none;
}

a:hover {
  
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
  color:#292929d0;
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
  padding-left:30px;
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

</style>