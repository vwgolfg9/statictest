<template>
  <nav class="navbar" >
    <div class="navbar-brand">
      <a href="@/index">
      <img src="@/assets/tshibo-logo.png" width="190" alt="">
      </a>
      <a role="button" class="navbar-burger " aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
        <span aria-hidden="true"><a href="#">About</a></span>
        <span aria-hidden="true">Services</span>
        <span aria-hidden="true">Contact</span>  
      </a>
      <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a href="@/pages/about" class="navbar-item">
        Home
      </a>

      <a class="navbar-item">
        Documentation
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          More
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            About
          </a>
          <a class="navbar-item">
            Jobs
          </a>
          <a class="navbar-item">
            Contact
          </a>
          <hr class="navbar-divider">
          <a class="navbar-item">
            Report an issue
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary">
            <strong>Sign up</strong>
          </a>
          <a class="button is-light">
            Log in
          </a>
        </div>
      </div>
    </div>
    </div>
    </div>
  </nav>
</template>
