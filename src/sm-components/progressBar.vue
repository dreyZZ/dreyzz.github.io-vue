<template>
  <div class="progress space" :style="{ height: styleObj.height }">
    <div
      class="progress-bar bar"
      :style="styleObj"
      aria-valuenow="value"
      aria-valuemin="0"
      aria-valuemax="100"
    >
      {{ name }}
    </div>
  </div>
</template>


<script>
export default {
  props: ["name", "value"],
  data: function () {
    return {
      styleObj: {
        height: "30px",
        textAlign: "center",
        fontSize: "20px",
        width: this.value + "%",
      },
    };
  },
};
</script>

<style lang="scss">
.bar {
  background-color: black !important;

  &:hover {
    background-color: rgb(35, 75, 75) !important;
  }
}

.space {
  background-color: grey;
}
</style>
