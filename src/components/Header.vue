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
  background: #7999f0  ;
  /* Old browsers */
  background: -moz-linear-gradient(
    -45deg,
    #7999f0 10%,
    #668efd    50%,
    #7999f0  100%
  );
  /* FF3.6-15 */
  background: -webkit-linear-gradient(
    -45deg,
    #7999f0  10%,
      #668efd    50%,
     #7999f0  100%
  );
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(135deg,    #7999f0  10%,   #668efd   50%,   #7999f0  100%  100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */

  /* IE6-9 fallback on horizontal gradient */
  background-size: 350% 350%;
  animation: waveColors 8s ease infinite;
  /* End Wave Color */
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
  color: #ffffffb2;
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
  color: #ffffffd8;
}

a:hover {
  border-bottom: rgb(0, 0, 0) solid 1px;
  color:black;
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
  color: rgb(234, 250, 245);
  font-style: initial;
}

.linkA {
  color: #000000d0;
  font-weight: normal;
  text-decoration-line: none;
}

.linkA:hover {
  color: #000000;
  
  
 
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
  font-weight: lighter;
  font-style: italic;
  line-height: 24px;
  color: #ffffff;
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