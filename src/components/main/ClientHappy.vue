<template>
      <div class="happyClient container text-center">
            <h1>What our happy client say</h1>
            <span class="span pt-5 pb-10 d-block">Things that make it the best place to start trading</span>
            <div>
                  <div class="boxs justify-content-between d-flex my-5">
                        <div class="happy-box box-bg p-4 mt-5">
                              <img class="mx-auto mb-2" src="../icons/Ellipse24.svg">
                              <div class="d-flex justify-content-center my-3">
                                    <i :class="icon.icon" v-for="icon in icons" :key="icon.id"></i>
                              </div>
                              <h4>Robin Ayala Doe</h4>
                              <span class="span d-block mt-3">
                                    countries Vokaila and Consonantia, there <br>
                                    the blind texts. Separated they live in <br>
                                    cookmarksgrove right at the coast.
                              </span>
                        </div>    
                        <div class="happy-box box-bg mx-4 p-4 mt-5">
                              <img class="mx-auto mb-2" src="../icons/Ellipse25.png">
                              <div class="d-flex justify-content-center my-3">
                                    <i :class="icon.icon" v-for="icon in icons" :key="icon.id"></i>
                              </div>
                              <h4>John De marli</h4>
                              <span class="span d-block mt-3">
                                    Far far away, behind the word mountains, far from the <br>
                                    countries Vokalia and Consonantia, there live the blind <br>
                                    texts. Separatedvthey live in Bookmarsgrove.
                              </span>
                        </div>      
                        <div class="happy-box box-bg p-4 mt-5">
                              <img class="mx-auto mb-2" src="../icons/Ellipse26.svg">
                              <div class="d-flex justify-content-center my-3">
                                    <i :class="icon.icon" v-for="icon in icons" :key="icon.id"></i>
                              </div>
                              <h4>Rowhan Smith</h4>
                              <span class="span d-block mt-3">
                                    When she reached the first hills of the <br>
                                    Mountains, she had a last view back on the <br>
                                    of her hometown Bookmarksgrove, the her
                              </span>
                        </div>    
                  </div>
            </div>
            <i class="far my-10 fa-chevron-left p-3 px-5 br-12"></i><i class="far my-10 fa-chevron-right p-3 px-5 bg-black br-12"></i>
            <hr class="my-15">
      </div>
</template>
<script>
export default{
      data(){
            return{
                  icons:[
                        {icon:'fas fs-5 fa-star'},
                        {icon:'fas fs-5 fa-star'},
                        {icon:'fas fs-5 fa-star'},
                        {icon:'fas fs-5 fa-star'},
                        {icon:'fas fs-5 fa-star'},
                  ]
            }
      }
}
</script>