<template>
    <div class="mor">
        <b-row >
          <b-col cols="2" class="mor-div"></b-col>
          <b-col cols="8" class="mor-div">

            <ul>
                <li v-for="item in iconimage" :key="item.id" class="mor-li">
                 <a><img :src="item.icon" class="mor-img"/></a>
                 <a style="padding-top:10px;" ><strong>{{item.title}}</strong></a>
               </li>
            </ul> 

          </b-col>
          <b-col cols="2" class="mor-div"></b-col>
        </b-row>

    </div>
</template>

<script>
export default{
    data(){
        return{
            iconimage:[
            {
              id:0,
              title:"Mağazalarımız",
              icon: require('../assets/image/magaza.svg')
            },
            {
              id:1,
              title:"Kolay İade",
              icon: require('../assets/image/teslimat.svg')
            },
            {
              id:2,
              title:"Yardım ve Destek",
              icon: require('../assets/image/simit.svg')
            },
            {
              id:3,
              title:"İletişim",
              icon: require('../assets/image/iletisim.svg')
            },
            ]
        }
    }
}
</script>
<style>
ul{
list-style:none;
}
.mor-li{
     
     float: left;
     padding-left: 100px;
}
.mor-li>a {
     color: black !important;
     display: block;
     margin-top: 15px;
     float: left;
     margin-right: 10px;
 }
.mor-img{
     width:50px
 }
.mor{
   
    height:80px;
    padding-right:auto;
    padding-left:auto;
}

.mor-div{
 background-color: rgb(230, 189, 230);
}
</style>