<template>
    <div class="home-page">
       <mainslider/>
        <productSlider/>
        
           
    </div>
</template>

<script>
import mainslider from "~/components/mainslider"
import productSlider from "~/components/productSlider"
import Sepetbtn from '~/components/sepetbtn.vue'
export default {
    components:{
        mainslider,
        productSlider,
        Sepetbtn
    }
}
</script>
<style>

</style>