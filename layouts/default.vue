<template>
  <div>
    <default-header />
    <nuxt />
    <default-footer />
  </div>
</template>

<script>
import DefaultFooter from '@/components/Footer/DefaultFooter'
import DefaultHeader from '@/components/Header/DefaultHeader'
export default {
  components: {
    DefaultFooter,
    DefaultHeader
  }
}
</script>
