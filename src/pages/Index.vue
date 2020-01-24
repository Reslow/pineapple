<template>
  <Layout>
     <Header/>
    <div id="bodyWrap">
      
      <div id="projects">
        <div id="cardwrap">
          <div class="cardHeadline">
          <p id="titleP">UX Projects</p>
          <p id="titleT">These are my selected top three projects. 
          these projects are focused on user research. 
          </p>
          </div>

          <div id="cards">
            <g-link to="/projects/mobile-tool">
              <div class="card">
                <div class="container">
                  <g-image
                    src="~/assets/images/mojocard.png"
                    alt="icon"
                    style="width:100%"
                    class="imgCard"
                  />
                  <div class="cardtext">
                    <p>Journalist tools</p>
                  </div>
                </div>
              </div>
            </g-link>

            <g-link to="/projects/my-forest-drone-app">
              <div class="card">
                <div class="container">
                  <g-image
                    src="~/assets/images/forest.png"
                    alt="icon"
                    style="width:100%"
                    class="imgCard"
                  />
                  <div class="cardtext">
                    <p>Forest drone app</p>
                  </div>
                </div>
              </div>
            </g-link>

            

            <g-link to="/projects/vet-app">
              <div class="card">
                <div class="container">
                  <g-image
                    src="~/assets/images/dog.png"
                    alt="icon"
                    style="width:100%"
                    class="imgCard"
                  />

                  <div class="cardtext">
                    <p>Vet diagnostic app</p>
                  </div>
                </div>
              </div>
            </g-link>
          </div>
        </div>

        <div id="cardwrap">
            <div class="cardHeadline">
          <p id="titleP">UI Design</p>
          <p id="titleT"> I have focused on, contrast, information architecture and 
            user flow in these UI designs.
          </p>
            </div>

          <div id="cards">
            <g-link to="/projects/for-kitchen">
              <div class="card">
                <div class="container">
                  <g-image
                    src="~/assets/images/forkitchenpattern.png"
                    alt="icon"
                    style="width:100%"
                    class="imgCard"
                  />
                </div>
              </div>
            </g-link>

            <g-link to="/projects/draw">
              <div class="card">
                <div class="container">
                  <g-image
                    src="~/assets/images/Drawpattern.png"
                    alt="icon"
                    style="width:100%"
                    class="imgCard"
                  />
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
                    class="imgCard"
                  />
                </div>
              </div>
            </g-link>
          </div>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
  import Header from "../components/Header";

export default {
  components: {
    Header
  },
        metaInfo: {
          title: " Fanny Reslow Portfolio"
        }
};
</script>


<style>

.cardHeadline{
  padding-bottom: 10px;
  padding-left:60px;

   margin-left: auto;
  margin-right: auto;
  
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 100px;
}

#titleT{
  color:  #351655d0;
 
  align-items: center;
  max-width: 70%;
  font-size: 18px;
}
.linkA {
  color:   #351655d0;
  text-decoration-line: none;
}

.linkA:hover {
  color: #6087ac;
}

#cardwrap {
  display: flex;
  flex-direction: column;
  max-width: 600px;
  align-items: center;
}


.container {
  text-align: left;
  position: relative;
  color: #1c2833;
  margin-top: auto;
}

#cards {
  padding-top: 30px;
  flex-wrap: wrap;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

#projects {
  display: flex;
  flex-direction: row;
  padding-top:550px;
}
.cardtext {
  position: absolute;
  bottom: 10px;
  left: 20px;
  font-size: 20px;
  letter-spacing: 1px;
  line-height: 24px;
  color: rgba(255, 255, 255, 0.966);
  font-weight: bold;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  margin-bottom: 0px;
}

p {
  margin-bottom: 5px;
  
}



#titleP {
    color:   #351655d0;
  font-size: 28px;
  margin-bottom: 20px;
  padding-top:30px;

  font-weight: bold;
}

#bodyWrap {
  flex-direction: column;
  display: flex;
  justify-content: center;
  margin: auto;
  max-width: 1700px;
  align-items: center;
  padding-bottom: 80px;
}

.card {
  box-shadow: 0 3px 5px 0 rgba(136, 136, 136, 0.473);

  transition: all 0.3s ease;
  margin-left: 20px;
  margin-top: 20px;
  max-width: 220px;
  min-height: 160px;
  min-width: 230px;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
  transform: translateY(-3px);
}

.home-links a {
  margin-right: 3rem;
}

@media (max-width: 800px) {
  a {
    width: 100%;
  }

  #cardwrap {
    width: 100%;
  }
  #projects {
    display: flex;
    flex-direction: column;
    width: 100%;
  }

  .imgCard {
    width: 100%;
  }

  .card {
    max-width: 100%;
    margin: 0px;
    margin-bottom: 15px;
    margin-right: 0px;
  }

  #cards {
    width: 100%;
    align-items: center;
    padding-bottom: 10px;

    display: flex;
    margin: 0px;
  }
  p {
    min-width: 0px;
  }

  .wrap {
    max-width: 100%;
  }
  #fronttext {
    text-align: left;
    
    padding-left: 60px;
    padding-right: 20px;
    margin-right: 0px;

    margin-top: 20px;
    margin-bottom: 20px;
    font-size: 18px;
    color: #1c2833;
  }

  #bodyWrap {
    flex-direction: column;
    display: flex;

    max-width: 100%;
  }

  #textwrap {
    justify-content: center;
    max-width: 100%;
  }

  #titleP {
    margin-bottom: 40px;
  }

  .cardtext{
     position: absolute;
  bottom: 36px;
  left: 20px;
  font-size: 28px;
  letter-spacing: 1px;
  line-height: 24px;
  color: rgba(255, 255, 255, 0.966);
  font-weight: bold;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  margin-bottom: 0px;
  }
}
</style>
