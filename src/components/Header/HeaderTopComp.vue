<template>
  <div class="border-bottom">
    <div class="container">
      <div class="row row-cols-3 d-flex align-items-center py-2">
        <div class="col-4">
          <form>
            <fieldset>
              <div class="">
                <select id="disabledSelect" class="form-select w-25">
                  <option>English</option>
                </select>
              </div>
            </fieldset>
          </form>
        </div>
        <div class="col-6 d-flex align-items-center">
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
        <div class="col-2">
          icons
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