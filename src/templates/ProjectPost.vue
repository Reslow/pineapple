<template>
  <Layout>
    <div class="project">
      <div class="container">
        <div class="project-header">
          <h1 class="project-title" v-html="$page.post.title"/>
          <div class="project-content-container">
            <div v-html="$page.post.content" class="project-content"/>
          </div>
        </div>
      </div>
    </div>
  </Layout>
</template>

<page-query>
query ProjectPost ($path: String!) {
  post: projectPost (path: $path) {
    title
    content
  }
}
</page-query>

<script>
export default {
  metaInfo() {
    return {
      title: this.$page.post.title,
    }
  },
}
</script>

<style scoped>
@media (max-width: 760px){
  .project {
  color: rgb(39, 39, 39);

   padding: 20px;
  }

  .project-content{
    font-size:14px;
    margin-left:15px;
    margin-right: 15px;
    justify-content: center;
 
    
  }

}
.container{
  padding:10px;
  justify-content: center;

}

  .wrap{
    padding:0px;
    justify-content: center
  }

.project{
  text-align:justify;
  padding:0px;
  align-content: center;
  max-width: 800px;
  



}

.project-title {
  margin-bottom:15px;
  font-size: 36px;
  letter-spacing: 0px;
  word-spacing: 0px;
  margin: 0px;
  text-align: left;
  color:#7767a3;
  
   
  
}
</style>