<template>
    <div class="alt-main">
        <strong style="color:rgb(71, 30, 112); font-size:20px; margin-left:80px; margin-top:-25px;">Alt Kategoriler</strong>
        <div class="alt" style=" padding-top:25px;  margin-top:-12px;">

            <ul style="padding-left:12px; ">
                <li v-for="item in altKategoriler" :key="item" style="font-size:15px;">{{item}}</li>
            </ul>
        </div>

<div class="alt" style="   margin-top:30px;">
  <div style="width:248px; ">
      <a style="float:left; padding-top:2px;  margin-bottom:-27px; color:rgb(68, 37, 93); margin-left:10px;"><b>Markalar</b></a>
      <a style="float:left;padding-top:4px; margin-left:150px; margin-bottom:-27px; color:rgb(68, 37, 93); font-size:12px;"><b>Sırala</b><img src="../assets/image/sort.svg"></a>
      <button v-b-toggle.collapse-a 
      style="margin-left:223px; border:0; color:rgb(68, 37, 93);"
      ><b>&#8744;</b></button>
  </div>
  
  <b-collapse  id="collapse-a" style="border:0;" >
    <b-card>
    <!--burası scrollbar kodu-->
      <div class="scrollbar" id="style-default">
        <div class="force-overflow">
        <!-- burası checkbox ların sıralandığı yer -->
                    <form>
                     <div id="boxi" style="height:70px;">
                         <input type="text" id="search" style="width:210px; padding-left:5px;" placeholder="Markalar Ara">
 
                     </div>
                   </form>
          <ul>
              <li v-for="item in markalar" :key="item" >
              <label class="container">{{item}}
                <input type="checkbox">
                <span class="checkmark"></span>
              </label>
              </li>
          </ul>
        </div>
      </div> 
      <!--__________________________________________-->
    </b-card>
  </b-collapse>
</div>


<!--________________Fiyat aralığı kısmı______________________-->


<div class="alt" style="   margin-top:30px;">
  <div style="width:248px; ">
      <a style="float:left; padding-top:2px;  margin-bottom:-27px; color:rgb(68, 37, 93); margin-left:10px;"><b>Fiyat Aralığı</b></a>
           <button v-b-toggle.collapse-b
      style="margin-left:223px; border:0; color:rgb(68, 37, 93);"
      ><b>&#8744;</b></button>
  </div>
  
  <b-collapse  id="collapse-b" style="border:0;" >
    <b-card>
    <!--burası scrollbar kodu-->
        <div>
            <div style="width:70px; height:35px;border:1px solid gray; border-radius:5px; float:left; text-align:center; padding-top:2px;">5</div>
            <div style="width:70px; height:35px;border:1px solid gray; border-radius:5px; float:left;margin-left:10px;text-align:center; padding-top:2px;">{{value}}</div>
            <button style="font-size:20px; background-color:rgb(68, 37, 93); width:40px; height:35px; border-radius:5px; color:white; margin-left:15px;">&#10140;</button>
           
            <div class="mt-2" style="float:left;">5 TL</div>
            <div class="mt-2" style="margin-left:160px ;">{{ value }} TL</div>

            <b-form-input id="range-1" v-model="value" type="range" min="5" max="85" step="1">
            </b-form-input>
            
            
        </div>
    <!--__________________________________________-->
    </b-card>
  </b-collapse>
</div>




    </div>
</template>

<script>
export default {
    data(){
        return{    
            value:45,
            altKategoriler:["Tırnak","Göz","Dudak","Yüz","Makyaj Paletleri","Makyaj Fırça &\n Aksesuarları","Makyaj Temizleme\n Ürünleri" ],
            markalar:[
            "Flormar(396)",
            "Pastel(329)",
            "Golden Rose(321)",
            "Beaulis(221)",
            "Note(178)",
            "Rimmel London(164)",
            "Pretty By Flormar(161)",
            "wet n wild(144)",
            "essence(140)",
            "Eklips(107)",
            "the Balm(106)",
            "Max Factor(100)",
            "Nascita(67)",
            "Cecile(66)",
            "Maybelline New York(59)",
            "Pierre Cardin(58)",
            "Loreal Paris(48)",
            "New Well(46)",
            "Cocosh She(39)",
            "Lionesse(38)",
            "Promani(35)",
            "Benri(32)"]
        }
    }
}
</script>

<style scoped>


/*_____________________________________*/
.scrollbar
{
	margin-left: -20px;
	float: left;
	height: 250px;
	width: 247px;
	background: #ffffff;
	overflow-y: scroll;
	margin-bottom: -20px;
}

.force-overflow
{
	min-height: 450px;
}

ul { list-style-type:none; }
.alt-main{
    width:350px;
    height:1100px;
    background-color: rgb(255, 255, 255);
    padding-top:70px;
    border:solid 1px rgb(10, 10, 10);
    
}
.alt{
    border:solid 1px rgb(153, 151, 151);
    border-radius: 5px;
    width:250px;
    height:auto;
    margin-left: 25px;
 
  
}
/*checkbox kutusunun büyümesi için*/
.container {
  display: block;
  position: relative;
  padding-left: 15px;
  margin-bottom: 12px;
  cursor: pointer;
  font-size: 15px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/* Hide the browser's default checkbox */
.container input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
  height: 0;
  width: 0;
}

/* Create a custom checkbox */
.checkmark {
  position: absolute;
  top: 0;
  left: -20px;
  height: 23px;
  width: 23px;
  background-color: rgb(255, 255, 255);
  border:1px solid rgb(68, 37, 93);
  border-radius: 2px;
}


/* Create the checkmark/indicator (hidden when not checked) */
.checkmark:after {
  content: "";
  position: absolute;
  display: none;
}

/* Show the checkmark when checked */
.container input:checked ~ .checkmark:after {
  display: block;
}

/* Style the checkmark/indicator */
.container .checkmark:after {
  left: 6px;
  top: -2px;
  width: 9px;
  height: 18px;
  border: solid rgb(134, 27, 148);
  border-width: 0 3px 3px 0;
  -webkit-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  transform: rotate(45deg);
}
</style>