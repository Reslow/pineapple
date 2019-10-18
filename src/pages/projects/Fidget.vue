<template>
  <Layout>
    <div class="content">
      <div class="container2">
        <g-image src="/png/penPage.png" alt="icon" style="max-height: calc(100vh - 100px);" />
      </div>
      <div class="container1">
        <div id="title">
          <h2>Penelope</h2>
          <p>A product concept</p>
        </div>

        <div class="spalt">
          <h3>The app</h3>
          <p class="text">
            A new fidget was designed through brainstorming activities and a lot of sketching. Penelope is a case for a pencil, the case is built up from different modules which can spin and have various materials and colors.
            These modules create a case like a jewelry for the pencil. The modules wake curiosity and give people something to do when people are still and need to focus like in a classroom. Penelope can change in look due to the different modules and the material is organic and ecofriendly.
          </p>
          <h3>The project</h3>
          <p
            class="text"
          >The project started with three solutions on fidgets that could entertain a person silently during a meeting and not to disturb too much. I started a brainstorming session based on one question, 1. What do you do when you do nothing?</p>
          <h3>The Study</h3>
          <p
            class="text"
          >This product design has been created through different brainstorming techniques, Sketches and defining product material, brand, market, persona and more. To develop a new fidget, I started with brainstorming and sketching on three types of fidget ideas, Then I chose the fidget idea that was most promising. Then I started sketching on look and feel of the fidget on side of searching for information about similar products. The Penelope fidget became the result as a pen accessory for younger students.</p>
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

  overflow-y: scroll;
  max-height: calc(100vh - 100px);

  display: flex;
  flex-direction: column;
  max-width: 100%;
}
.container2 {
  display: flex;
  flex-direction: row;
  box-shadow: 0 50px 1px 3px rgba(168, 168, 168, 0.911);
}

.content {
   position: fixed;
  display: flex;
  
    position: fixed;
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