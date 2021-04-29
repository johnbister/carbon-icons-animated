<template>
  <svg class="icon--data--base" aria-hidden="true" viewBox="0 0 32 32">
    <title>data base</title>
    <path
      d="M24,3H8C6.9,3,6,3.9,6,5v22c0,1.1,0.9,2,2,2h16c1.1,0,2-0.9,2-2V5C26,3.9,25.1,3,24,3z M24,5v6H8V5H24z M8,19v-6h16v6H8z
		 M8,27v-6h16v6H8z"
    />
    <circle class="database-circle1" cx="11" cy="8" r="1" />
    <circle class="database-circle2" cx="11" cy="16" r="1" />
    <circle class="database-circle3" cx="11" cy="24" r="1" />
  </svg>
</template>
<script>
export default {
  name: "DataBaseIcon"
};
</script>
<style lang="scss">
.icon--data--base {
  width: 32px;
  height: 32px;
  transition: 0.2s all;
}
</style>
