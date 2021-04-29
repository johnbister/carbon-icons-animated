<template>
  <svg class="icon icon--purchase" aria-hidden="true">
    <title>purhcase</title>
    <path class="purchase-stripe" d="M6,20h10v2H6V20z" />
    <path
      class="purchase-card"
      d="M28,6H4C2.9,6,2,6.9,2,8v16c0,1.1,0.9,2,2,2h24c1.1,0,2-0.9,2-2V8C30,6.9,29.1,6,28,6z M28,8v3H4V8H28z M4,24V13h24v11H4z"
    />
  </svg>
</template>
<script>
export default {
  name: "PurchaseIcon"
};
</script>
<style lang="scss">
.icon--purchase {
  width: 32px;
  height: 32px;
}
</style>
