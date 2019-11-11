<template>
  <Layout>
   <div class="myUi">
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

.uiImage{
  max-width:80%;
  margin-left:auto;
  margin-right: auto;
}

.myUi{
  display:flex;
  align-content: center;
}

</style>