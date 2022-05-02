<template>
  <div>
    <div class="big-container">
      <h2> We are Proud</h2>
      <p>Certificates courses are instructured by highly educated and qualified instructors who hold doctoral and master's level degrees.</p>
      <div class="container py-5">
        <div class="row">
          <div class="col-3 border-end">
            <span>2000 <br> students</span>
          </div>
          <div class="col-3 border-end">
            <span>950 <br> courses</span>
          </div>
          <div class="col-3 border-end">
            <span>1600 <br> hours video</span>
          </div>
          <div class="col-3">
            <span>150 <br> countries reached</span>
          </div>
        </div>
      </div>
      
    </div>
    <div class="container newsletter-container">
        <div class="row">
          <div class="col-6">
            <h4>Subscribe our newsletter</h4>
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words.</p>
          </div>
          <div class="col-6">
            <form class="d-flex justify-content-around">
              <div class="mb-3">
                <h3>Your e-mail address</h3>
                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
              </div>
              <button type="submit" class="btn btn-primary">Submit</button>
            </form>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'StatsNewsletterComp',

}
</script>

<style scoped lang="scss">
.big-container{
  width: 100%;
  background-image: url("./../../assets/img/we_proud.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: 60%;
  background-position-y: 60%;
  background-color: #F0F4F9;
}

.newsletter-container{
  background-color: #4bd7a8;
}
</style>