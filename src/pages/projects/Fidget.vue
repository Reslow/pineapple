<template>
  <Layout>
    <div class="content">
      <h1 class="headline">UX Project</h1>
      <div class="container1">
        <div id="title">
          <h2>Penelope</h2>
          <p class="subtext">A product concept</p>
        </div>
      <div class="container2">
        <g-image src="~/assets/images/penfidget.png" alt="icon" style="max-height: calc(100vh - 100px);" />
      </div>

        <div class="spalt">
         
          <p class="text">
            A new fidget was designed through brainstorming activities and a lot of sketching. Penelope is a case for a pencil, the case is built up from different modules which can spin and have various materials and colors.
            These modules create a case like a jewelry for the pencil. The modules wake curiosity and give people something to do when people are still and need to focus like in a classroom. Penelope can change in look due to the different modules and the material is organic and ecofriendly.
          </p>
        
          <p
            class="text"
          >The project started with three solutions on fidgets that could entertain a person silently during a meeting and not to disturb too much. I started a brainstorming session based on one question, 1. What do you do when you do nothing?</p>
         
          <p
            class="text"
          >This product design has been created through different brainstorming techniques, Sketches and defining product material, brand, market, persona and more. To develop a new fidget, I started with brainstorming and sketching on three types of fidget ideas, Then I chose the fidget idea that was most promising. Then I started sketching on look and feel of the fidget on side of searching for information about similar products. The Penelope fidget became the result as a pen accessory for younger students.</p>
        </div>
      </div>
    </div>
  </Layout>
</template>

<style scoped>

.headline {
  margin: 0px;
  font-size: 36px;
 color: rgba(252, 120, 120, 0.726);
  margin-left: 15px;
}

#title {

  color: rgba(13, 13, 13, 0.89);
  margin-bottom: 20px;
}
.headline {
  margin-left: 80px;
  padding-left: 60px;
  font-size: 36px;
 color: rgba(252, 120, 120, 0.726);
  margin-left: 15px;
}

.spalt {
  display: flex;
  flex-direction: column;
  margin-bottom: 30px;
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
  
  color: rgba(13, 13, 13, 0.856);
  padding-top: 30px;
  padding-bottom: 30px;
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 30px;
  font-size: 18px;
  
  max-height: calc(100vh - 100px);

  display: flex;
  flex-direction: column;
  align-content: center;
  max-width: 100%;
}
.container2 {
  
  display: flex;
  flex-direction: column;
  align-items: center;
   margin-top: 100px;
  margin-bottom: 100px;
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