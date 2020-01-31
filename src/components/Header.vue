<template>
  <header class="header">
    <div id="textwrap">
      <p id="headerHeadline">Welcome to my website, I am Fanny</p>
      <p id="fronttext">
        <br />
        <br />I design interfaces with the aim of creating better experiences for users.
        <br />
        <br />Check out my site and find out more
        <g-link class="linkA" to="/About">about</g-link>&nbsp;me.
      </p>
    </div>
    <div id="navContent">
      <div class="name">
        <p>reslowf@gmail.com</p>
      </div>

      <div class="nav">
        <g-link class="link" to="/">Home</g-link>
        <g-link class="link" to="/about">About</g-link>
      </div>
    </div>
  </header>
</template>

<style scoped>
.header {
  background: #ffffff  ;

  background: linear-gradient(135deg,    #b2c3f1 10%,   #b2f1e9    50%,   #cef1b2   100%  100%);
  
  background-size: 350% 350%;
  animation: waveColors 8s ease infinite;
 
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  text-align: center;
  margin: 0 auto;
}

@-webkit-keyframes waveColors {
  0% {
    background-position: 0% 7%;
  }
  50% {
    background-position: 100% 94%;
  }
  100% {
    background-position: 0% 7%;
  }
}

@keyframes waveColors {
  0% {
    background-position: 0% 7%;
  }
  50% {
    background-position: 100% 94%;
  }
  100% {
    background-position: 0% 7%;
  }
}

#navContent {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-left: 0px;
  padding-bottom: 0px;
  margin-bottom: 0px;
  font-size: 14px;
  position: absolute;
  bottom: 0px;
}

.name {
  color: #2c2c2cb2;
  margin-right: 0px;
  margin-bottom: 8px;
  margin-left: 15px;
  font-size: 14px;
  font-weight: bold;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

a {
  text-decoration-line: none;
  color: #000000d8;
}

a:hover {
  border-bottom: rgb(0, 0, 0) solid 1px;
  color:rgb(0, 0, 0);
}

p {
  margin-left: 0px;
}

.nav {
  display: flex;
  flex-direction: row;
  font-weight: bold;
  
}

.link {
  cursor: pointer;
}

#headerHeadline {

  padding-top: 30px;
  font-size: 36px;
  font-weight: bolder;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  color: rgb(0, 0, 0);
  font-style: initial;
}

.linkA {
  color: #ff4949d0;
  font-weight: normal;
  text-decoration-line: none;
}



#textwrap {
  padding-top: 130px;
  padding-bottom: 130px;
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
  padding-bottom: 20px;
  margin-top: 0px;
  font-size: 24px;
  font-weight: normal;
  line-height: 24px;
  color: #000000;
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

  #headerHeadline {
  font-size: 24px;
  text-align: left;
  margin-left: 25px;
  margin-right: 25px;
}

#fronttext{
   margin-left: 25px;
  margin-right: 25px;
  justify-content: left;
  padding:0px;
  font-size:18px

}
  .nav {
    margin-left: 15px;
  }

  a.link{
    margin-left:15px;
  }
}
</style>