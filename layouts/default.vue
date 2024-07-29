<template>
  <div class="flex flex-col min-h-screen">
    <header class="py-4">
      <div class="container mx-auto">
        <div class="flex items-center justify-between">
          <NuxtLink to="/" class="text-2xl font-semibold">OKS</NuxtLink>

          <ul class="flex items-center space-x-10 md:space-x-16">
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
    <main class="flex-1 flex flex-col">
      <slot />
    </main>
    <Toaster />
  </div>
</template>

<style>
body {
  @apply font-mono;
}
</style>
