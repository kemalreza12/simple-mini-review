<template>
  <div class="container">
      <div class="row">
          <div class="col-6"><h3>Review</h3></div>
          <div class="col-6"><star-rating /></div>
      </div>
      <div class="row mt-3">
          <input type="text" class="form-control form-control-lg my-auto col" placeholder="Tulis Nama Kamu">
      </div>
      <div class="row mt-2">
          <input type="text" class="form-control form-control-lg my-auto col" placeholder="Tulis Review Terbaik mu">
      </div>
      <div class="row p-0">
        <button class="btn btn-outline-secondary m-0 px-3 mx-auto mt-4">Upload Gambar</button>
        <button class="btn btn-outline-secondary m-0 px-3 mx-auto mt-4">Kirim</button>
        </div>
        <user-comment/>
  </div>
</template>

<script>
import StarRating from 'vue-star-rating'
import UserComment from '../components/UserComment'

export default {
  name: 'Review',
  components: {
    StarRating,
    UserComment
  }
}
</script>

<style>

</style>
