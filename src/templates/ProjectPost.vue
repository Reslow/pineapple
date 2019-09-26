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
@media (max-width: 860px){
  .project {
  color: rgb(0, 0, 0);
   align-content:center;
   padding: 20px;
  }

  .project-content{
    font-size:14pt;
    margin-left:15px;
    margin-right: 15px;
  }

}
.container{
  padding:10px;

}

  .wrap{
    padding:0px;
  }

.project{
  text-align:justify;
  padding:0px;
}

.project-title {
  margin-bottom:15px;
  font-size: 36pt;
  letter-spacing: 0px;
  word-spacing: 0px;
  margin: 0px;
  text-align: left;
  
   
  
}
</style>