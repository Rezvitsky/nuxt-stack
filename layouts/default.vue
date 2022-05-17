<template>
  <div>
    <nav class="flex align-center gap-4 p-4">
      <NuxtLink to="/">
        Index
      </NuxtLink>
      <NuxtLink to="/welcome">
        Welcome
      </NuxtLink>
    </nav>

    <slot />
    
  </div>
</template>