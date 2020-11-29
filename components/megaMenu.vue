<template>
    <div class="megamenu">
    <div class="navt">
        <div class="container2">
            <ul class="menu-main">
                <li class="baslık"><nuxt-link to="/Anasayfa/icerik">Makyaj</nuxt-link>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/m1.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/m2.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/m3.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="">Cilt Bakım</a>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/yuzmaske001.png" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/epilasyon-revize.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/c3.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="">Saç Bakım</a>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/s1.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/s2.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/s3.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="">Sağlık & Hijyen</a>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/agiz.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/h2.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/h3.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="">Parfüm & Deodorant</a>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/p1.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/p2.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/p3.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="">Erkek Bakım</a>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/tiras.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/e2.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/erkek.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="">Ev & Yaşam</a>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/ey1.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/odasprey.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/ey3.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="">Anne & Bebek</a>
                    <div class="menu-sub">
                        <div class="menu-sub">
                            <div class="menu-col-1">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="Makyaj" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-2">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-3">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-4">
                              <ul>
                                 <li  v-for="i in Makyaj" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Dudaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                 </li>
                                 <br>
                                  <li  v-for="i in Tırnaklar" v-html="i" v-text="i" :key="i">
                                  <a style="padding-top:10px;" >{{i}}</a>
                                  </li>
                                  <br>
                              </ul>
                            </div>
                            <div class="menu-col-5">
                                <ul >
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/bp.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/ab2.jpg" /></li>
                                    <li class="resimler"> <img src="https://www.gratis.com/file/general/ab3.jpg" /></li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </li>
                <li class="baslık"><a href="" style=" color: rgb(209, 19, 146);" ><strong>OUTLET</strong></a></li>
                <li class="baslık"><a href="" style=" color: rgb(209, 19, 146);" ><strong>Trendler</strong></a></li>
            </ul>
        </div>
    </div>
    </div>
    
</template>
<script>
export default {
    data(){
        return{
            Makyaj:[
            'Göz ',
            'Maskara',
            'Göz Kalemi',
            'Eyeliner',
            'Göz Farı',
            'Kaş Makyajı',
            'Far & Maskara Bazı'],

            Dudaklar:[
              'Dudaklar',
              "Ruj",
              "Dudaklar Parlatıcısı",
              "Dudak Kalemi"
            ],

            Tırnaklar:[
             'Tırnaklar',
             "Oje",
             "Aseton"
            ]
       }
    }   
}
</script>

<style>
.resimler{
  padding-top:25px;
}
.mor-li-a{
  width:45px;
  font-size:15px;
}
#container2{
  
    width: 100%;
    margin: auto;
    overflow:hidden;
    height: 70px;

}

/*mega menü ekranı*/
/*başlıkları ortala için .menu-main ı kullanırız*/
  .menu-main{
      margin:0 auto;
      display: flex;
      position: relative;
      padding:0;
      justify-content: center;
 
  }
  .menu-main a{
      text-transform: uppercase;
  }
  .navt {
    padding-top: 7px;
    height: 50px;
    width:100%;
    background: rgb(112, 52, 114);
    box-shadow: 0 0 15px 0 rgba(0,0,0,.10);
    

  }
  
  .navt ul {
      
    height: 30px;
    margin: 0 auto;
    padding: 0;
    list-style: none;
    position: relative;
    text-align: left;
    justify-content: center;
  
  }
  
  .baslık {
    vertical-align: middle;
    display: inline-block;
    border-right:solid 1px rgb(238, 17, 209);
  }

  .navt a {
    color: rgb(255, 255, 255);
    font-size: 12px;
    font-weight: bold;
    font-family: helvetica,sans-serif;
    text-decoration: none;
    display: block;
    padding-right:5px;
    padding-left:5px;
    padding-top: 10px;
    text-align: center;
    line-height: 18px;
    
  }

  .navt li:hover a {
    color: rgb(255, 251, 0);
        
  }
  #ff{
      
      padding: 17px 10px 10px 15px;
      height:57px;
    }
  
  .menu-sub {

    padding-left: 12%;
    height:550px;
    position: absolute;
    left: 0;
    background: rgb(40, 44, 78);
    width:100%;
    display: none;
    color: white;
    opacity: 0.75;
    margin-top:15px

  }
  
  .navt li:hover .menu-sub {
    display: block;
  }
  
  .menu-sub li {
    display: block;
    
  }
  
  .menu-sub a {
    padding: 0;
  }
  
  .menu-sub a:hover {
    text-decoration: underline;
  }
  
  .menu-category {
    margin: 2.5em 0 .5em;
    ;
  }
  
  .menu-category:first-of-type {
    margin-top: 0;
  }
  
  .menu-col-1,
  .menu-col-2,
  .menu-col-3, 
  .menu-col-4 {
    float: left;
    width: 200px;
    margin-left: 2%;


  }
  .menu-col-5{
    float: left;
    width: 400px;
  }
  .menu-col-1>button{
    background-color:transparent;
    border-width: 0px;
  }
  .menu-col-1>button:hover{
  color: rgb(255, 96, 0);
  }
  .menu-col-2>button{
    background-color:transparent;
    border-width: 0px;
  }
  .menu-col-2>button:hover{
  color: rgb(255, 96, 0);
  }
  .menu-col-3>button{
    background-color:transparent;
    border-width: 0px;
  }
  .menu-col-3>button:hover{
  color: rgb(255, 96, 0);
  }
  .menu-col-4>button{
    background-color:transparent;
    border-width: 0px;
  }
  .menu-col-4>button:hover{
  color: rgb(255, 96, 0);
  }

  /*-----Dropdown menü ( elektronik kısmının )-----*/
  
</style>