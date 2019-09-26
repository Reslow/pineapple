
  


<template>
  <Layout class="Layout">
    <div id="bodyWrap">
    <div id="textwrap">
    <h1 id="hdFirst"> UX & interaction designer</h1>
    <p id="fronttext">
 My name is Fanny and I am a designer of interaction between users and products. I have an education in interaction design. I design with the aim of creating better interactions and experiences for users. 
    </p>
    </div>

    
 <div id="cardwrap">

      
<div v-if="$page" id="cards">
  <g-link v-for="edge in $page.projects.edges" :key="edge.node.id" :to="edge.node.path" >
    <div class="card">
      <div class="container">
        <img :src="edge.node.cover.src" alt="icon" style="width:20%">
        <div class="cardtext">
        <h4 class="CardTitle">{{edge.node.title}}</h4>
        <p>{{edge.node.description}}</p>
        </div>
      </div>
    </div>
  </g-link>
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
    title: ' Fanny Reslow Portfolio',
}
}

</script>

<style>



.wrap{
  max-width: 1000px;
}

#textwrap{
  display: flex;
  flex-direction: column;
  margin: 10px;
  max-width: 600px;  
}

#cards{
  flex-wrap: wrap;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.cardtext{
   color:   rgb(119, 103, 163);
}

#fronttext{
  text-align: left;
  padding-top: 40px;
  margin-right: 20px;
  margin-top:0px;
  font-size: 18px;

}


#bodyWrap{
  
  flex-direction: row;
  display: flex;
  justify-content: center;
 

}
.card {

  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  padding-top:8px;
  padding-left: 8px;
  padding-top: 8px;
  margin-left: 8px;
  margin-top: 8px;
  padding-bottom: 20px;
  max-width:250px;
  min-height: 300px;
  min-width: 250px;
  
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.cardtext{
  margin-left: 10px;

}

.container {
  padding: 10px 16px;
  
}


.home-links a {
  margin-right: 3rem;

}

#hdFirst{
color:  rgb(0, 0, 0);
margin-bottom: 0px;
text-align: left;
font-size: 60px;
}

@media (max-width: 800px){
#cards{
  align-items: center;
  padding-bottom: 10px;
  margin-top: 2rem;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content:center;
}

#fronttext{
  text-align: left;
  padding-top: 8px;
  margin-right: 20px;
  margin-top:0px;
  font-size: 16px;
}

#hdFirst{
color:  rgb(0, 0, 0);
margin-bottom: 0px;
text-align: left;
font-size: 40pt;
margin-top: 15px;
}

#bodyWrap{
  
  flex-direction: column;
  display: flex;

}

#textwrap{
  justify-content: center;
}


}
</style>
