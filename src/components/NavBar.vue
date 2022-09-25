<template>
  <el-menu
    default-active="2"
  >
    <el-menu-item index="1">
      <RouterLink to="/"><span>Home</span></RouterLink>
    </el-menu-item>
    <el-menu-item index="2">
      <RouterLink to="/work"><span>Work</span></RouterLink>
    </el-menu-item>
    <el-menu-item index="3">
      <RouterLink to="/projects"><span>Projects</span></RouterLink>
    </el-menu-item>
    <el-menu-item index="4">
      <RouterLink to="/contact"><span>Contact</span></RouterLink>
    </el-menu-item>
  </el-menu>
</template>
<script>
import { RouterLink } from 'vue-router';

export default {
    components: {
        RouterLink,
    },
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<style scoped>
.el-menu {
  height: 100vh;
  padding: 1rem;
}
</style>
