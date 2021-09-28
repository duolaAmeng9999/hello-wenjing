<template>
    <div>
        <Girlfriend></Girlfriend>
        <Spouse></Spouse>
    </div>
</template>

<script>
// 引入组件
import Girlfriend from "./Girlfriend.vue";
import Spouse from "./Spouse.vue";
export default {
  name: "App",
  components: {
      Girlfriend,
      Spouse
  }
};
</script>

<style>

</style>