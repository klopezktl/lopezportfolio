<template>
    <nav class="navbar navbar-expand-lg navbar-dark">
      <!-- <a class="navbar-brand" href="">tindog</a> -->
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02">
          <span class="navbar-toggler-icon"></span>
      </button>

      <div class="navbar-container collapse navbar-collapse" id="navbarTogglerDemo02">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#introduction">Introduction</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#experience">Experience</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#education">Education</a>
          </li>
          <!-- <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li> -->
        </ul>
      </div>

    </nav>
</template>

<script>
</script>

<style>

.navbar {
  background-color: #FEFAEC;
  /* padding: 100px 100px !important; */

  padding: 20px 100px 20px !important;
}

.nav-item {
  padding: 0 18px;
}

.nav-link {
  color: #625772 !important;
  font-size: 1rem;
  text-align: center;
}

.nav-link:hover {
  background-color: #625772;
  color: #FEFAEC !important;
}

.navbar-toggler-icon{
  background-color: #625772 !important;
}

.navbar-nav {
  position: absolute;
  left: 50%;
  transform: translatex(-50%);
}

.navbar-container {
  background-color: #FEFAEC;
}

</style>
