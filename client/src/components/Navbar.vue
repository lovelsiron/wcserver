<template>
<nav class="navbar navbar-icon-top navbar-expand-lg navbar-custom">
  <a class="navbar-brand" href="#"><img id="icon" src="../assets/IGN.jpg" width="100px"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/">
         Home
        </router-link>
        </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/Members">
         Members
        </router-link>
          </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/News">
         News
        </router-link>
          </a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder="search" aria-label="Search">
      <button class="btn btn-default my-2 my-sm-0" type="submit">search</button>
    </form>
  </div>
</nav>
</template>

<style>
.navbar-custom { 
    background-color: #2c2c2c; 
} 
.nav-item a{
color:white;
}

.nav-item a:hover{
  text-decoration: none;
 color:red; 
}
</style>
