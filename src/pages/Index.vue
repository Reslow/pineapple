<template>
  <div id="bg">
    <div id="bg2">
      <Layout>
        <div id="bodyWrap">
          <div id="textwrap">
            <p
              id="fronttext"
            > Hi, I am Fanny. <br><br> I am educated in Interaction design.<br> 
            I like to solve problems by understanding users.<br><br>
            I design interfaces with the aim of creating better interactions and experiences for users.<br><br>
              </p>
          </div>
          <div id="cardwrap">

            <p id="titleP">UX Projects</p>
            <div id="cards">
              <g-link to="/projects/fidget">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/penpattern.png" alt="icon" style="width:100%" />
                    <div class="cardtext">
                      <p
                        class="cardText"
                      >A fidget that could be used during a meeting or a presentation</p>
                    </div>
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/ar-concept">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/arpattern.png" alt="icon" style="width:100%" />
                    <div class="cardtext">
                      <p class="cardText">A concept that could improve a learning environment</p>
                    </div>
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/my-forest-drone-app">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/dronepattern.png" alt="icon" style="width:100%" />
                    <div class="cardtext">
                      <p
                        class="cardText"
                      >An interface that motivates workers in the forest industry to use drones</p>
                    </div>
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/vet-lab-app">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/vetpattern.png" alt="icon" style="width:100%" />

                    <div class="cardtext">
                      <p
                        class="cardText"
                      >An interface that visualizes the results of rapid test in dogs cancer diagnosis</p>
                    </div>
                  </div>
                </div>
              </g-link>
            </div>
          </div>

          <div id="cardwrap">
            <p id="titleP">UI Design</p>

            <div id="cards">
              <g-link to="/projects/draw">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/Drawpattern.png" alt="icon" style="width:100%" />
                  
                    
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/city-event">
                <div class="card">
                  <div class="container">
                    <g-image
                      src="~/assets/images/cityeventpattern.png"
                      alt="icon"
                      style="width:100%"
                    />
                    
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/for-kitchen">
                <div class="card">
                  <div class="container">
                    <g-image
                      src="~/assets/images/forkitchenpattern.png"
                      alt="icon"
                      style="width:100%"
                    />
                    
                  </div>
                </div>
              </g-link>
            </div>
          </div>
        </div>
      </Layout>
    </div>
  </div>
</template>

<script>
export default {
  metaInfo: {
    title: " Fanny Reslow Portfolio"
  }
};
</script>

<style>
.cardwrap{
  display:flex;
  flex-direction: column;
  align-items: center;
}
#textwrap {
  display: flex;
  flex-direction: column;
  margin: 10px;
  max-width: 600px;
}

.container {
  font-size: 16px;
  font-weight: bold;
  line-height: 24px;
  position: relative;
  text-align: center;
  display: flex;
  align-items: center;

  color: rgb(223, 223, 223);
}

#cards {
  flex-wrap: wrap;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.cardText {
  position: absolute;

  bottom: 20px;
  left: 10px;
  right: 10px;
}

#fronttext {
  width:100%;
  text-align: left;
  padding-bottom: 20px;
  margin-right: 20px;
  margin-top: 0px;
  font-size: 24px;
  line-height: 34px;
  color: rgba(19, 19, 19, 0.795);
   

  
}

#titleP {
  color: rgba(252, 120, 120, 0.726);
  font-size: 36px;
  margin-bottom: 5px;
  text-align: center;
  
  font-weight: bold;
}

#bg2 {
 
  background-repeat: no-repeat;
  background-size: cover;

  min-height: 100vh;
}

#bodyWrap {
  flex-direction: row;
  display: flex;
  justify-content: center;
  margin: auto;
  max-width: 1600px;
  align-items: center;
}

.card {
  box-shadow: 0 3px 5px 0 rgba(136, 136, 136, 0.473);
  border-radius: 5px;
  transition: all 0.3s ease;
  margin-left: 10px;
  margin-top:10px;
  max-width: 220px;
  min-height: 140px;
  min-width: 200px;

  overflow: hidden;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
  transform: translateY(-3px);
}

.home-links a {
  margin-right: 3rem;
}

@media (max-width: 800px) {

  #bg2 {
 background-image: linear-gradient(rgb(214, 212, 212), rgb(224, 224, 224));


  
}
 
  #cards {
    align-items: center;
    
    padding-bottom: 10px;
    margin-top: 2rem;
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
   
    margin-bottom: 30px;
  }

  #fronttext {
    text-align: left;
    padding-top: 8px;
    margin-top: 0px;
    font-size: 16px;
    color: white;
  }

  #bodyWrap {
    flex-direction: column;
    display: flex;
  }

  #textwrap {
    justify-content: center;
  }
}
</style>
