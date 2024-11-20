<template>
  <footer 
  v-if="$slidev.nav.currentPage !== 1 && $slidev.nav.currentPage !== 34 && $slidev.nav.currentPage !== 37"
  class="absolute bottom-0 right-0">
    <img src="/images/footer.png" />
  </footer>
</template>