<template>
  <Layout>
    <div class="content">
    <div id="breadcrums">
      <h1><g-link class="Back" to="/">back to homepage</g-link></h1>
      <h1 class="headline">UX Project</h1>
      </div>
      <div class="container1">
        <div id="title">
          <h2>Penelope</h2>
          <p class="subtext">A product concept</p>
        </div>
      <div class="container2">
        <g-image src="~/assets/images/penfidget.png" alt="icon" class="imagep" />
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
 color: #1c2833;
  margin-left: 15px;
}

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
  color:   #4768ff;
  
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
  padding-bottom: 30px;
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
  a{
  font-size: 24px;
} 

.headline{
  font-size:24px;
  margin-right: 10px;
}

  .container2 {
    display: flex;
    flex-direction: column;
    max-width: 100%;
  }

  .imagep{
    max-width: 100%;
    margin-left:13px;
    
  }
  .container1 {
    padding-left: 0px;
    margin-left: 10px;
    margin-right: auto;
    padding-top: 30px;
    padding-bottom: 30px;
    padding-bottom: 30px;
    font-size: 18px;
    max-width: 100%;
    align-items: center;
    text-align: justify;

  }

  #title {
    padding-left: 10px;
    align-items: center;
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