<template>
  <header class="header">
    <div id="textwrap">
      <p id="headText">
        Hi! I am Fanny, I design interfaces with the aim of creating
        
great experiences for users.
      </p>
    </div>
  </header>
</template>

<style scoped>

.header{  
height: 500px;
}

#textwrap {
  display: flex;
  flex-direction: column;
  align-items: baseline;
}

#headText {
  width: 50%;
  text-align: left;
  margin-left: 40px;
  margin-bottom: 0px;
  padding-left:20px;
  padding-right:20px;
  font-size: 44px;
  font-weight:bold;
  color:  #505050;
}

@media (max-width: 800px) {

  #headText{
    margin-left: 15px;
  }
}
</style>