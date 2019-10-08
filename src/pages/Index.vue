
  


<template>
    <div id="bg">
          <div id="bg2">
  <Layout>
      
  
    <div id="bodyWrap">

    
    <div id="textwrap">
    <h1 id="hdFirst"> UX & interaction designer</h1>
    
    <p id="fronttext">
   I design interfaces with the aim of creating better interactions and experiences for users.  
    </p>
    </div>
 <div id="cardwrap">
   <p id="titleP">Projects</p>

      
<div v-if="$page" id="cards">
  <g-link v-for="edge in $page.projects.edges" :key="edge.node.id" :to="edge.node.path" >
    <div class="card">
      <div class="container">
        <img :src="edge.node.cover.src" alt="icon" style="width:20%">
        <div class="cardtext">
      
        <p>{{edge.node.description}}</p>
        </div>
      </div>
    </div>
  </g-link>
 </div>
   
</div>

 </div>
  </Layout>
    </div>
    </div>


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

#credit{
margin-top:200px;
margin-left:10px;

}


.wrap{
  max-width: 1000px;

  margin: auto;
}

#textwrap{
  display: flex;
  flex-direction: column;
  margin: 10px;
  max-width: 600px;  
  padding:10px;
}

#cards{
  flex-wrap: wrap;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.cardtext{
  padding-top:10px;
   color: #7767a3;
   font-size: 18px;
   font-weight:bold;
   text-align: left;
   font-family: helvetica;
  
}




#fronttext{
  text-align: justify;
  padding-top: 40px;
  margin-right: 20px;
  margin-top:0px;
  font-size: 24px;
  font-weight: bold;
  color:white;
  padding-bottom: 5px;

   border-bottom: 5px solid rgba(198, 253, 0, 0.596);

}


#titleP{
  color:rgba(198, 253, 0, 0.63);
  font-size: 36px;
  margin-bottom: 5px;
  padding-left:10px;
  font-weight: bold;
}

   


#bg2{
background-image:
linear-gradient(to bottom, rgba(252, 250, 250, 0.89), rgba(49, 49, 49, 0.918),rgba(37, 37, 37, 0.952)),
url(../../static/walking.png );
background-repeat:no-repeat;
background-size: cover;

min-height:100vh;

 
}



#bodyWrap{
  
  flex-direction: row;
  display: flex;
  justify-content: center;
  margin: auto;
 

}
.card {

  box-shadow: 0 4px 8px 0 rgba(216, 216, 216, 0.521);
  border-radius: 5px;
  transition: 0.5s;
  padding-top:15px;
  padding-left: 8px;
  padding-top: 8px;
  margin-left: 8px;
  margin-top: 8px;
  padding-bottom: 20px;
  max-width:250px;
  min-height: 220px;
  min-width: 200px;
  background-image: linear-gradient(rgb(224, 224, 224),rgb(233, 233, 233));
  
  
 
  
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  
}

.cardtext{
  margin-left: 10px;
  margin-top:20px;
  
  border-bottom: #7767a3 1px solid;

}

.container {
  padding: 10px 16px;
 
}


.home-links a {
  margin-right: 3rem;

}

#hdFirst{
color:  rgb(255, 255, 255);
margin-bottom: 0px;
text-align: right;
font-size: 80px;

}

@media (max-width: 800px){
  #credit{
margin-top:20px;
display: inline-block;
margin:auto;

}
#cards{
  align-items: center;
  padding-bottom: 10px;
  margin-top: 2rem;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content:center;
}




#bg2{
background-image:
linear-gradient(to bottom, rgba(252, 250, 250, 0.671), rgba(49, 49, 49, 0.918),rgba(37, 37, 37, 0.753)),
url(../../static/walking.png);
background-repeat:no-repeat;
background-size: cover;
min-height:100vh;

 
}

#fronttext{
  text-align: justify;
  padding-top: 8px;
  margin-top:0px;
  font-size: 16px;
  color: white;
}

#hdFirst{
color:  rgb(255, 255, 255);
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
