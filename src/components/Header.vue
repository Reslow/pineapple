<template>
  <header class="header">
    

    <div id="textwrap">
        <p id="fronttext">
          <br />
          <br />I design interfaces with the aim of creating better experiences for users.
          <br /> <br> Check out my site and read more 
          <g-link class="linkA" to="/About">about</g-link>&nbsp;me.

        </p>
      </div>
        
      
  
  </header>
</template>

<style scoped>

.linkA {
  color: #eb1e62;
  font-weight: normal;
  text-decoration-line: none;
}

.linkA:hover {
  color: #eaf5ff;
}


#textwrap {

  margin-left: auto;
  margin-right: auto;
  padding-top: 130px;
  padding-bottom: 130px;
  max-width: 900px;
}

#fronttext {
  
  text-align: left;
  padding-bottom: 20px;
  margin-top: 0px;
  font-size: 24px;
  font-weight:lighter;
  line-height: 24px;
  color: #ffffff;
}

header{
  background-image: linear-gradient(#2b094b,#200d55)
}

@media (max-width: 860px) {
  .nametext {
    font-size: 14px;
  }
  .header {
    padding-top: 10px;
  }
  .nav {
    margin-left: 5px;
  }
}
</style>