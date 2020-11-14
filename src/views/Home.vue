<template>
  <div class="home">

    <mor/>
    <headerr/>
    <megamenu/>
    <altkategori/>
  </div>
</template>

<script>
// @ is an alias to /src


import mor from '../components/mor'
import headerr from '../components/header'
import megamenu from '../components/megaMenu'
import altkategori from '../components/altKategoriler'
export default {
  name: 'Home',
  components: {
    mor,
    headerr,
    megamenu,
    altkategori
  }
}
</script>
