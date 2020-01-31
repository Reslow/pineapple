<template>
  <Layout>
    <div id="tWrap">
       <div id="breadcrums">
      <h1><g-link class="Back" to="/">Back to homepage</g-link></h1>
      <h1 class="headline">About</h1>
      </div>
      <div class="profileImg">
        <div class="bildOchText">

          <div class="text">
          <h2 id="FirstLine">Hello</h2>
         <p class="colored"> My name is Fanny and I have a bachelor degree in interaction design from Linneaus University. I currently live in Gothenburg and are looking for new projects. If you are searching for a driven designer with passion for user research and interface design, lets talk! ;) 
            </p>

              
          </div>
          <g-image src="~/assets/images/profile_small.png" alt="Profile image" class="imageProfile" />
        </div>
        <a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin">LinkedIn</a>
      </div>

      <g-image src="~/assets/images/uxmodel.svg" alt="ux model image" class="imageUxModel" />

        

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
.imageUxModel{
  min-width: 40%;
  margin-right: auto;
  margin-left:auto;
  display: flex;
  align-items: center;
  margin-top:100px;
  margin-bottom: 100px;
  padding-bottom: 50px;
  
}

#firstLine{
  text-align: left;
  color: #000000d0;
  font-size: 24px;
}

#breadcrums{
  display: flex;
  flex-direction: row;
  margin-left: 20px;
  align-items: center;
}
#title {

  color: #000000;
  margin-bottom: 20px;
}
.spalt {
  display: flex;
  flex-direction: column;
  margin-bottom: 20px;
}

.back{
  color: #000000;
}

a{ 
  font-size: 18px;
   color:#030303d8;
  text-decoration: none;
  
  
}

a:hover{ 
    border-bottom: black solid 1px;

  
}


a:active{ 
  font-size: 18px;
  color: #000000;

}

.headline {
  margin-left: 30px;
  margin-bottom: 0px;
  padding-left: 60px;
  font-size: 18px;
   color:#292929d0;
  
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
  font-size: 24px;
  font-weight: bold;
 
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
  background-color: #ffffffd0;
 
}

.text {

  font-size: 18px;
  line-height: 34px;
  max-width: 50%;
  padding-bottom: 0px;
  margin-bottom: 0px;
  margin-top: 100px;
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

  color:#000000d0;
  
}



#linkedin {
  
  margin-top:25px;
  margin-bottom: 25px;
  letter-spacing: 1px;
  
  padding: 7px;
  padding-left: 8px;
  padding-right: 8px;
  cursor: pointer;
  border-radius: 5px;
 
  background-color:white;
   color: #1c2833;
  border: 2px solid  #1c2833;
  align-items: center;
  
  font-weight: bold;
  font-size: 16px;
  font-kerning: initial;
}

#linkedin:hover {
  box-shadow: 0 5px 8px 0 rgba(158, 153, 153, 0.473);
 border: solid #ffffff 2px;
  color: #ffffff;
  background-color: #1c2833;
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
  font-size: 18px;
  min-width:7%
  
}

.headline{
  font-size:18px;
  margin-right: 20px;
  margin-top:0px;
}
  

  .text {
    max-width: 80%;
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
