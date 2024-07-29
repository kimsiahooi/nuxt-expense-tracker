<template>
  <div>
    <header class="py-4">
      <div class="container mx-auto">
        <div class="flex items-center justify-between">
          <NuxtLink to="/" class="text-2xl font-semibold">OKS</NuxtLink>

          <ul class="flex items-center space-x-10">
            <li>
              <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/transactions">Transactions</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </header>
    <slot />
  </div>
</template>

<style>
body {
  @apply font-mono;
}
</style>
