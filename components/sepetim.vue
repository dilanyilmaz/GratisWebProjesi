<template>
    <div class="sepetimekrani">
        <p style="font-size:35px; color:gray;">Sepetim <a style="color: rgb(60, 13, 65); font-size:15px; margin-left:520px;"><b>&#10094; Alışverişe devam et</b></a></p>
        
        <div class="ic" style="float:left;">
                <div class="base fill " id="beyazEkranmini" style="float:left; margin-right:20px; width:100px;" >
                <img :src="image1" style="width:100px;"/>
                </div>

                <div style="margin-left:15px; float:left;
                 width:300px; margin-top:10px; font-size:15px;"
                ><b>Colgate Advanced White Charcoal Diş Macunu 75 ml 2'li</b></div>

                <div style="float:left; margin-top:30px;">
                <button style=" background-color:white;
                text-color:white; width:100px; height:40px; border-radius:50px; ">
                <a><b style="font-size:15px; color:purple;"> - | 2 | + </b></a> 
                </button>
                </div>

                <div style="width:150px; float:left; margin-top:10px; margin-left:70px;">
                    <div><a style="font-size:10px;">Toplam</a>
                    <img :src="kalp" style="width:20px; margin-left:15px;"/>
                    <img :src="cop" style="width:20px; margin-left:15px;"/>
                    </div>
                    <div>
                        <a style="font-size:10px; margin-left:-15px"><b style="font-size:25px;">35</b>,00 TL</a>
                    </div>
                </div>
        </div>
        
        <div class="spozeti" style=" padding-top:15px; float:left;">
            <div style="padding-left:15px; padding-bottom:15px;"><b>Siparis Özeti</b></div>
            <div><a style="padding-left:15px; font-size:12px">Ürün Fiyatı(1 Ürün)</a>
            <a style="font-size:12px; padding-left:20px;">35.00 TL</a></div>
            <div style="padding-left:15px; margin-top:15px; border-bottom:1px solid gray;"><a style="color:purple; font-size:12px;"><b>+ Promosyon Kodu Ekle</b></a></div>
             
             <div style="padding-left:15px; margin-top:15px;"><a style="color:purple; font-size:12px"><b>Ara Toplam</b></a>
            <a style="font-size:12px; padding-left:55px;">35.00 TL</a></div>

            <div style="background-color:purple; width:200; height:40px; margin-top:22px;
            border-bottom-left-radius:5px;
            border-bottom-right-radius:5px;
             "><p style="color:white; padding-left:100px; padding-top:5px;">SATIN AL &#10140;</p></div>
        
            <div><a style="font-size:12px; width:200px;">Bu aşamada onayınız alınacaktır.</a></div>
        </div>





    </div>
</template>
<script>
export default {
     data(){  
        return{  
            image1: require('../assets/image/macun1.webp'),
            kalp: require('../assets/image/kalp.svg'),
            cop: require('../assets/image/delete.png'),
     }
   }
}
</script>
<style>
.spozeti{
    margin-top:-55px;
    margin-left: 20px;
    background-color: rgb(255, 255, 255);
    border:1px solid gray;
    border-radius: 5px;
    width:200px;
    height:220px;
}
.resim{
    width:90px;
    height: 50px;
    background-image: url('../assets/image/macun1.webp');
}
.sepetimekrani{
    margin-left: 20px;
    border:1px solid gray;
    width:1080px;
    height: 500px;
    padding-top: 35px;
    padding-left:25px;
}
.ic{

    padding-left:40px;
    border:solid 1px gray;
    border-radius: 10px;
    background-color: rgb(255, 255, 255);
    width:800px;
    height:120px;
}
</style>