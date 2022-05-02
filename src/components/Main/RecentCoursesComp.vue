<template>
  <div>
    <div class="text-center">
      <h2>Recent Courses</h2>
      <div class="d-flex justify-content-center">
        <nav class="navbar navbar-expand-lg navbar-light text-center">
          <div class="container-fluid text-center">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">All Categories</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Art</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Exercise</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Material Design</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Music</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Photography</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Software Development</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-2">
            <div class="card" style="width: 18rem;">
              <img src="./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg" class="card-img-top" alt="...">
              <div class="card-body">
                <h6 class="card-title">Web Coding and Apache Basics</h6>
                <hr>
                <a href="#" class="btn btn-primary">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="col-2">

          </div>
          <div class="col-2">

          </div>
          <div class="col-2">

          </div>
          <div class="col-2">

          </div>
          <div class="col-2">

          </div>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'RecentCoursesComp',

}
</script>

<style scoped lang="scss">
.container{
  width: 90%;
  margin: 0 auto;
}
</style>