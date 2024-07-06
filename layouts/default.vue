<template>
  <main
    class="max-w-[720px] mx-auto w-full px-4 py-12 md:py-16 prose dark:prose-invert font-sans prose-headings:font-sans"
    meta-layout="default"
  >
    <HypergridLogo class="text-black max-h-10 w-fit" />
    <NuxtLink
      to="/rpc"
      class="absolute text-black top-16 right-16 outline-none"
    >
      RPC Summit - London 🇬🇧 2024
    </NuxtLink>
    <slot />
  </main>
</template>
