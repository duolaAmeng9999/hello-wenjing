<template>
  <div class="demo">
    <h3>girlfriend: {{ name }}</h3>
    <h3>年龄: {{ age }}</h3>
    <button @click="showName">点我提示女朋友姓名</button>
  </div>
</template>

<script>
export default {
  name: "Girlfriend",
  data() {
    return {
      name: "wenjing",
      age: 22,
    };
  },
  methods: {
    showNamw() {
      console.log(this.name);
    },
  },
};
</script>

<style>
.demo {
  background: palegoldenrod;
  color: aqua;
}
</style>