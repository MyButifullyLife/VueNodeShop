<template>
  <div class="page-index">
    <el-row>
      <el-col :span="5">
        <emenu/>
      </el-col>
      <el-col :span="19">
        <life/>
      </el-col>
    </el-row>
    <el-row >
      <el-col :span="24">
        <artistic/>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import Emenu from '../components/public/index/menu.vue'
import Life from '../components/public/index/life.vue'
import Artistic from '../components/public/index/artistic.vue'
export default {
  components: {
    Emenu,
    Life,
    Artistic
  }
}
</script>

<style lang="scss">
  @import "@/assets/css/index/index.scss";
</style>
