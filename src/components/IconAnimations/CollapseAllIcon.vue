<template>
  <svg class="icon--collapse-all" aria-hidden="true" viewBox="0 0 32 32">
    <title>collapse all</title>
    <path
      class="collapse-all"
      d="M18,27H4c-1.1,0-2-0.9-2-2v-8c0-1.1,0.9-2,2-2h14c1.1,0,2,0.9,2,2v8C20,26.1,19.1,27,18,27z M4,17v8h14l0-8H4z"
    />
    <path
      class="collapse-all-line1"
      d="M25,20h-2v-8L8.8,12v-2L23,10c1.1,0,2,0.9,2,2V20z"
    />
    <path
      class="collapse-all-line2"
      d="M30,15h-2V7H13.8V5H28c1.1,0,2,0.9,2,2V15z"
    />
  </svg>
</template>
<script>
export default {
  name: "CollapseAllIcon"
};
</script>
<style lang="scss">
.icon--collapse-all {
  width: 32px;
  height: 32px;
}
</style>
