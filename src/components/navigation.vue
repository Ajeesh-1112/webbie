<template>
   <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid ">
    <a class="navbar-brand text-success" href="#">WEBBIE!</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item mx-5">
          <a class="nav-link active " aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item mx-5">
          <a class="nav-link " href="#">About</a>
        </li>
        <li class="nav-item dropdown mx-5">
          <a class="nav-link dropdown-toggle nav-link-hover"  href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" >
            Services
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Website Creation</a></li>
            <li><a class="dropdown-item" href="#">Design</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Many more....</a></li>
          </ul>
        </li>
      </ul>  
      <form class="d-flex" role="search">
        <button class="btn btn-success ms-5" type="button">Login</button>
      </form>
    </div>
  </div>
</nav>
</template>


<script>
export default {
    name: 'navigationHome'
}
</script>

<style scoped>

</style>