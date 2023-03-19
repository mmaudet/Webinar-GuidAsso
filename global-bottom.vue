<!-- global-bottom.vue 
<template>
  <footer class="absolute bottom-0 left-0 right-0 p-2">"$slidev.nav.currentPage"</footer>
</template>-->

<template> 
    <footer v-if="$slidev.nav.currentLayout !== 'cover'" class="absolute bottom-0 right-0 p-2 text-teal-900" > {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }} </footer>
</template>