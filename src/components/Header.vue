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

 
 
  .nav{
    border: 4px solid   rgb(119, 103, 163);
  
    margin-left:30px;
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
  color:   rgb(119, 103, 163);

  
}
   
 

  
</style>