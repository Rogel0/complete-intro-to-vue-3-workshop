<script>
export default {
  props: {
    text: String,
    icon: String,
    iconRight: String,
  },
};
</script>

<template>
  <button>
    <slot>Submit</slot>
  </button>
</template>
