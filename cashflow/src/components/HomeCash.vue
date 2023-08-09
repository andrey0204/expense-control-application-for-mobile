<template>
  <LayoutCash>
    <template #header>
      <HeaderCash></HeaderCash>
    </template>
    <template #resume>
      <ResumeCash
        :totalLabel="'Ahorro Total'"
        :label="label"
        :amount="amount"
        :totalAmount="40000"
      >
        <template #graphic> Graphic</template>
        <template #action>Action</template>
      </ResumeCash>
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
  data() {
    return {
      amount: null,
      label: null,
    };
  },
};
</script>
