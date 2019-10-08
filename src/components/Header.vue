<template>
  <header class="header">
    <g-link id="name" to="/">
      <span class="nametext">Fanny Reslow</span>
      <span class="nametext2">UX &amp; Interaction designer</span>
      <span class="nametext">reslowf@gmail.com</span>
    </g-link>
   
   
      
    <div  class="base">

    <nav class="nav">
      <g-link class="button" to="/">Home</g-link>
    </nav>
    <nav class="nav">
      <g-link class="button" to="/About">About</g-link>
    </nav>
    </div>

    
     

  </header>
</template>

<style>


 
  .nav{
  
  
border:solid rgba(0, 0, 0, 0.596) 7px;
    
  
    margin-left:10px;
    
    padding-left:10px;
    padding-right: 10px;
    padding-bottom:4px;
    cursor: pointer;
    border-radius: 5px;
    display: inline-block;
    display:flex;
    font-size: 18px;
    font-weight: bold;
    

  }
  

  .base{
    margin-right: 100px;
    display: inline-block;
    display:flex;
  }

  #name{
  border-bottom:solid rgba(0, 0, 0, 0.432) 7px;
  

  }

.nametext{
  color:rgba(0, 0, 0, 0.596); 

  font-size: 18px;
  font-weight: bolder;
  padding-bottom: 5px;
}
.nametext2{
  color:rgba(0, 0, 0, 0.466); 

  font-size: 18px;
  font-weight: bolder;
  padding-bottom: 5px;
}

@media (max-width: 860px){
  .nametext{ font-size: 18px;}
  .header{
    padding-top:10px;
  }
  .nav{
    margin-left:5px;
  }
  
   
  

}
   
 

  
</style>