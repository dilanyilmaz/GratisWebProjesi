<template>
  <div id="app">
    <b-rol>
      <b-col cols="12"> <router-link to="/home">home</router-link></b-col>
      <b-col cols="12"> <router-link to="/about">about</router-link></b-col>
      <b-col cols="12">  <router-link to="/uye">uye</router-link></b-col>
    </b-rol>



<router-view/>
</div>
</template>