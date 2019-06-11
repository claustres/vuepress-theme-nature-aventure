<template>
  <Layout>
    <Banner slot="sidebar-top"/>
  </Layout>
</template>

<script>
import Layout from '@parent-theme/layouts/Layout.vue'
import Banner from '@theme/components/Banner.vue'

export default {
  components: {
    Layout,
    Banner
  }
}
</script>
