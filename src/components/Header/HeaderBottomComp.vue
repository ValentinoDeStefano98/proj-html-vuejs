<template>
  <div class="container">
    <div class="row">
      <div class="col-2">
        <img src="./../../assets/img/MasterStudy_logo.svg" alt="">
      </div>
      <div class="col-4 d-flex">
        CATEGORY
        <form class="d-flex">
          <div class="mb-3">
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-3">
        <span>Became an insctructor</span>
        <span>For Enterprise</span>
      </div>
      <div class="col-3">
        <span>Log in</span>
        <span>Sign up</span>
        <span>icona</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderBottomComp',

}
</script>

<style scoped lang="scss">
.container{
  width: 90%;
  margin: 0 auto;
}
</style>