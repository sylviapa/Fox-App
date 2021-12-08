<template>
  <span>
    <img :src="fox" class="favorites-img" />
    <button @click="removeFave(index)" class="remove">Remove</button>
  </span>
</template>

<script>
export default {
  props: {
    fox: {
      type: String,
    },
  },
};
</script>