<template>
  <Layout>
   <div class="myUi">
     <div id="breadcrums">
      <h1><g-link class="Back" to="/">back to homepage</g-link></h1>
      <h1 class="headline">UI design</h1>
      </div>
     <g-image src="~/assets/images/cityevent.png" alt="city event image" class="uiImage"/>
   </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "City-Event"
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



a{ 
  font-size: 18px;
  color: #1c2833;
  text-decoration: none;
  
  
}

a:hover{ 
  font-size: 18px;
  color:   #008080;
  
}


a:active{ 
  font-size: 18px;
  color: #1c2833;

}

.headline {
  
  
  font-size: 18px;
 color:  #351655a1;
  margin-left: 30px;
  margin-bottom: 0px;
}

.uiImage{
  max-width:80%;
  margin-left:auto;
  margin-right: auto;
}

.myUi{
  display:flex;
  align-content: center;
   flex-direction: column;
}

@media (max-width: 800px) {


.headline{
  font-size:18px;
  margin-right: 10px;
}
}

</style>