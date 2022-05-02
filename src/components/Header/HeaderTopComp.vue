<template>
  <div class="border-bottom">
    <div class="container">
      <div class="row row-cols-3 d-flex align-items-center py-3">
        <div class="col-4">
          <form>
            <fieldset>
              <div class="">
                <select id="disabledSelect" class="form-select w-25">
                  <option>English</option>
                  <option>Italian</option>
                  <option>Mandarin</option>
                  <option>Hindi</option>
                  <option>Spanish</option>
                  <option>French</option>
                  <option>Arabic</option>
                  <option>Russian</option>
                </select>
              </div>
            </fieldset>
          </form>
        </div>
        <div class="col-6 d-flex align-items-center justify-content-end">
          <ul class="d-flex menu-list m-0">
            <li class="me-3">Courses</li>
            <li class="me-3">Zoom</li>
            <li class="me-3">Pages</li>
            <li class="me-3">Bundles</li>
            <li class="me-3">Course Formats</li>
            <li class="me-3">Add Course</li>
            <li class="me-3">Demos</li>
          </ul>
        </div>
        <div class="col-2 text-end">
          <i class="fa-brands fa-twitter me-3"></i>
          <i class="fa-brands fa-instagram me-3"></i>
          <i class="fa-brands fa-git me-3"></i>
          <i class="fa-brands fa-linkedin me-3"></i>
          <i class="fa-brands fa-pinterest"></i>
        </div>
      </div> 
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'HeaderTopComp',

}
</script>

<style scoped lang="scss">
.menu-list{
  list-style-type: none;
}

.container{
  width: 90%;
  margin: 0 auto;
}
</style>