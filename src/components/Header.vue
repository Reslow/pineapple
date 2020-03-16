<template>
  <header class="header">
    <div id="textwrap">
     
      <p id="fronttext">
        
        <br />I design interfaces with the aim of creating better experiences for users.
        
       
      </p>
    
    
      
      
    </div>
  </header>
</template>

<style scoped>
.header {
  

  background-color:  #ff2e85d0;;
  
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  text-align: center;
  margin: 0 auto;
}


#navContent {
  display: flex;
  flex-direction: row;
  margin-left: 0px;
  padding-bottom: 0px;
  margin-bottom: 0px;
  font-size: 14px;
  position: absolute;
  bottom: 0px;
  align-items: center;
  align-self: center;
}



#textwrap {
 
 
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  align-items: baseline;
}

#fronttext {
  text-align: left;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 0px;
  padding-bottom: 10px;
  margin-top: 0px;
  font-size: 18px;
  font-weight: normal;

  color: #ffffff;
}

@media (max-width: 860px) {

  #textwrap{
    padding-top:30px;
  }
  .nametext {
    font-size: 14px;
  }
  .header {
    padding-top: 10px;
  }


#fronttext{
   margin-left: 25px;
  margin-right: 25px;
  justify-content: left;
  padding-bottom:30px;
  padding-left:0px;
  font-size:28px;
  line-height: 36px;

}
  .nav {
    margin-left: 15px;
  }

  a.link{
    margin-left:15px;
  }
}
</style>