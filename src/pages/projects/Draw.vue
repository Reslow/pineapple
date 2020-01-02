<template>
  <Layout>
     <div class="myUi">
       <div id="breadcrums">
      <h1><g-link class="Back" to="/">back to homepage</g-link></h1>
      <h1 class="headline">UI Design</h1>
      </div>
          <g-image src="~/assets/images/draw.png" alt="Draw image" class="uiImage" />
   </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Draw"
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
  color:   #e24405;
  
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

.uiImage{
  max-width:70%;
  margin-left:auto;
  margin-right: auto;
}

.myUi{
  display:flex;
  align-content: center;
   flex-direction: column;
}
</style>