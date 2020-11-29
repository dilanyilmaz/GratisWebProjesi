<template>
    <div class="home-page">
        <b-row>
            <b-col cols="2"></b-col>
            <b-col cols="7"><productPage/></b-col>
            <b-col cols="3"></b-col>
        </b-row>

        
           
    </div>
</template>

<script>
import productPage from "~/components/productPage"

export default {
    components:{
        productPage
    }
}
</script>
<style>
.home-page{
    width:100%;

    background-color: rgb(217, 218, 219);
}
</style>