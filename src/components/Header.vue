<template>
  <header class="header">
    <div id="textwrap">
      <p id="headText">
        Hi! I am Fanny, I design interfaces with the aim of creating
        <br />
great experiences for users.
      </p>
    </div>
  </header>
</template>

<style scoped>
.header {
  background-color: 
  #ffffffd0;
  width: 100%;
  text-align: center;
  
}


#textwrap {
  display: flex;
  flex-direction: column;
  align-items: baseline;
}

#headText {
  text-align: left;
  margin-left: 40px;
  margin-bottom: 0px;
  margin-top: 5pxpx;
  padding-top:10px;
  padding-bottom:10px;
  font-size: 16px;
  font-weight: bolder;
  color:  #db0c51d0;
}

@media (max-width: 860px) {
}
</style>