<template>
  <div id="bg">
    <div id="bg2">
      <Layout>
        <div id="bodyWrap">
          <div id="textwrap">
            <h1 id="hdFirst">UX & interaction designer</h1>

            <p
              id="fronttext"
            >I design interfaces with the aim of creating better interactions and experiences for users.</p>
          </div>
          <div id="cardwrap">
            <p id="titleP">Projects</p>

            <div id="cards">
              <g-link to="/projects/Fidget">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/pen.jpg" alt="icon" style="width:100%" />
                    <div class="cardtext">
                      <p
                        class="cardText"
                      >A fidget that could be used during a meeting or a presentation</p>
                    </div>
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/Ar-concept">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/glasses.jpg" alt="icon" style="width:100%" />
                    <div class="cardtext">
                      <p class="cardText">A concept that could improve a learning environment</p>
                    </div>
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/my-forest-drone-app">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/drone.jpg" alt="icon" style="width:100%" />
                    <div class="cardtext">
                      <p
                        class="cardText"
                      >An interface that motivates workers in the forest industry to use drones</p>
                    </div>
                  </div>
                </div>
              </g-link>

              <g-link to="/projects/Vet-lab-app">
                <div class="card">
                  <div class="container">
                    <g-image src="~/assets/images/vet.jpg" alt="icon" style="width:100%" />

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
#credit {
  margin-top: 200px;
  margin-left: 10px;
}

#textwrap {
  display: flex;
  flex-direction: column;
  margin: 10px;
  max-width: 600px;
  padding: 10px;
}

#cards {
  flex-wrap: wrap;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.cardText {
  color: #131313d3;
  font-size: 14px;
  text-align: left;
  font-family: helvetica;
  font-weight: bold;
  line-height: 18px;
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 10px;
  margin-left: auto;
  margin-right: auto;
}

#fronttext {
  text-align: justify;
  padding-top: 40px;
  margin-right: 20px;
  margin-top: 0px;
  font-size: 24px;
  font-weight: bold;
  color: white;
  padding-bottom: 5px;

  border-bottom: 5px solid rgba(255, 255, 255, 0.89);
}

#titleP {
  color: rgba(255, 255, 255, 0.89);
  font-size: 36px;
  margin-bottom: 5px;
  padding-left: 50px;
  font-weight: bold;
}

#bg2 {
  background-image: linear-gradient(
      to bottom,
      rgba(238, 237, 237, 0.8),
      rgba(99, 98, 98, 0.8),
      rgba(36, 36, 36, 0.8)
    ),
    url(../assets/images/cup.png);

  background-repeat: no-repeat;
  background-size: cover;

  min-height: 100vh;
}

#bodyWrap {
  flex-direction: row;
  display: flex;
  justify-content: center;
  margin: auto;
  max-width: 1000px;
}

.card {
  box-shadow: 0 3px 5px 0 rgba(136, 136, 136, 0.473);
  border-radius: 5px;
  transition: all 0.3s ease;
  margin-left: 10px;

  margin-top: 10px;
  padding-bottom: 20px;
  max-width: 220px;
  min-height: 240px;
  min-width: 200px;
  background-image: linear-gradient(rgb(255, 255, 255), rgb(226, 226, 226));
  overflow: hidden;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
  transform: translateY(-3px);
}

.home-links a {
  margin-right: 3rem;
}

#hdFirst {
  color: rgb(238, 238, 238);
  margin-bottom: 0px;
  text-align: right;
  font-size: 85px;
}

@media (max-width: 800px) {
  #credit {
    margin-top: 20px;
    display: inline-block;
    margin: auto;
  }
  #cards {
    align-items: center;
    padding-bottom: 10px;
    margin-top: 2rem;
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
    margin-bottom: 30px;
  }

  #bg2 {
    background-image: linear-gradient(
        to bottom,
        rgba(255, 254, 254, 0.712),
        rgba(22, 22, 22, 0.877),
        rgba(53, 53, 53, 0.897)
      ),
      url(../../static/walking.png);
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
  }

  #fronttext {
    text-align: left;
    padding-top: 8px;
    margin-top: 0px;
    font-size: 16px;
    color: white;
  }

  #hdFirst {
    color: rgb(255, 255, 255);
    margin-bottom: 0px;
    text-align: left;
    font-size: 40pt;
    margin-top: 15px;
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
