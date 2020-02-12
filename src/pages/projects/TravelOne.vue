<template>
  <Layout>
   <div class="myUi">
     <div id="breadcrums">
      <h1><g-link class="Back" to="/">Back to homepage</g-link></h1>
      <h1 class="headline">UI Design</h1>
      </div>
     <g-image src="~/assets/images/travelonea.png" alt="Travel site image" class="uiImage" />
     <g-image src="~/assets/images/traveloneb.png" alt="For kitchen image" class="uiImage" />
     <g-image src="~/assets/images/travelonec.png" alt="For kitchen image" class="uiImage" />

   </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Travel-One"
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
  font-size: 18px;
   color:#c70053d0;
  text-decoration: none;
  font-weight: normal;
  
  
}

a:hover{ 
  font-size: 18px;
   color: #1c2833;
  
}


a:active{ 
  font-size: 18px;
  color: #1c2833;

}

.headline {
  
 
  font-size: 18px;
 color:#292929d0;
  margin-left: 30px;
  margin-bottom: 0px;
  font-weight: normal;
}

.uiImage{
 margin-top:20px;
  max-width:90%;
  margin-left:auto;
  margin-right: auto;
}

.myUi{
  display:flex;
  flex-direction: column;
  align-content: center;
  padding-bottom:200px;
}

@media (max-width: 800px) {


.headline{
  font-size:18px;
  margin-right: 10px;
}
}

</style>