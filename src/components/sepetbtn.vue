<template>
  <div>
    <b-row>
     
      <b-col cols="12">
        <div class="sepetbtn">
         <sepet @addToCard="cardItems.push($event)" :product="product" v-for="product in productList" :key="product.id"/>
        </div>
        
         <div>
          <b-dropdown  variant="link"  no-caret>
           <template #button-content>
            <img src="../assets/image/sepetim.svg" style="width:20px">
          </template>
          <!-- aşağısı dropdown ın iç kısmı --->
          <b-dropdown-item style="width:350px; margin:15px; ">
            <!-- burası sepetin dropdown içinddeki slidebar kısmı--->
              <div>
                <b-card no-body>
                   <b-card-body
                
     
                   style="position:relative; height:300px; overflow-y:scroll;"
                  >
                       
                          <ul style="list-style-type:none; margin-left:-30px;">
                            <div>
                            <li  class="icdiv" v-for="item in cardItems" :key="item.id">
                                 <a><img :src="item.iconu"  style="width:80px; height:70px;
                                 margin-top:10px;
                               
                                 margin-left:10px;"/></a>
                                 <label 
                                 style="margin-left:10px;"
                                 >Ürün Kodu:<p>{{item.Ukodu}}</p></label>
                                 <p>
                                 <label v-html="item.title" style="margin-left:100px; margin-top:-35px;">{{item.title}}</label>
                                 </p>
                                 <label 
                                 style="margin-left:95px;margin-top:-20px;"
                                 ><p><b>{{item.fiyat}}</b>Tl</p></label>
                                 <label 
                                 style="margin-left:45px;margin-top:-20px;"
                                 ><p>1 Adet</p></label>

                            </li>
                            </div>
                          </ul>

                       <p v-if="cardItems.length ==0">Sepetiniz Boş.</p>
                  </b-card-body>
                </b-card>
              </div>
            </b-dropdown-item>
          <!-- yukarısı dropdown ın iç kısmı  --->
          <div style="width:380px; height:110px; border-top:solid 1px gray; ">
            <button
            style="margin-top:60px; background-color:white;border: 1px solid rgb(74, 19, 82);
            text-color:white;
             margin-left:50px;width:120px; height:40px; border-radius:50px; float:left">
             <a style="color: rgb(74, 19, 82);">  Sepete Git</a>
            </button>
            <button style="margin-top:60px; background-color:rgb(74, 19, 82);
            text-color:white;
             margin-left:30px;width:120px; height:40px; border-radius:50px; float:left">
             <a style="color:white;"> Satın Al &#10140;</a> 
            </button>
            </div>
      
    
            
          </b-dropdown>
        </div>
         
      </b-col>

    </b-row>
  </div>
</template>

<script>
import sepet from "../components/sepetCard"
export default {
    components: {
    sepet
  },
  data(){
    return{
      productList:[
        {
          id:0,
          Ukodu:"10557361",
          title:"Duş Jeli",
          iconu: require('../assets/image/ürün2.webp'),
          count:0,
          fiyat:25
        },
         {
          id:1,
          Ukodu:"38557361",
          title:"Bee Beauty<br>Parfüm",
          iconu: require('../assets/image/ürün3.webp'),
          count:0,
          fiyat:55
        }
      ],
      cardItems:[]
    }
  }
}
</script>

<style scoped>

.icdiv{
  margin-top:5px;
  padding-left:0px;
  border:1px solid;
  height: 150px;
  
}
</style>
