<template>
  <a
    class="text-blue-800 underline hover:text-black"
    :href="url"
    target="_blank"
    >{{ text }}</a
  >
</template>

<script>
export default {
  props: {
    url: { type: String, default: '' },
    text: { type: String, default: '' },
  },
}
</script>
