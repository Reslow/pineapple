<template>
  <Layout>
    <div id="bodyWrap">
      <div id="textwrap">
        <p id="fronttext">
          Hi, I am Fanny.
          <br />
          <br />I am educated in Interaction design.
          I like to solve problems by understanding users.
          <br />
          <br />I design interfaces with the aim of creating better interactions and experiences for users.
          <br />Read more
          <g-link class="linkA" to="/About">about</g-link> me
        </p>
      </div>
      <div id="cardwrap">
        <p id="titleP">UX Projects</p>
        <div id="cards">
          <g-link to="/projects/fidget">
            <div class="card">
              <div class="container">
                <g-image src="~/assets/images/pen.png" alt="icon" style="width:100%" />
                <div class="cardtext">
                  <p>A fidget concept</p>
                </div>
              </div>
            </div>
          </g-link>

          <g-link to="/projects/ar-concept">
            <div class="card">
              <div class="container">
                <g-image src="~/assets/images/Ar.png" alt="icon" style="width:100%" />
                <div class="cardtext">
                  <p>AR learning tool</p>
                </div>
              </div>
            </div>
          </g-link>

          <g-link to="/projects/my-forest-drone-app">
            <div class="card">
              <div class="container">
                <g-image src="~/assets/images/forest.png" alt="icon" style="width:100%" />
                <div class="cardtext">
                  <p>Forest drone app</p>
                </div>
              </div>
            </div>
          </g-link>

          <g-link to="/projects/vet-lab-app">
            <div class="card">
              <div class="container">
                <g-image src="~/assets/images/dog.png" alt="icon" style="width:100%" />

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
                <g-image src="~/assets/images/cityeventpattern.png" alt="icon" style="width:100%" />
              </div>
            </div>
          </g-link>

          <g-link to="/projects/for-kitchen">
            <div class="card">
              <div class="container">
                <g-image src="~/assets/images/forkitchenpattern.png" alt="icon" style="width:100%" />
              </div>
            </div>
          </g-link>
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
  color: #e24405;
  text-decoration-line: none;
}

.linkA:hover {
  color: #1c2833;
}

.cardwrap {
  display: flex;
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
.cardtext {
  position: absolute;
  bottom: 5px;
  left: 10px;
  font-size: 18px;
  line-height: 24px;
  color: white;
  font-weight: bold;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

#fronttext {
  width: 100%;
  text-align: left;
  padding-bottom: 20px;
  margin-right: 20px;
  margin-top: 0px;
  font-size: 24px;
  line-height: 34px;
  color: #1c2833;
}

#titleP {
  color: #1c283398;
  font-size: 36px;
  margin-bottom: 5px;
  text-align: center;

  font-weight: bold;
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
    margin-left: 8px;
    padding-top: 8px;
    margin-top: 10px;
    font-size: 24px;
    color: #1c2833;
  }

  #bodyWrap {
    flex-direction: column;
    display: flex;
    padding-bottom: 30px;
  }

  #textwrap {
    justify-content: center;
  }
}
</style>
