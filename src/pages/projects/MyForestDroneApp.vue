<template>
  <Layout>
    <div class="content">
      <div class="container2">
        <g-image src="/png/dronepage.png" alt="icon" style="max-height: calc(100vh - 100px);" />
      </div>
      <div class="container1">
        <div id="title">
          <h2>My Forest drone application</h2>
          <p>A project with four other students during the spring 2018 with The swedish forest agency</p>
        </div>

        <div class="spalt">
          <h3>The app</h3>
          <p
            class="text"
          >My forest drone app is a concept of a mobile application that helps forest workers to plan and overview the forest. The app has two main functions, first one is controlling the drone, second is tagging objects for work purposes. The app has only the most critical information needed for flying, such as battery strength, height of drone and direction of the drone. The application has different map layers because the map layers view different information.</p>
          <h3>The project</h3>
          <p
            class="text"
          >The project was given by The Swedish forest agency. In this project I worked with four other students. We developed a design of an interface for a mobile application that helps forest workers to plan and overview the forest. The Swedish forest agency wanted to motivate more workers to use drones in their workday. It is important to develop an interface that forest workers understand.</p>
          <h3>The Study</h3>
          <p
            class="text"
          >We conducted a study where we met a user and an expert on flying drones in the forest industry. We did an interview with observations and think aloud technique. In the study we learned about the importance of feeling control and there is a need for simplifying the interface and options of micro functionality. After the study we wrote down and discussed our thoughts in an affinity diagram. Then we started creating our first concept. The concept was presented towards experts for validation. We did a user test where we presented a paper prototype to a potential user and asked questions of his understanding of the interface. The test got us a lot of knowledge about perception of interface elements. We redesigned and then started on building an interactive prototype in Axure RP.</p>
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
   margin-bottom: 30px;
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