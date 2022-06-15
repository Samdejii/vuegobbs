<template>
  <div id="app">
    <div id="nav">


         <header id="header">

    <div id="topbar">
      <div class="container-fluid">
        <div class="social-links">
        </div>
      </div>
    </div>

    <div class="container-fluid">

      <div class="logo float-left ml-3">
        <!-- Uncomment below if you prefer to use an image logo -->
       <!--  <h1 class="text-light"><a href="#intro" class="scrollto"><span>Rapid</span></a></h1>-->
        <a href="#header" class="scrollto"><img src="img/Image (4).png" alt="" class="img-fluid"></a> 
      </div>

      <nav class="main-nav float-left d-none d-lg-block ml-3">
        <ul>
          <li class="active"><router-link to="/">Personal</router-link></li>
          <li><router-link to="/business">Business</router-link></li>
          <li><a href="#services">Company</a></li>
          <li><a href="#portfolio">Features</a></li>
          <li><a href="#team">Help</a></li>
        </ul>
      </nav><!-- .main-nav -->
      
        <div class="logo float-right ml-3">
        <button  type="button" class="btn btn-sm btn-outline-secondary mr-3">Sign in</button>
        <button  type="button" class="btn btn-sm btn-success mr-3" style="background-color:#008080;">Create free account</button>
        </div>

    </div>
  </header><!-- #header -->





    </div>
    <router-view />
  </div>
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 0px;
}

#nav a {
  font-weight:normal;
  color: #2c3e50;
  font-size:12px;
}

#nav a.router-link-exact-active {
  color: #008080;
}
</style>
