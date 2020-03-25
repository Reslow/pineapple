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
 
  background-color:#ffffff;
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

@media (max-width: 800px) {

  #app{
    display:flex;
    height:100%;
    width:100%;
  }
}





</style>
