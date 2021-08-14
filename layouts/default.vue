<template>
  <div>
    <the-header />
    <transition>
      <nuxt />
    </transition>
    <the-footer />
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue'
import TheFooter from '@/components/TheFooter.vue'

export default {
  name: 'Default',
  components: {
    'the-header': TheHeader,
    'the-footer': TheFooter,
  },
}
</script>
