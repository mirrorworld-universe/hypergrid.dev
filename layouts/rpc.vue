<template>
  <main
    class="max-w-[720px] mx-auto w-full px-4 py-12 md:py-16 prose dark:prose-invert font-sans prose-headings:font-sans"
    meta-layout="rpc"
  >
    <slot />
  </main>
</template>

<script lang="ts" setup>
definePageMeta({
  name: "rpc",
});
</script>
