<template>
  <div>
    <TheNavBar />
    <div class="w-4/5">
      <slot />
    </div>
    <TheFooter />
  </div>
</template>

<style>
.document-driven-page {
  /* @apply bg-gray-900 h-screen text-white; */
}
</style>
