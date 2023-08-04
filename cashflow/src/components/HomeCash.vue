<template>
  <LayoutCash>
    <template #header>
      <HeaderCash></HeaderCash>
    </template>
    <template #resume>
      <ResumeCash></ResumeCash>
    </template>
    <template #movements>
      <MovementsCash></MovementsCash>
    </template>
  </LayoutCash>
</template>

<script>
import LayoutCash from "./LayoutCash.vue";
import HeaderCash from "./HeaderCash.vue";
import ResumeCash from "./ResumeCash.vue";
import MovementsCash from "./MovementsCash.vue";

export default {
  components: {
    LayoutCash,
    HeaderCash,
    ResumeCash,
    MovementsCash,
  },
};
</script>
