<template>
  <div class="">
      <div class="page-changeCity">
        <el-row>
          <el-col :span="24">
            <iSelect></iSelect>
          </el-col>
        </el-row>
        <el-row>
          <el-col :span="24">

            <hot></hot>
          </el-col>
        </el-row>
        <el-row>
          <el-col :span="24">
            <Categroy></Categroy>
          </el-col>
        </el-row>
      </div>

  </div>
</template>

<script>
  import iSelect  from '../components/changeCity/iselect.vue'
  import hot  from '../components/changeCity/hot.vue'
  import Categroy  from '../components/changeCity/categroy.vue'
export default {
      components:{
          iSelect,
           hot,
          Categroy
      }
}
</script>

<style lang="scss">
</style>
