<template>
  <div class="home">
    <h1>Review</h1>
    <h3>Destination</h3>
    <div class="card-group align-center">
      <div class="card col-md-4" @click="review">
        <img
          src="https://ik.imagekit.io/tvlk/loc-asset/gNr3hLh55ZCkPJisyxFK-v9MmzxPu57ZRVI%2B10VZ2S4b1PNW4T%2B%2BcbA6yK4gzhAhs9o2HLZ9vs7gy3rpcIU%2BoKi5EygzQLRjTUv7fRblEVA%3D/images/1532064029753-1926x1290-FIT_AND_TRIM-c36904e6e724e1bbbc266c6b30b93075.jpeg?_src=imagekit&tr=c-at_max,h-400,q-40,w-1280"
          class="card-img-top rounded mx-auto d-block"
        />
        <div class="card-body">
          <h5 class="card-title">Yogyakarta</h5>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  methods: {
    review () {
      this.$router.push('/review')
    }
  }
}
</script>

<style scoped>
.card-img-top {
  cursor: pointer;
}
</style>
