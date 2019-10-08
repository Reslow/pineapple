<template>
  <header class="header">
    <g-link id="name" to="/">
      <span class="nametext">Fanny Reslow</span>
      <span class="nametext">UX &amp; Interaction designer</span>
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

#name{

 
}
 
  .nav{
    border: 4px solid   rgb(0, 0, 0);
  
    margin-left:10px;
    padding:4px;
    padding-left:8px;
    padding-right: 8px;
    cursor: pointer;
    border-radius: 5px;
    display: inline-block;
    display:flex;
    font-size: 12px;

  }
  .base{
    margin-right: 100px;
    display: inline-block;
    display:flex;
  }

.nametext{
  color: rgb(0, 0, 0);
  font-size: 1em;
  padding-bottom: 5px;
}

@media (max-width: 860px){
  .nametext{ font-size: 12px;}
  .header{
    padding-top:10px;
  }
  .button {
    font-size: 12px;
    color: black;
  }

}
   
 

  
</style>