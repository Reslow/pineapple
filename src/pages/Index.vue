<template>
  <Layout>
    <div id="bodyWrap">
      <div id="textwrap">
        <p id="fronttext">
          Hi, I am Fanny
          <br />
          <br />I design interfaces with the aim of creating better experiences for users.
          <br /> <br>Check out my top three UX projects and UI designs. And/ or read more
          <g-link class="linkA" to="/About">about</g-link>&nbsp;me

        </p>
      </div>
      <div id="projects">
        <div id="cardwrap">
          <p id="titleP">UX Projects</p>
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
          <p id="titleP">UI Design</p>
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
export default {
  metaInfo: {
    title: " Fanny Reslow Portfolio"
  }
};
</script>

<style>
.linkA {
  color: #fe7849;
  text-decoration-line: none;
}

.linkA:hover {
  color: #1c2833;
}

#cardwrap {
  display: flex;
  flex-direction: column;
}
#textwrap {
  display: flex;
  flex-direction: column;
  max-width: 600px;
}

.container {
  text-align: left;
  position: relative;
  color: #1c2833;
  margin-top: auto;
}

#cards {
  flex-wrap: wrap;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

#projects {
  display: flex;
  flex-direction: row;
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
  min-width: 100%;
}

#fronttext {
  width: 60%;
  text-align: justify;
  padding-bottom: 20px;
  margin-right: 50px;
  padding-right: 100px;
  margin-top: 0px;
  font-size: 18px;
  line-height: 34px;
  color: #1c2833;
}

#titleP {
  color: #351655a1;
  font-size: 24px;
  margin-bottom: 5px;
  text-align: center;

  font-weight: bold;
}

#bodyWrap {
  flex-direction: row;
  display: flex;
  justify-content: center;
  margin: auto;
  max-width: 1700px;
  align-items: center;
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
