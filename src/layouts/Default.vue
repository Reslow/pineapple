<template>
  <div class="layout">
    <Header />
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
import Header from "../components/Header";

export default {
  components: {
    Header
  }
};
</script>

<style>
body {
  font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  font-size: 14px;
  margin: 0;
  padding: 0;
  margin: auto;
  background-color: #ffffff;
  min-height: 100vh;
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

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 100px;
}

.nav__link {
  margin-left: 10px;
  margin-right: 10px;
}

a {
  color: #131313d3;
  text-decoration: none;
}

a.button {
  
 
  padding-left: 20px;
  padding-right: 20px;
  padding-top: 5px;
  padding-bottom: 3px;
  border-radius: 5px;
  margin-left: 10px;

  cursor: pointer;
  display: inline-block;
  display: flex;
  font-size: 18px;
  font-weight: bold;
  color: rgb(46, 42, 42);

  border-radius: 5px;
  transition: 0.3s;
}

a.button:hover {
  box-shadow: 0 5px 8px 0 rgba(0, 0, 0, 0.199);
}


</style>
