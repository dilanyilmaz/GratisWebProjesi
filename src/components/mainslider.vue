<template>  
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
    >
        <ul class="miniul">
          <li v-for="itemim in imageList" :key="itemim.id">
            <b-carousel-slide>
              <template #img>
                 <img
                 class=" img-fluid w-100"
                 width="100%"
                 height="480"
                 :src="itemim.iconu"
                 alt="image slot"
                 >
             </template>
            </b-carousel-slide>
          </li>
       </ul>

      <!-- Slide with blank fluid image to maintain slide aspect ratio -->

    </b-carousel>

 
  </div>
</template>

<script>
  export default {
      data(){
        return{
          imageList:[
            {
              id:0,
              iconu: require('../assets/image/w1.webp')
            },
                        {
              id:1,
              iconu: require('../assets/image/w2.webp')
            },
                        {
              id:2,
              iconu: require('../assets/image/w3.webp')
            },
                        {
              id:3,
              iconu: require('../assets/image/w4.webp')
            },
                        {
              id:4,
              iconu: require('../assets/image/w5.webp')
            },
          ]
        }
      }
   
  }
</script>
<style scoped>
.miniul{
  padding-left:0px;
}
</style>