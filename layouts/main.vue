<template>
    <div class="home-page">
             <header1/>
             <megaMenu/>
        <nuxt/>
           
    </div>
</template>

<script>

import header1 from "~/components/header"
import megaMenu from "~/components/megaMenu"

export default {
    components:{
        header1,
        megaMenu
    }
}
</script>
<style>

</style>