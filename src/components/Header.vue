<template>
  <header class="header">
    <div id="textwrap">
      <p id="headText">
        Hi! I am Fanny, I design interfaces with the aim of creating
        great experiences for users.
      </p>
      <div id="box"></div>
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

#box{
  height: 300px;
  width: 300px;
  margin:50px;
  border-radius: 60%;;
  
}

#headText {
  width: 50%;
  text-align: left;
  padding-left: 200px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 150px;
  font-size: 44px;
  font-weight:bold;
  color: #3b3b3b;
}

@media (max-width: 800px) {

  #headText{
    margin-left: 15px;
  }
}
</style>