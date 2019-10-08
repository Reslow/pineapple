<template>
  <div class="layout">
      <Header />
    <div class="wrap">
      <slot/>
    </div>
  </div>
 
</template>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

<script>
import Header from '../components/Header';

export default {
  components: {
    Header
  }
}
</script>

<style>
body {
  font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  font-size: 14px;
  margin:0;
  padding:0;
  margin: auto;

  background-image: linear-gradient(rgb(255, 255, 255),rgb(255, 255, 255));
}



.wrap {
  max-width: 800px;
  margin: auto;
 
 
}

#name {
  Padding-top:0px; 
  padding-bottom: 0px;
  padding-left:20px;
  margin-top:0px;
  margin-bottom:0px;
  display: flex;
  flex-direction: column;
  font-size: 14px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
#nametext{ 
  padding-top:3px;
  margin-top:0px;
  Padding-top:0px; 
  padding-bottom: 0px;
  margin-bottom: 0px;
  
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 100px;
  
 
}

.nav__link {
  margin-left: 20px;
  margin-right: 40px;
}

img {
  max-width: 82vw;
}

a{
  color:  rgb(0, 0, 0);
  text-decoration:none;
}

a.button{
  color: #505050d3;
  border: solid #505050a2 5px;
  padding-left:20px;
  padding-right: 20px;
  padding-top:5px;
  padding-bottom:3px;
  border-radius: 5px;
  margin-left:10px;

  cursor: pointer;
 display: inline-block;
   display:flex;
  font-size: 18px;
 font-weight: bold;
  

  border-radius: 5px;
  transition: 0.3s;

}


a.button:hover {
  box-shadow: 0 8px 16px 0 rgba(146, 146, 146, 0.2);
}

@media (max-width: 800px){
  a.button{
    color: #505050d3;
  border: solid #505050a2 5px;
  padding-left:10px;
  padding-right: 10px;
  padding-top:5px;
  padding-bottom:3px;
  border-radius: 5px;
  margin-left:5px;
  font-size: 18px;

  
}
}
</style>
