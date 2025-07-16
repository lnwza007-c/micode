<script setup>
const props = defineProps({
  item: {
    type: null,
    required: true,
  },
})
</script>

<template>
  <li class="">
    <div class="title-wrapper">
      <!-- eslint-disable vue/no-v-text-v-html-on-component -->
      <span
        class="title-text"
        icon="ri-subtract-line"
        v-text="item.heading"
      />
      <!-- eslint-enable vue/no-v-text-v-html-on-component -->
    </div>
  </li>
</template>
