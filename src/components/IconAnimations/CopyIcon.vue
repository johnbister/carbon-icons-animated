<template>
  <svg class="icon icon--copy" aria-hidden="true" viewBox="0 -10 36 44">
    <title>copy</title>
    <path
      class="copy-new"
      d="M4,18H2V4c0-1.1,0.9-2,2-2h14v2H4V18z"
    />
    <path class="copy-original" d="M28,10v18H10V10H28 M28,8H10c-1.1,0-2,0.9-2,2v18c0,1.1,0.9,2,2,2h18c1.1,0,2-0.9,2-2V10C30,8.9,29.1,8,28,8z" />
  </svg>
</template>
<script>
export default {
  name: "CopyIcon"
};
</script>
<style lang="scss">
.icon--copy {
  width: 36px;
  height: 44px;
  margin-top: -12px;
}
</style>
