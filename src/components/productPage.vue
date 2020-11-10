<template>
    <div class="productk">
        
        

        <div class="beyazEkran" :class="className" v-if='showImage'>
        </div>
        <div style="margin-left:25px;">
            <button ><img src="../assets/image/macun1.webp" style="width:70px;height:50px;"></button>
            <button  @click="showimage" style="margin-left:25px;"><img src="../assets/image/macun2.webp" style="width:70px;height:50px;"></button>
        </div>

    </div>
</template>

<script>
export default {
     data(){
         return {
        showImage: true,
         }
    },
    methods: {
        toggleImage: function () {
            this.showImage = !this.showImage;
        },
      
    }
}
</script>

<style scoped>
.beyazEkran{
    margin-top:50px;
    margin-left:25px;
    display:inline-flex;
    background-color: white;
    border:1px solid;
    width:400px;
    height:400px;
}
.productk{
    width:850px;
    height:600px;
    background-color: rgb(217, 218, 219);
}
.className{
    background-image: url("../assets/image/macun1.webp");
}
</style>