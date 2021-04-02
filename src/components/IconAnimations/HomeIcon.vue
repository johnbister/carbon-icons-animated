<template>
  <svg class="icon--home" aria-hidden="true" >
    <title>home</title>
    <path class="home" d="M16.6,2.2c-0.4-0.3-0.9-0.2-1.2,0L1,13.4L2.2,15L4,13.6V26c0,1.1,0.9,2,2,2h20c1.1,0,2-0.9,2-2V13.6l1.8,1.4
		l1.2-1.6L16.6,2.2z M26,26H6V12.1l10-7.8l10,7.8V26z" />
    <path class="home-door-left" d="M12,18v8h2v-8H12z"/>
    <path class="home-door-right" d="M20,18v8h-2v-8H20z" />
    <path class="home-door-top" d="M18,16h-4c-1.1,0-2,0.9-2,2h2h4h2C20,16.9,19.1,16,18,16z" />/>
  </svg>
</template>
<script>
export default {
  name: "HomeIcon"
};
</script>
<style lang="scss">
.icon--home {
  width: 32px;
  height: 32px;
  transition: 0.2s all;
}
</style>
