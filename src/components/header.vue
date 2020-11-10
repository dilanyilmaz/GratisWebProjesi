<template>
    <div class="header-div">
        <b-row >
          <b-col cols="3" class="mor-divh"> 
              <a><img src="../assets/image/teslimat.svg" style="width:30px;padding-right:5px"/></a>
              <a style="color:rgb(190, 49, 131);"><b>99 TL üzeri alışverişe ÜCRETSİZ KARGO fırsatı</b> </a>

          </b-col>
          <b-col cols="4" class="mor-divh">
          </b-col>
          <b-col cols="5" class="mor-divh">

            <ul>
                <li v-for="item in iconimage" :key="item.id" class="mor-lih">
                 <a ><img :src="item.icon" class="mor-imgh"/></a>
                 <a ><strong>{{item.title}}</strong></a>
               </li>
            </ul> 

          </b-col>
        </b-row>
    <!--___________________________ikinci kısmı_____________________________-->
        <b-row class="wht">
            <b-col cols="2">
                
            </b-col>
            <b-col cols="1">    
                 <div style="float:left">
                 <a><img src="../assets/image/logo.svg" style="width:160px; z-index:1;"/></a>
                </div>
            </b-col>
            <b-col cols="6">
                 <div class="moryazi ">
                    <b>  Markalar</b>
                </div>
                <div class="moryazi">
                    <b>  Kampanyalar</b>
                </div>

                <div style="float:left;width:600px;">
                   <form>
                     <div id="boxi" >
                         <input type="text" id="search" placeholder="Haftanın En Çok Satan Ürünlerini Keşfet...">
                         <i class="fa fa-search"></i>
                         <a><img src=""></a>
                     </div>
                   </form>
                </div>
            </b-col>

            <b-col cols="2">
                <div style="float:left;"> 
                    <button class="saributon"><strong>Giriş Yap</strong><br>
                    <a style="font-size:12px; color:rgb(99, 99, 99);">Üye ol</a></button>
                </div>
                <div style="float:left; padding-top:7px; border-right:2px solid gray;"> 
                    <a style="margin-left:15px; margin-right:7px;"><img src="../assets/image/fav.svg" style="width:35px;"></a>
                </div>
                <div style="float:left; padding-top:7px"> 
                    <a style="margin-left:7px;"><img src="../assets/image/sepetim.svg" style="width:35px"></a>
                </div>

            </b-col>
            <b-col cols="2">

            </b-col>
        </b-row>


    </div>
</template>

<script>
export default{
    data(){
        return{
            iconimage:[
            {
              id:1,
              title:"Gratis Beauty",
              icon: require('../assets/image/gb.png')
            },
            {
              id:2,
              title:"Gratis Kart",
              icon: require('../assets/image/b.webp')
            },
                        {
              id:2,
              title:"Mağazalarımız",
              icon: require('../assets/image/magaza.svg')
            },
            {
              id:3,
              title:"Yardım ve Destek",
              icon: require('../assets/image/help.svg')
            },
            ],
             options: ['<b>Popüler Kategori</b>','Çorap', 'Hijyen Ürünleri', 'Set Ürünleri', 'Pamuk', 'Sıcak Su Torbası','Temizlik']
        }
    }
}
</script>


<style>

.saributon{
    text-align: left;
    padding-left:45px;
    line-height: 15px;
    color:rgb(47, 37, 114);
    background-image: url("../assets/image/profile.svg");
    background-repeat: no-repeat;
    background-color: rgb(255, 230, 0);
    width:150px;
    height: 50px;
    border-radius: 50px;
    border:transparent;
    background-position:15px, center;
}
.saributon:hover{
    border:transparent;
    border: none;
}
.saributon:visited{
    border: transparent;
    border:none;
}
.saributon:active {
  color: blue;
  border:none;
}
.moryazi{
    float:left;
    color:rgb(190, 49, 131);
    margin:10px;
}
/*-------------Arama Butonu ------------*/
#boxi {
    max-width: 600px;
    position: relative;
   border-color: tomato;
    
}
 
#boxi .fa-search {
    position: absolute;

    left: 12px;
    font-size: 20px;
    color:rgb(127, 28, 151);
}
 
#search {
    height: 50px;
    position:absolute;
    right:5px;
    width: 400px;
    box-sizing: border-box;
    border: 2px solid rgb(95, 14, 95);
    border-radius: 4px;
    font-size:18px;
    padding: 12px 20px 12px 40px;
    -moz-transition: right 0.4s ;
    -o-transition: right 0.4s ;
    -webkit-transition: right 0.4s ;
    transition:width 0.4s ease-in-out;
    background-image: url("../assets/image/search.svg");
    background-repeat:no-repeat;
    background-position:right center;
 
}
 
#search:focus {
    width: 100%;
    border: 2px solid rgb(95, 14, 95);
    

}
 
/*-------------Arama Butonu ------------*/

.wht{
    padding-top:7px;
    height: 70px;
    background-color: white;
    border-top:2px double rgb(172, 170, 170);
    border-bottom:2px double rgb(172, 170, 170);
}
.mor-lih{

     float: left;
    
}
.mor-lih a {
    
    display: block;
    float: left;
    padding-top:10px;
    padding-bottom:0px;
    font-size:10px;
    padding-right:10px;
    padding-left: 10px;
    }
.mor-imgh{
     display:block;
     width:30px;
     padding-top:2px !important;
     padding-top: -2px;
     margin-top:-8px;


 }
.headerh{
   
    height:80px;
    padding-right:auto;
    padding-left:auto;
}
.collh{
    display: flex;
    background-color:yellow;
}
.mor-divh{
 background-color: rgb(230, 189, 230);
}
</style>