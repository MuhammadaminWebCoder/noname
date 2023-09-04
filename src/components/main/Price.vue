<template>
      <div class="price">
            <div class="price-box shadow with-50 text-center br-12">
                  <h3>Pricing</h3>
                  <div class="d-flex mt-4 justify-content-center">
                        <div class="premium me-5">
                              <span>Startel</span>
                              <span class="d-block fw-bold fs-5">$4,000/mo</span>
                        </div>
                        <div class="premium ms-5">
                              <span>Business</span>
                              <span class="d-block fw-bold fs-5">$7,500/mo</span>
                        </div>
                  </div>
                  <span class="d-block mt-10 span mt-4">{{ range }} products</span>
                  
                  <div class="d-flex align-items-center">
                        <span class="d-block fs-12 mt-1 ms-3">1</span>
                        <input type="range"  track-color="green"  class="form-range text-dark" max="50" min="1" v-model="range">
                        <span class="d-block fs-12 mt-1 ms-3">+50</span>
                  </div>

                  <div class="d-flex rounded position-abs align-items-center border p-3">
                        <span class="span d-block">Ready to get started?</span>
                        <button class="btn bg-blu ms-5 px-5">Get Started</button>
                  </div>
            </div>
      </div>
</template>

<style scoped>
.form-range::-webkit-slider-thumb {
  background-color: black;
}



.form-range::-moz-range-thumb {
  background-color: var(--thumb-color);
}

.form-range::-ms-thumb {
  background-color: var(--thumb-color);
}
</style>

<script>
export default{
      data() {
            return{
                  range:'1'
            }
      }
}
</script>