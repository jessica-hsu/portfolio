<template>
  <div class="common-layout">
    <el-container>
      <el-aside>
        <NavBar/>
      </el-aside>
      <el-container>
        <RouterView/>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import { RouterView } from 'vue-router';

export default {
  components: {
    NavBar,
    RouterView
  }
}
</script>

<style>
.common-layout {
    font-family: verdana;
}
</style>


