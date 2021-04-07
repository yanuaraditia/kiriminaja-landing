<template>
  <section class="py-5 mt-5 front-slider d-flex mx-auto my-auto justify-content-center align-items-center mt-5">
    <div class="container mt-5">
      <div class="row">
        <div class="col-lg">
          <form action="">
            <div class="form-group">
              <label for="order-id" class="d-block text-white display-4">Lacak paketmu disini</label>
              <div class="row no-gutters max-row">
                <div class="col-lg">
                  <input type="text" id="order-id" name="order_id" value="" placeholder="Masukkan nomor order" class="form-control">
                </div>
                <div class="col-lg-3 pl-lg-3">
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
  .max-row {
    max-width: 40vw;
  }
}
</style>
