<template>
  <div class="product">
    
  </div>
</template>
<script>
  export default {
      data(){
        return{
          imageList:[
            {
              id:0,
              icon: require('../assets/image/ürün3.webp')
            },
                        {
              id:1,
              icon: require('../assets/image/ürün2.webp')
            },
                        {
              id:2,
              icon: require('../assets/image/ürün.webp')
            }
          ]
        }
      }
   
  }
</script>
<style scoped>
p{
    background-image: url('../assets/image/ürün.webp');
    height: 150px;
    width:150px;
}

</style>