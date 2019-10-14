<template>
  <header class="header">
    <div id="name" to="/">
      <span class="nametext">Fanny Reslow</span>
      <span class="nametext">UX &amp; Interaction designer</span>
      <span class="nametext">reslowf@gmail.com</span>
    </div>

    <div class="base">
      <nav class="nav">
        <g-link class="button" to="/">Home</g-link>
      </nav>
      <nav class="nav">
        <g-link class="button" to="/about">About</g-link>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.base {
  margin-right: 100px;
  display: inline-block;
  display: flex;
    
}



.nametext {
    color: #131313d3;
  font-size: 14px;
  font-weight: bolder;
  padding-bottom: 5px;
}


@media (max-width: 860px) {
  .nametext {
    font-size: 18px;
  }
  .header {
    padding-top: 10px;
  }
  .nav {
    margin-left: 5px;
  }
}
</style>