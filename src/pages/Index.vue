
  


<template>
  <Layout class="Layout">
  
  
    <div id="bodyWrap">
    <div id="textwrap">
    <h1 id="hdFirst"> UX & interaction designer</h1>
    <p id="fronttext">
    My passion is to design useful interfaces for better interactions of users. Whith my knowledge I have tools for shaping and redesign user experience with focus on 
    Interactions between user and interface.   // Fanny 
    </p>
    </div>
    <div id="cardwrap">

      
<div id="cards">
   
  <div class="card" v-for="edge in $page.projects.edges" :key="edge.node.id" :post="edge.node">   

    <img :src="edge.node.cover.src" alt="AR icon" style="width:20%">
      <div class="container">
        <g-link :to="edge.node.path" class="project-link">
          <h4><b>{{edge.node.title}}</b></h4>
        </g-link>
        <p>{{edge.node.description}}</p>

    </div>
  </div>
     
  </div>
  </div>
    </div>
   
  



  </Layout>

</template>

<page-query>
query Posts {
	projects: allProjectPost {
    edges {
      node {
        title
        description
        cover
        path
      }
    }
  },
}
</page-query>

<script>
export default {
  metaInfo: {
    title: 'Portfolio'
  },
}




</script>

<style>




#cards{
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  width: 600px;
 

}

#fronttext{
  text-align: justify;
}

#textwrap{
  padding-right: 30px;
  text-align: right;
}
#bodyWrap{
  
  flex-direction: row;
  display: flex;
  justify-content: center;
  

}
.card {

  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  padding-top:0px;
  margin-left: 10px;
  margin-left: 10px;
  margin-top:30px;
  padding-bottom: 20px;
  height:250px;
  width:250px;
  width:ww;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}


.container {
  padding: 10px 16px;
}


.home-links a {
  margin-right: 3rem;
}

#cardwrap{
  display: flex;
  flex-direction: column;
}
#hdFirst{
color: rgb(10, 10, 10);
margin-right:20px;
margin-left: 0px;
text-align: right;
font-size: 67px;

}
</style>
