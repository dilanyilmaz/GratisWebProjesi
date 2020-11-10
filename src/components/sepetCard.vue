<template>
<div class="sepet" >
    {{product.title}}
    Fiyatı : {{product.fiyat}}
    Adet : {{product.count}}
    kodu: {{product.Ukodu}}
    
    <button @click="addToCard(product)"> Sepete Ekle</button>
</div>
</template>
<script>
export default {
    props:["product"],
    methods:{
        addToCard(product){
            this.$emit("addToCard",product)
            /*bu komponentte bir event meydana geldi demeye çalışıyoruz */
        },
    }
}
</script>

<style>
.sepet{
    border:2px dashed #666;
    padding: 5px 10px;
    width:300px;
    background-color:salmon;
    margin-bottom: 5px;
}
.sepet:hover{
    border:2px solid #666;
    transition: all .1s;
}
</style>