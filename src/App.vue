<template>
  <div>
    <Header></Header>
    <router-view></router-view>
  </div>
</template>

<script>
import Header from "components/common/Header.vue";
export default {
  components: {
    Header,
  },
};
</script>
<style></style>
