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


.project{
  
    text-align:justify;
   
}
.project-title{
  margin:0px;
  padding:0px;
}



</style>