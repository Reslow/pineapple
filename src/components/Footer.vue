<template>
  <footer class="footer">
    <div id="footerContent">
      <div class="name">
        <p>reslowf@gmail.com</p>
      </div>

      <div class="nav">
        <g-link class="link" to="/">Home</g-link>
        <g-link class="link" to="/about">About</g-link>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      social: [
        {
          icon: "linkedin",
          link: "https://www.linkedin.com/in/fanny-reslow-39491a153/"
        }
      ]
    };
  }
};
</script>


<style>
.footer {
  margin-top: 80px;
  flex-shrink: 0;
}

#footerContent {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding-bottom: 0px;
  margin-bottom: 0px;
  font-size: 14px;
}

footer a {
  color: #1c2833d8;
}

footer a:hover {
   color: #e24405;
}

.name {
  color: #1c283398;
  margin-left: 100px;
  margin-right: 0px;
  font-size: 14px;
  font-weight: bold;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

.nav {
  color: rgb(252, 252, 252);
  margin-left: 40px;
  display: flex;
  flex-direction: row;
  font-weight: bold;
}

.link {
  margin-left: 100px;
  cursor: pointer;
}
</style>