# Search Bar Nuxt Component

Search bar with `<kbd>` inside

```
<template>
  <div class="w-96">
    <UInput
      v-model="q"
      name="q"
      placeholder="Search..."
      icon="i-heroicons-magnifying-glass-20-solid"
      :ui="{ icon: { trailing: { pointer: '' } } }"
    >
      <template #trailing>
        <div class="flex items-center gap-0.5">
          <UKbd>{{ metaSymbol }}</UKbd>
          <UKbd>K</UKbd>
        </div>
        <UButton
          v-show="q !== ''"
          color="gray"
          variant="link"
          icon="i-heroicons-x-mark-20-solid"
          :padded="false"
          @click="q = ''"
        />
      </template>
    </UInput>
  </div>
</template>

<script setup lang="ts">
const q = ref("");

const { metaSymbol } = useShortcuts();
</script>
```
