<template>
  <Layout>
    <div class="content">
      <div id="breadcrums">
      <h1><g-link class="Back" to="/">back to homepage</g-link></h1>
      <h1 class="headline">UX Project</h1>
      </div>
      <div class="container1">
        <div id="title">
          <h2>My Forest drone application</h2>
          <p
            class="subtext"
          >A project with four other students during the spring 2018 with The swedish forest agency</p>
        </div>

        <div class="container2">
          <g-image
            src="~/assets/images/forestapp.png"
            alt="icon"
            style="min-width: 30%;"
          />
        </div>
        <div class="spalt">
        
          <p
            class="text"
          >My forest drone app is a concept of a mobile application that helps forest workers to plan and overview the forest. The app has two main functions, first one is controlling the drone, second is tagging objects for work purposes. The app has only the most critical information needed for flying, such as battery strength, height of drone and direction of the drone. The application has different map layers because the map layers view different information.</p>
       
          <p
            class="text"
          >The project was given by The Swedish forest agency. In this project I worked with four other students. We developed a design of an interface for a mobile application that helps forest workers to plan and overview the forest. The Swedish forest agency wanted to motivate more workers to use drones in their workday. It is important to develop an interface that forest workers understand.</p>
          
          <p
            class="text"
          >We conducted a study where we met a user and an expert on flying drones in the forest industry. We did an interview with observations and think aloud technique. In the study we learned about the importance of feeling control and there is a need for simplifying the interface and options of micro functionality. After the study we wrote down and discussed our thoughts in an affinity diagram. Then we started creating our first concept. The concept was presented towards experts for validation. We did a user test where we presented a paper prototype to a potential user and asked questions of his understanding of the interface. The test got us a lot of knowledge about perception of interface elements. We redesigned and then started on building an interactive prototype in Axure RP.</p>
        </div>
      </div>
    </div>
  </Layout>
</template>

<style scoped>

#breadcrums{
  display: flex;
  flex-direction: row;
  margin-left: 20px;
  align-items: center;
}
#title {

  color: #1c2833;
  margin-bottom: 20px;
}
.spalt {
  display: flex;
  flex-direction: column;
  margin-bottom: 20px;
}

.back{
  color: #1c2833;
}

a{ 
  font-size: 36px;
  color: #1c2833;
  text-decoration: none;
  
  
}

a:hover{ 
  font-size: 36px;
  color:   #e24405;
  
}


a:active{ 
  font-size: 36px;
  color: #1c2833;

}

.headline {
  margin-left: 80px;
  padding-left: 60px;
  font-size: 36px;
 color: #1c283398;
  margin-left: 15px;
}

.text {
  margin: auto;
  padding-right: 10px;
  padding-bottom: 20px;
  max-width: 50%;
  font-size: 18px;
  font-style: normal;
  line-height: 28px;
}
h2 {
  margin: 0px;
  padding: 5px;
  text-align:center;
}

h3 {
  padding-left: 15px;
  margin-top: 0px;
  font-size: 18px;
  
}
.subtext{
text-align: center;
font-size: 24px;
}
p {
  
  margin: 0px;
  padding-top: 15px;
  font-size: 18px;
   align-content: center;
   justify-content: left;
}

.container1 {
  
  color: #1c2833;
  padding-top: 30px;
  padding-bottom: 30px;
  padding-left: 20px;
  padding-right: 20px;
  font-size: 18px;
  display: flex;
  flex-direction: column;
  align-content: center;
  max-width: 100%;
}
.container2 {
  
  display: flex;
  flex-direction: column;
  align-items: center;
}

.content {
   
  display: flex;
  flex-direction: column;
  margin-left:auto;
  margin-right: auto;
}
.textCon {
  display: flex;
  margin: auto;
  max-width: 50%;
}

@media (max-width: 860px) {
  .container2 {
    display: flex;
    flex-direction: column;
   
    min-width: 100vw;
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