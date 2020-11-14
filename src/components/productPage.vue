<template>
    <div class="productk">
       <div style="margin-left:30px; margin-bottom:25px;">Ana Sayfa > Sağlık & HijyenAğız & Diş Bakımı > Diş Macunları > Colgate Natural Extracts Aloe Vera Diş Eti Bakımı Diş Macunu 75 ml</div>
        <!--_______İmage divi________-->
        <div class="" style="float:left">

        <div class="base fill" id="beyazEkran"  >
        <img class="fk" :src="image" />
        </div>
        
        <!--_______minik görüntüler________-->
        <button @click="changeimage1()" class="base fill" id="beyazEkranmini" style="float:left; margin-left:25px;" >
        <img class="fk" :src="image1" />
        </button>

        <button @click="changeimage2()" class="base fill" id="beyazEkranmini" style="float:left"  >
        <img class="fk" :src="image2" />
        </button>

        <button @click="changeimage3()" class="base fill" id="beyazEkranmini" style="float:left" >
        <img class="fk" :src="image3" />
        </button>

        <button @click="changeimage4()" class="base fill" id="beyazEkranmini" style="float:left"  >
        <img class="fk" :src="image4" />
        </button>

        </div>
        
        <!--__________________Bilgi Kısmı_________________________-->
        <div style="float:left " >
         <div class="bilgi"  style="float:left;">
          <div v-html="ad" class="ad">{{ad}}</div>
        </div>

        <div style="font-size:14px; margin-top:90px; margin-left:20px; text-align:center; width:300px; color:rgb(77, 19, 74); "><img :src="icon" style="width:20px; height:20px; margin-top:5px;">
        {{yorum}}<b style="padding-left:35px;">Colgate</b></div>
        
        <div class="fiyat" style="float:left">
            <div style="float:left; margin-top:5px;"><a style="font-size:35px;"><b>35</b></a></div>
            <div style="float:left; margin-top:12px;"><a style="font-size:20px;"><b>,</b> 00 TL</a></div>
        </div>

         <div class="etiket" style="float:left">
            <div style="float:left; width:60px; height:70px; background-color: rgb(243, 213, 223); padding-top:10px; padding-left:10px; color: rgb(189, 12, 174);">
              <a style="font-size:10px;"><b>%</b></a> 
              <a style="font-size:20px;"><b>40</b></a>
              <p style="font-size:10px; margin-top:-2px;">indirim</p>
            </div>

            <div style="float:left;">
              <div class="kart" style="height:65px;">
                <p style="font-size:8px; margin-bottom:-4px; padding-top:5px; padding-left:15px;"><b>Gratis Kart ile</b></p>
                <p style="color:rgb(61, 33, 83);"><b style="font-size:20px; padding-left:15px;">21</b>,00 TL</p>
              </div>

              <div style="background-color:rgb(108, 42, 124); width:190px; height:18px; margin-top:-13px; border-bottom-right-radius:5px;">
               <p style="color:white;font-size:10px; padding-left:50px; padding-top:2px; " > HEMEN YARARLAN</p>
              </div>
            </div>

            <!--____________________________Butonlarım____________________________-->
        </div>

             <div style=" width:500px; margin-left:50px; margin-top:220px; ">
             <button style=" background-color:white;
            text-color:white; width:150px; height:60px; border-radius:50px; ">
             <a><b style="font-size:25px"> - | 2 | + </b></a> 
            </button>

            <button style=" background-color:rgb(74, 19, 82);
            text-color:white;
              width:200px; height:60px; border-radius:50px; ">
             <a style="color:white;"> SEPETE EKLE </a> 
            </button>

            <button
            style="  background-color:white; border: 1px solid rgb(74, 19, 82);
            text-color:white;
            width:60px; height:60px; border-radius:50px;">
             <a style="color: rgb(74, 19, 82);"><img src="../assets/image/kalp.svg"/></a>
            </button>
            </div>


     </div>


    </div>
</template>

<script>
export default {
      data() {
        return {
            image: require('../assets/image/macun1.webp'),
            text: "Colgate Advanced White Charcoal Diş Macunu 75 ml 2'li",
            icon: require('../assets/image/pen.svg'),
            yorum:"İlk Yorumu Sen Yap!",
            image1: require('../assets/image/macun1.webp'),
            image2: require('../assets/image/macun2.webp'),
            image3: require('../assets/image/macun3.webp'),
            image4: require('../assets/image/macun4.webp'),

            ad:"<b>Colgate Natural Extracts Aloe Vera Diş Eti Bakımı Diş Macunu 75 ml</b>",

        }
      }  ,
      methods:{
        changeimage1(){
            this.image=this.image1;
            /*bu komponentte bir event meydana geldi demeye çalışıyoruz */
        },
        changeimage2(){
            this.image=this.image2;
            /*bu komponentte bir event meydana geldi demeye çalışıyoruz */
        },
        changeimage3(){
            this.image=this.image3;
            /*bu komponentte bir event meydana geldi demeye çalışıyoruz */
        },
        changeimage4(){
            this.image=this.image4;
            /*bu komponentte bir event meydana geldi demeye çalışıyoruz */
        }
      }    
}
</script>

<style scoped>

.kart{
background-image: url("../assets/image/kart.webp");
background-color: rgb(207, 207, 207);
background-repeat:no-repeat;
background-size: 150px 50px;
background-position: right bottom;
}

.fiyat{
  background-color: rgb(255, 255, 255);
  box-shadow: 
      0.1em -0.1em 0.1em rgb(207, 207, 207),
      0.1em 0.1em 0.1em rgb(207, 207, 207),
     -0.1em 0.1em 0.1em rgb(207, 207, 207),
     -0.1em -0.1em 0.1em rgb(207, 207, 207);
  width:125px;
  height:70px;
  margin-left: 50px;
  margin-top:15px;
  border-radius: 5px;
  padding-top:4px;
  padding-left: 15px;

}
.etiket{
  background-color: white;
  box-shadow: 
      0.1em -0.1em 0.1em rgb(207, 207, 207),
      0.1em 0.1em 0.1em rgb(207, 207, 207),
     -0.1em 0.1em 0.1em rgb(207, 207, 207),
     -0.1em -0.1em 0.1em rgb(207, 207, 207);
  width:250px;
  height:70px;
  margin-left:10px;
  margin-top:15px;
  border-radius: 5px;

}
.ad{
  margin-left:50px;
  width:650px;
  color:black;
  font-size: 25px;

}
.base img  {
  width:100%;
  height:100%;
}

.fill img {
  object-fit: fill;
}

.product-info {
  width: 50%;
}

#beyazEkran{
    margin-left:25px;
    border:1px solid;
    width:400px;
    height:400px;
}
#beyazEkranmini{
    margin-top:20px;
    margin-left:15px;
    border:1px solid;
    width:70px;
    height:70px;
}
.productk{
    padding-top: 50px;
    width:1150px;
    height:650px;
    background-color: rgb(217, 218, 219);
}


</style>