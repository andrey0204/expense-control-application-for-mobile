<template>
  <LayoutCash>
    <template #header>
      <HeaderCash></HeaderCash>
    </template>
  </LayoutCash>
</template>

<script>
import LayoutCash from "./LayoutCash.vue";
import HeaderCash from "./HeaderCash.vue";

export default {
  components: {
    LayoutCash,
    HeaderCash,
  },
};
</script>
