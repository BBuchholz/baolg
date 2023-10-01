<script>
export default {
  name: 'AppDropDownContent',
  inject: ['sharedState'],
  computed: {
    active() {
      return this.sharedState.active
    },
  },
}
</script>

<template>
  <div v-if="active">
    <slot />
  </div>
</template>
