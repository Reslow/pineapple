<template>
  <div class="layout">
    <div class="wrap">
     
      <slot />
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


export default {
  components: {
  
  
  }
};
</script>

<style>
body {
  min-height: 100vh;
  font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  font-size: 14px;
  margin: 0PX;
  padding: 0PX;
 
  background-color: #ffffff;
}

body,
html {
  height: 100%;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100%;
}

.wrap {
  flex: 1 0 auto;
}

#name {
  padding-top: 0px;
  padding-bottom: 0px;
  padding-left: 20px;
  margin-top: 0px;
  margin-bottom: 0px;
  display: flex;
  flex-direction: column;
  font-size: 14px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

#nametext {
  padding-top: 3px;
  margin-top: 0px;
  padding-top: 0px;
  padding-bottom: 0px;
  margin-bottom: 0px;
}




</style>
