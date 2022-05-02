<template>
  <div class="big-container py-5">
    <div class="container py-5">
      <div class="row">
        <div class="col-6">
          <h2>Limitless learning, more possibilities</h2>
          <p>Online courses open the opportunity for learning to almost anyone regardless of their scheduling commitments.</p>
          <button>Read more</button>
        </div>
        <div class="col-6">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ReadMoreComp',

}
</script>

<style scoped lang="scss">
.big-container{
  width: 100%;
  background-image: url("./../../assets/img/Untitled-1-1-1-1-1.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: 60%;
  background-position-y: 60%;
}

.container{
  width: 65%;
  margin: 0 auto;
}
</style>