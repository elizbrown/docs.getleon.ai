<template>
  <ParentLayout>
    <CarbonAds slot="sidebar-top"/>
  </ParentLayout>
</template>

<script>
  import ParentLayout from '@parent-theme/layouts/Layout.vue'
  import CarbonAds from '../components/CarbonAds.vue'
  export default {
    components: {
      ParentLayout,
      CarbonAds
    }
  }
</script>
