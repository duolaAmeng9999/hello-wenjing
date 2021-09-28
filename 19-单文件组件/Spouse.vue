<template>
  <div class="spouse">
    <h3>对象: {{ name }}</h3>
    <h3>年龄: {{ age }}</h3>
    <h3>爱好: {{ hobby }}</h3>
    <button @click="showName">点我提示对象名字</button>
  </div>
</template>

<script>
export default {
  name: "Spouse",
  data() {
    return {
      name: "刘文静",
      age: 22,
      hobby: "逛街",
    };
  },
  methods: {
    showName() {
      alert(this.name);
    },
  },
};
</script>

<style>
.spouse {
  color: aqua;
}
</style>
