<template>
   <div class="m-geo">
     <i class="el-icon-location">
        {{$store.state.geo.position.city}}
        <nuxt-link class="changeCity" to="/changeCity">切换城市</nuxt-link>
       [香河 浪凡 田径]
     </i>
   </div>
</template>

<script>

export default {

}
</script>

<style >

</style>
