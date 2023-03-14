<template>
  <button type="button" class="big-btn" @click="$emit('onClick')">
    {{ content }}
  </button>
</template>

<script>
export default {
  name: 'BigBtn',
  props: {
    content: String
  },
}
</script>

<style>
.big-btn {
  display: block;
  padding: 2%;
  color: white;
  background-color: #0e8ac4;
}
</style>
