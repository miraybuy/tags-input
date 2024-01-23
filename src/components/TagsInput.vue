<template>
  <div v-text="tags.length"></div>
  <input type="text" />
</template>

<script>
export default {
  data: () => ({
    tags: ["vue", "react", "angular"],
  }),
};
</script>
