<template>
<div style="margin-left:10%; ">
    <div class="Uye" style=" margin-left: 50px;"> 
            <div style="margin-top:25px;" class="UyeMain">
                <a style="color:gray; font-size:40px;">Üye Misiniz?</a>
                <form style="margin-top:50px;">
                    <a style="color:gray; font-size:15px;">E-Posta</a><br>
                     <input type="text"  class="uye" style="margin-top:10px" placeholder="E-posta adresinizi giriniz."><br><br>
                     
                     <a style="color:gray; font-size:15px; ">Şifre</a><br>
                     <input type="text"  class="uye" style="margin-top:10px" placeholder="Şifrenizi giriniz.">
                    
                    <div style="border-radius:5px;border:1px solid; margin-top:50px;  background-color:rgb(233, 233, 233); width:350px; height:80px">
                        <img src="../assets/image/logo_48.png" style="padding-left:200px;padding-top:15px">
                        <input style="margin-top:35px; margin-left:50px;float:left;" type="checkbox" id="checkbox" v-model="checked" >
                        <label style="float:left; margin-top:-34px;margin-left:70px" for="checkbox">{{msg}}</label>  
                    </div>
                     <button class="btnGiris">Giriş Yap ve DEVAM ET</button>
                </form>
            </div>
    </div> 
        <div class="Uye" style="margin-left:540px;"> 
            <div style="margin-top:25px;" class="UyeMain">
                <a style="color:gray; font-size:40px;">Üye Değil Misiniz?</a>
                <form style="margin-top:50px;">
                    <a style="color:gray; font-size:15px;">E-Posta</a><br>
                     <input type="text"  class="uye" style="margin-top:10px" placeholder="E-posta adresi"><br><br>
                     
                     <label v-html="sp_msj"></label>
                    
                     <button class="btnGiris1">ÜYE OL</button><br><br>

                     <label style="color:rgb(95, 14, 95); margin-left:100px;" v-html="U_olm_dev"></label>
                </form>
            </div>
    </div>
            <div class="Uye" style=" margin-left:1024px;"> 
            <div style="margin-top:25px; padding-top:150px" class="UyeMain">
                <a style=" color:rgb(95, 14, 95); font-size:25px; padding-left:60px;" >Üye olmanın Avantajları?</a>
                <form style="margin-right:50px;border:solid 2px rgb(248, 244, 0);">
                    
                    <div style="float:left; margin-right:5px;height:200px;margin-top:10px">
                        <ul>
                             <li v-for="item in Avantajlar" :key="item.id">
                                <label class="mor-liste"><strong>{{item.id}}</strong></label>
                                <br><br>
                            </li> 
                        </ul>   
                    </div>

                    <div style="margin-top:10px" >
                       <ul>
                           <li v-for="item in Avantajlar" :key="item.id">
                              {{item.title}}<br><br>
                           </li>
                        </ul>
                    </div>
                        
                </form>
            </div>
    </div>
    </div>
</template>
<script>
export default {
    data(){  
        return{  
            sifre:"E-posta adresi zorunludur.",
            uye:"Parola zorunludur.",
            msg:"Ben Robot Değilim",
            sp_msj:"<b> Sipariş bilgileriniz bu adrese gönderilecektir </b>",
            U_olm_dev:"<b> Üye olmadan devam et &#10140; </b>",

        Avantajlar:[
            {
                id:1,
                title:    "Gratis Kart ile indirimlerden yararlanırsınız!",
            },
            {
            id:2,
            title:    "Kendinizi tanıtıp size özel ürün önerileri alır, yeni çıkan ürünlerden haberdar olursunuz!",
            },
            {
            id:3,
            title:    "Siparişinizin durumunu kolayca sorgulayabilir, kargonuzu takip edebilirsiniz!"
            }
           ]
        }
    }
}
</script>

<style scoped>
.mor-liste{
    background-color: rgb(236, 234, 243);
    width:40px;
    height:40px;
    border-radius: 50px;
    color: rgb(115, 9, 156);
    font-size:20px;
    text-align: center;
    padding-top:7px;
}
.btnGiris{
    margin-top:50px;
    width:400px;
    height:50px;
    border-radius: 50px;
}
.btnGiris1{
   border: 1px solid rgb(95, 14, 95);
   background-color: white;
    margin-top:50px;
    width:400px;
    height:50px;
    border-radius: 50px;
}
.Uye{
   border-right: 1px solid;
}
.UyeMain{
    border-left: 1px solid;
    width:500px;
    height:800px;
    background-color:white;
       
    position:absolute;
    padding-left: 50px;
    padding-top: 50px;
}
.uye {

    height: 50px;
    position:relative;
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
    background-repeat:no-repeat;
    background-position:right center;
 
}

</style>
