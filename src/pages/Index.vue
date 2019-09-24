
  


<template>
  <Layout class="Layout">
    <div id="bodyWrap">
    <div id="textwrap">
    <h1 id="hdFirst"> UX & interaction designer</h1>
    <p id="fronttext">
 My name is Fanny and I am a designer of the interaction between users and products. My passion and curiosity of human behavior and the future of technology drives me to keep develop my skills and knowledge of the areas. I have an education in interaction design. I design with the aim of creating better interactions and experiences for users.  Check out a few of my earlier projects. 
// Fanny

    </p>
    </div>

    
 <div id="cardwrap">

      
<div id="cards">
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
  title: 'Portfolio',
}
}





</script>



<style>

#textwrap{
  display: flex;
  flex-direction: column;
  margin: 10px;

  
}

#cards{
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: center;
  width: 600px;
}

.cardtext{
   color:   rgb(119, 103, 163);
}


#fronttext{
  text-align: left;
  padding-top: 40px;
  margin-right: 20px;
  margin-top:0px;

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
  padding-left: 5px;
  padding-top: 5px;
  margin-left: 5px;
  margin-top: 5px;
  padding-bottom: 20px;
  height:250px;
  width:250px;
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

#cardwrap{
  display: flex;
  flex-direction: row;
}
#hdFirst{
color:  rgb(0, 0, 0);

margin-bottom: 0px;
text-align: left;
font-size: 96px;

}
@media (max-width: 860px){
#cards{
  align-content: center;
  flex-wrap: wrap;
  flex-direction: row;
  padding-bottom: 10px;
  margin-top: 2rem;

}

.container{
    padding: 0px 0px;
}
#bodyWrap{
  
  flex-direction: column;
  display: flex;
  justify-content: center;
}

}
</style>
