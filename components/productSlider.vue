<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="pink"
      img-width="900"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333; width:1500px;padding-left:150px;"
    >

          <!--_________________1.SLAYT_____________________________________-->
       <b-carousel-slide>
        <template #img>
           <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; " class="hover-overlay-container">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v3590969328435898643/products/10380325_09.jpg&height=300&width=300"
            alt="image slot"
          >

   <div class="overlay-btn-container">
        <nuxt-link to="/Anasayfa/Urun" class="overlay-btn">Sepete Ekle</nuxt-link>
    </div>


          <div style="text-align:center; font-size:12px;"> Colgate Natural Extracts Aloe Vera Diş Eti Bakımı Diş Macunu </div>
          <div style="text-align:center; font-size:12px;">75 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>35</b>.00</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">17.50 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
          <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v7788113077750413372/products/10236839_01.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;"> Simple Daily Skin Detox Arındırıcı Yüz Yıkama Jeli</div>
          <div style="text-align:center; font-size:12px;">150 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>40</b>.00</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">20.00 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
           <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v7788135957824132009/products/10277416_05.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;"> Urban Care Twisted Curls Hibiscus & Shea Butter Durulanmayan Saç Bakım Kremi</div>
          <div style="text-align:center; font-size:12px;">175 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>6</b>.75</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">3.25 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
          <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v5396242259157771043/products/10264071_01.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;"> Beaulis Shape it Transparan Kaş ve Kirpik Maskarası</div>
          <div style="text-align:center; font-size:12px;">175 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>18</b>.00</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">9.00 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->   
         </template>    
      </b-carousel-slide>

          <!--_________________2.SLAYT_____________________________________-->
             <b-carousel-slide>
        <template #img>
           <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v531194122423075528/products/10029621_01.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;">Dax Supergro Saç Bakım Yağı</div>
          <div style="text-align:center; font-size:12px;">198 gr</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>149</b>.00 TL</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">3.25 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
          <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v6534298583068257916/products/10011395_01.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;"> Krauterhof Anti-Cellulite Jel</div>
          <div style="text-align:center; font-size:12px;">250 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>102</b>.25 TL</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">3.25 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
           <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v177332860614785613/products/10212609_01.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;">Revox At Kuyruğu Biotin&Collagen Şampuan</div>
          <div style="text-align:center; font-size:12px;">360 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>54</b>.50 TL</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">3.25 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
          <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v9057390633596241447/products/10443888_14.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;">Zigavus 3 Katlı Lastikli Yüz Maskesi 50'li</div>
          <div style="text-align:center; font-size:12px;">175 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>17</b>.50 TL</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">3.25 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->   
         </template>    
      </b-carousel-slide>
          <!--__________________3.SLAYT______________________________________-->      
      <b-carousel-slide>
        <template #img>
           <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v4901216926988382390/products/10034429_02.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;"> Life in Hindistan Cevizi Yapı</div>
          <div style="text-align:center; font-size:12px;">330 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>45</b>.00 TL</div>
          <div style="text-align:center;"><b>45</b>.00 TL</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">22.50 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
          <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v611619726668812625/products/10757290_02.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;">Sensodyne Tam Koruma Beyazlatıcı Diş Macunu + Diş Fırcası</div>
          <div style="text-align:center; font-size:12px;">75 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>58</b>.</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">3.25 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
           <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v7788135957824132009/products/10277416_05.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;"> Urban Care Twisted Curls Hibiscus & Shea Butter Durulanmayan Saç Bakım Kremi</div>
          <div style="text-align:center; font-size:12px;">175 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>6</b>.75</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">3.25 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->
          <!--___________________ ürün__________________________-->

          <div style="width:250px; height:400px; float:left; margin-left:20px; ">
          <img
            class="d-block img-fluid w-100"
            src="https://www.gratis.com/ccstore/v1/images/?source=/file/v6859199200253588235/products/10012352_01.jpg&height=300&width=300"
            alt="image slot"
          >
          <div style="text-align:center; font-size:12px;">Gilette Venus ConfortGlide Brerze Yedek Kadın Tıraş Bıçağı 4'lü Paket</div>
          <div style="text-align:center; font-size:12px;">175 ml</div>
          <div style="margin-left:7px; text-align:center; border-bottom:1px solid gray;width:230px;"><img :src="icon" style="width:15px; height:15px;">{{yorum}}</div>
          <div style="text-align:center;"><b>104</b>.00 TL</div>
          <div style="background-color:rgb(250, 213, 247); width:250px; height:45px; margin-bottom:0px;">
            <div style="float:left; margin-left:50px; padding-top:3px; width:50px; height:50px;font-size:12px;">Gratis Kart ile</div>
            <div style="float:left; padding:2px; width:50px; margin-top:5px; border-radius:5px; height:35px; background-color:rgb(223, 27, 206);; font-size:12px; color:white;">%<b style="font-size:20px; line-height:0.5px; padding-top:1px;">51</b><p>indirim</p></div>
            <div style="float:left; padding-left:7px; padding-top:3px; margin-top:5px; ">85.00 TL</div>
          </div>
          </div>
          <!--______________________________________________________________________________________________________-->   
         </template>    
      </b-carousel-slide>
    
    
    </b-carousel>
  </div>
</template>


<style>
    .hover-overlay-container {
        position: relative;
        width: 300px;
    }
 
    .hover-overlay-container:hover .overlay-image {
        opacity: 0.3;
    }
 
    .hover-overlay-container:hover .overlay-btn-container {
        opacity: 1;
    }
 
    .hover-overlay-container .overlay-image {
        display: block;
        width: 100%;
        height: auto;
        opacity: 1;
        transition: .5s ease;
        backface-visibility: hidden;
    }
 
    .hover-overlay-container .overlay-btn-container {
        position: absolute;
        top: 50%;
        left: 50%;
        opacity: 0;
        transition: .5s ease;
        text-align: center;
        transform: translate(-50%, -50%);
    }
 
    .hover-overlay-container .overlay-btn-container .overlay-btn {
        color: #fff;
        font-size: 16px;
        padding: 10px 16px;
        background-color: cornflowerblue;
        text-decoration: none;
    }
</style>


<script>
  export default {
    data() {
      return {

        icon: require('../assets/image/pen.svg'),
        yorum:"İlk Yorumu Sen Yap!"
      }
    }
  }
</script>

