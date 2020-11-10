<template>
  <div class="home">

    <mor/>
    <headerr/>
    
    <megamenu/>
  </div>
</template>

<script>
// @ is an alias to /src


import mor from '../components/mor'
import headerr from '../components/header'
import megamenu from '../components/megaMenu'

export default {
  name: 'Home',
  components: {
    mor,
    headerr,
    megamenu
  }
}
</script>
