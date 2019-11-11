<template>
  <Layout>
     <div class="myUi">
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
.uiImage{
  max-width:70%;
  margin-left:auto;
  margin-right: auto;
}

.myUi{
  display:flex;
  align-content: center;
}
</style>