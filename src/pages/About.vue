<template>
  <Layout>
    
   
    <div id="tWrap">
  
    <h1 class="headline">About</h1> 
      <div class="profileImg">
      <img src="../../static/png/profileround.png" alt="Profile image" class="ImageProfile" >
<a href="https://linkedin.com/in/fanny-reslow-39491a153/" id="linkedin"> Linkedin </a>
      </div>
    <div class="text">
    <p>As a UX  and interaction designer I am always focused on the user, what the user wants and more important the users needs. I am a good listener and I am good at shifting perspectives when thinking of design, this give more depth to the thoughts behind the design. I know how to conduct user research and how to produce products depending on user research. I have a bachelor degree in interaction design (informatics) at Linneaus University. I have been working with the design process from idea to interactive prototypes in various projects during my education.</p>
 </div>

  
  <h2 class="headline">Skills</h2> 
 <div class="list">
    <div class="listGroup">
    <p class="listItem"> User centered design</p>
    <p class="listItem"> User research</p>
    <p class="listItem" >Prototyping</p>
    </div>
      <div class="listGroup">
    <p class="listItem" >Interface design</p>
    <p class="listItem" >Design patterns</p>
      </div>
       <div class="listGroup">
    <p class="listItem" >Project management</p>
    <p class="listItem">Scrum</p>
       </div>
        <div class="listGroup">
    <p class="listItem">Social media</p>
        </div>
         <div class="listGroup">
    <p class="listItem">Joomla(CMS)</p>
    <p class="listItem" >UXPin</p>
    <p class="listItem">Axure RP</p>
    <p class="listItem">Adobe (Ps,Ai,Id & XD</p>
    <p class="listItem">HTML, CSS & Javascript</p>
         </div>
 </div>
   
  <h2 class="headline">Education</h2>
  <div class="listGroup">
  <p class="ItemEducation">Linneaus University - Interaction design (Bachelor degree) 2016 - 2019</p>
   <p class="ItemEducation">It-Media Gymnasiet (upper secondary shool) - digital media technology  2008 - 2011</p>
  </div>


 </div>
  </Layout>

</template>

<script>
export default {
  metaInfo: {
    title: 'About'
  }
}
</script>

<style>
@media (max-width: 860px){

  
  .text {
    
    padding:20px;
    text-align: justify;
    font-size: 16pt;
    
  }

   p.ItemEducation{
    
    padding-bottom: 5px;
  }

  .wrap{
    padding:10px;
  }

  .profileImg {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top:5px;
    flex-direction:column;
  }
 
  
  .listGroup{
    width: 50%;
    padding-bottom: 15px;
  }
  
}

.ImageProfile{
    min-width: 120px;
    min-height: 120px;

  }

.profileImg {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top:5px;
  padding-bottom: 20px;
  flex-direction:column;
}

p {
  margin:0px;

}



.list{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;  
}


.listItem{
  color: rgb(10, 10, 10);
  font-size: 14pt;
  font-weight: bold;
  padding:5px;
}

.ItemEducation{
   color: rgb(0, 0, 0);
  font-size: 14pt;
  font-weight: bold;
  margin: 10px;
}

.headline{
  padding-top: 20px;
  margin: 0px;
  font-size: 36pt;
}

#linkedin{ 
  border: 4px solid    rgb(119, 103, 163);
    margin-left: 10px;
    padding:4px;
    padding-left:8px;
    padding-right: 8px;
    margin-top: 20px;
    cursor: pointer;
    border-radius: 5px;
    color:   rgb(119, 103, 163);
    font-size: 14pt;
}
</style>
