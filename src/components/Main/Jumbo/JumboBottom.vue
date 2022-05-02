<template>
  <div class="container">
    <div class="row">
      <div class="col-8">
        <div>
          <img class="poster" src="./../../../assets/img/cat_1-770x375.jpg" alt="">
        </div>
        <div class="container p-0 m-0 w-100">
          <div class="row row-cols">
            <div class="col-6 text-start">
              Software Development
            </div>
            <div class="col-6 text-end">
              5 Courses
            </div>
          </div>
        </div>
      </div>
      <div class="col-4 d-flex flex-column justify-content-between">
        <div>
          <img class="poster" src="./../../../assets/img/cat_2-370x155.jpg" alt="">
        </div> 
        <div class="container p-0 m-0 w-100">
          <div class="row row-cols">
            <div class="col-6 text-start">
              Art
            </div>
            <div class="col-6 text-end">
              8 Courses
            </div>
          </div>
        </div>
        <div>
          <img class="poster" src="./../../../assets/img/cat_3-370x155.jpg" alt="">
        </div>
        <div class="container p-0 m-0 w-100">
          <div class="row row-cols">
            <div class="col-6 text-start">
              Material Design
            </div>
            <div class="col-6 text-end">
              5 Courses
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row row-cols-3">
      <div class="col-4">
        <div>
          <img class="poster" src="./../../../assets/img/cat_5-370x155.jpg" alt="">
        </div>
        <div class="container p-0 m-0 w-100">
          <div class="row">
            <div class="col-6 text-start">
              Music
            </div>
            <div class="col-6 text-end">
              5 Courses
            </div>
          </div>
        </div>
      </div>   
      <div class="col-4">
        <div>
          <img class="poster" src="./../../../assets/img/cat_4-370x155.jpg" alt="">
        </div>
        <div class="container p-0 m-0 w-100">
          <div class="row">
            <div class="col-6 text-start">
              Exercise
            </div>
            <div class="col-6 text-end">
              7 Courses
            </div>
          </div>
        </div>
      </div>   
      <div class="col-4">
        <div>
          <img class="poster" src="./../../../assets/img/cat_6-370x155.jpg" alt="">
        </div>
        <div class="container p-0 m-0 w-100">
          <div class="row">
            <div class="col-6 text-start">
              Photography
            </div>
            <div class="col-6 text-end">
              4 Courses
            </div>
          </div>
        </div>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'JumboBottom',

}
</script>

<style scoped lang="scss">
.container{
  width: 65%;
  margin: 0 auto;
}

.poster{
  max-width: 100%;
}
</style>