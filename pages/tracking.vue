<template>
  <section class="py-5 mt-5 front-slider d-flex mx-auto my-auto justify-content-center align-items-center mt-5">
    <div class="container mt-5">
      <div class="row">
        <div class="col-lg-6">
          <form action="">
            <div class="form-group">
              <label for="" class="d-block text-white">Lacak paketmu disini</label>
              <div class="row no-gutters">
                <div class="col-lg-8">
                  <input type="text" name="order_id" value="" placeholder="Masukkan nomor order" class="form-control">
                </div>
                <div class="col-lg-4 pl-lg-3">
                  <button type="submit" class="btn btn-primary btn-block">Lacak</button>
                </div>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
@media screen and (min-width: 1024px) {
  .front-slider {
    min-height: 70vh;
  }
  .front-slider {
    background: url('https://kiriminaja.com/assets/tracking.jpg');
    background-size: 100% auto;
    background-position: center top;
  }
}
</style>
