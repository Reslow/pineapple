<template>
  <Layout>
    <div id="tWrap">
       <div id="breadcrums">
      <h1><g-link class="Back" to="/">back to homepage</g-link></h1>
      <h1 class="headline">About</h1>
      </div>
      <div class="profileImg">
        <div class="bildOchText">

          <div class="text">
         <p class="colored"> My name is Fanny and I have a bachelor degree in interaction design from Linneaus University. I currently live in Gothenburg and are looking for new projects. If you are searching for a driven designer with passion for user research and interface design, lets talk! ;) 
            </p>

              
          </div>
          <g-image src="~/assets/images/profile_small.png" alt="Profile image" class="imageProfile" />
        </div>
        <a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin">Linkedin</a>
      </div>
    

      <div class="skills">
        <div class="skillsT">
          <h2>Designer</h2>
          <p class="skillsText">
            I am a good listener and I love working with people. I encourage new way of thinking.
            My curiosity keeps me redesigning and developing my design aesthetics and skills.
          </p>
        </div>
        <div class="skillsT">
          <h2>Interaction design</h2>
          <p class="skillsText">
           As part of the wide UX field, Interaction design focuses on the interaction between user and product. I use user research methods as foundation for interfaces that makes products useful
          </p>
        </div>
        <div class="skillsT">
          <h2>Toolbox</h2>
          <p class="skillsText">
            <ul>
            <li> Adobe Photoshop, Illustrator, InDesign, XD </li>
            <li> Axure RP</li>
            <li> UXPIn.</li>
            <li>CSS and HTML</li> 
            </ul>
          </p>
    
        </div>
      </div>
      </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "About"
  }
};
</script>

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


.bildOchText {
  display: flex;
  flex-direction: column;
  align-content: center;
  margin-right: auto;
  margin-left: auto;
  justify-content: center;
  align-items: center;
  margin-bottom: 50px;
}

#tWrap {
  
  min-height: calc(100vh - 100px);
}

h2 {
  margin-left: auto;
  margin-right: auto;
}



.skillsText {
  margin-left: 15px;
  margin-right: 15px;
  padding: 7px;
  margin-top: 15px;
  margin-bottom: 35px;
}

.skills {
  margin-top: 50px;
  display: flex;
  flex-direction: row;
  max-width: 70%;
  margin-left: auto;
  margin-right: auto;
  margin-bottom:300px;
}

.skillsT {
  display: flex;
  flex-direction: column;
  max-width: 30%;
  margin-left: auto;
  margin-right: auto;
 
  margin-bottom: 20px;

  text-align: left;
  font-size: 18px;
  line-height: 28px;
  border: #1c28333a 1px solid;
  border-radius: 5px;
  box-shadow: 0 5px 8px 0 #1c283359;
}

.text {
  
  color: #1c2833;
  font-size: 24px;
  line-height: 44px;
  max-width: 50%;
  padding-bottom: 10px;
  padding-left: 30px;
  justify-content: right;
}

.imageProfile {
  min-width: 120px;
  min-height: 120px;
  max-width: 30%;
  
}

.profileImg {
  display: flex;
  justify-content: center;
  align-items: center;
  
  flex-direction: column;
}

p {
  margin-bottom: 25px;
  color: #1c2833;
}



#linkedin {
  margin-left: auto;
  margin-right: auto;
  margin-top:25px;
  margin-bottom: 25px;
  border: solid #1c2833 3px;
  padding: 7px;
  padding-left: 8px;
  padding-right: 8px;

  cursor: pointer;
  border-radius: 5px;
  color: #1c2833;
  font-weight: bold;
  font-size: 16px;
  font-kerning: initial;
}

#linkedin:hover {
  box-shadow: 0 5px 8px 0 rgba(119, 119, 119, 0.473);
}

@media (max-width: 860px) {

  .skills{
    display: flex;
    flex-direction: column;

  }
  .skillsT {
    max-width: 100%;
  }

  .bildOchText {
    display: flex;
    flex-direction: column;
    align-content: center;
    margin-right: auto;
    margin-left: auto;
    justify-content: center;
  }

  .imageProfile{
    min-width:100%;
  }


a{ 
  font-size: 24px;
}

.headline{
  font-size:24px;
  margin-right: 20px;
}
  

  .text {
    max-width: 100%;
    padding-top: 20px;
    padding-bottom: 10px;
    padding-left: 20px;
    justify-content: right;
    text-justify: justify;
  }

  .skillsText {
    margin-left: 15px;
    margin-right: 15px;
    padding: 7px;
    margin-top: 15px;
    margin-bottom: 35px;
  }

  
}
</style>
