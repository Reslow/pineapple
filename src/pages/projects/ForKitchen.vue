<template>
  <Layout>
   <div class="myUi">
     <g-image src="~/assets/images/forkitchen.png" alt="For kitchen image" class="uiImage" />
   </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "For-kicthen"
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