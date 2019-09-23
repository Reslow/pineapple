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
  margin:0;
  padding:0;
  line-height: 1.5;
  margin: auto;
}



.wrap {
  max-width: 800px;
  display: flex;
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
  font-size: 10px;
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
  
  height: 80px;
}

.nav__link {
  margin-left: 20px;
  margin-right: 40px;
}



a{
  color:  rgb(0, 0, 0);
  text-decoration:none;
}

a.button{
  color:  rgb(119, 103, 163);
}
</style>
