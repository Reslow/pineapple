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
         <p class="colored"> My name is Fanny I have a bachelor degree in interaction design from Linneaus University. I currently live in Gothenburg and are looking for new projects. If you are searching for a driven designer with passion for user research and interface design, lets talk! ;) 
            </p>
            <p class="colored">
              I have practice interaction design through various projects. From defining problem and user need in context to validate prototype with users. 
              I want to learn more and I want to share my knowledge with others. I want to work with the design process from start to finish. 
              </p>
              <p class="colored"> 
                When I have time left I focus on exploring my design easthetic, new design trends and updating this website. I try to explore new tools, such as figma. 
                I am used to work with Illustrator and adobe XD.  I know my way around the adobe suit, UXPin and Axure RP for more interactive prototypes. 
                
              </p>

              
          </div>
          <g-image src="~/assets/images/profile.png" alt="Profile image" class="imageProfile" />
        </div>
        <a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin">LinkedIn</a>
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



#FirstLine{
  text-align: left;
color: #34079c;
  font-size: 44px;
  font-weight: lighter;
}




.text {

  font-size: 18px;
  line-height: 34px;
  max-width: 60%;
  padding-bottom: 0px;
  margin-bottom: 0px;
  margin-top: 50px;
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
    margin-top:10px;
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
