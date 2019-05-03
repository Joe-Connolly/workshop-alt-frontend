<template>
  <div class="count">#Todo Items: <strong>{{count}}</strong></div>
</template>

<script>
export default {
  name: "view-count",
  props: ["count"],
  methods: {
  }
};
</script>


<style>
.count {
  margin: 0px 10px;
};
</style>