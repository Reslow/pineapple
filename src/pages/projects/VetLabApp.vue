<template>
  <Layout>
    <div class="content">
      <div class="container2">
        <g-image src="/png/vacPage.png" alt="icon" style="max-height: calc(100vh - 100px);" />
      </div>
      <div class="container1">
        <div id="title">
          <h2>Vet app for rapid test</h2>
          <p>A mobile interface that visualizes the results of rapid test in dogs cancer diagnosis</p>
        </div>

        <div class="spalt">
          <h3>The app</h3>
          <p class="text">
            The vet takes a blood sample and drop blood on the rapid test. Then he/she wait 10 minutes and then they point the mobile camera towards the rapid test. Finally, the screen will show result that can be transferred to the journal.
            Today vets take blood sample and send them to a lab and haft to wait for result. With a rapid test and an app for viewing result the procedure would be faster and more efficient.
          </p>
          <h3>The project</h3>
          <p
            class="text"
          >For 9 weeks me and three other students researched about how vets diagnose cancer in dogs, to design an application which could visualize result from a rapid test. We worked with a company which had a new technique of measuring blood, the new technique makes it possible to catch some types of cancer in an earlier stage.</p>
          <h3>The Study</h3>
          <p
            class="text"
          >To understand how we could motivate vets to use this new application we wanted to understand how vets accept new products. According to our research, acceptance is built on the user background and experience and the perceived usefulness and usability of the product. The data gathering resulted in identification of factors which affect vet’s acceptance of the application. It is important with specificity in the test, we also found that the image of the company behind the product is important. The interface needs to be simple and only have the function needed for the vets to reach their goal.</p>
        </div>
      </div>
    </div>
  </Layout>
</template>

<style scoped>
#title {
  padding-bottom: 20px;
  color: rgba(13, 13, 13, 0.89);
  border-bottom: rgb(87, 87, 87) 0.5px solid;
  margin-bottom: 20px;
}
.spalt {
  display: flex;
  flex-direction: column;
}
.text {
  margin: auto;
  padding-top: 20px;
  padding-right: 10px;
  max-width: 50%;
  font-size: 16px;
  font-style: normal;
  line-height: 28px;
}
h2 {
  margin: 0px;
  padding: 5px;
}

h3 {
  padding: 0px;
  margin: 0px;
  font-size: 18px;
}
p {
  margin: 0px;
  padding: 5px;
  font-size: 18px;
}

.container1 {
  background-color: rgba(243, 243, 243, 0.89);
  color: rgba(13, 13, 13, 0.856);
  padding-top: 30px;
  padding-bottom: 30px;
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 30px;
  font-size: 18px;

  display: flex;
  flex-direction: column;
  max-width: 100%;
}
.container2 {
  box-shadow: 0 50px 1px 3px rgba(168, 168, 168, 0.911);
  display: flex;
  flex-direction: row;
}

.content {
  display: flex;
  flex-direction: row;
}
.textCon {
  display: flex;
  margin: auto;
  max-width: 50%;
}
.projectHeadline {
  text-align: center;
  justify-content: left;
}

@media (max-width: 860px) {
  .container2 {
    display: flex;
    flex-direction: column;
    box-shadow: 0 50px 1px 3px rgba(168, 168, 168, 0.911);
    min-width: 100%;
  }
  .container1 {
    padding-left: 0px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 30px;
    padding-bottom: 30px;
    padding-bottom: 30px;
    font-size: 18px;
    min-width: 100%;
  }

  #title {
    padding-left: 10px;
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
}
</style>