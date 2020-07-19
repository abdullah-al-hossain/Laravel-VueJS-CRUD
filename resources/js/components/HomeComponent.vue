// HomeComponent.vue

<template>
  <div class="row justify-content-center">
      <div class="col-md-8">
          <div class="card card-default">
              <img src="images/hello.jpg" alt="Images" class="card-img-top">
              
              <div class="card-body">
                  Give your words new a existence.
              </div>
          </div>
      </div>
  </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Home Component mounted.');
        }
    }
</script>