<!--  -->
<template>
  <swiper>
    <swiper-item v-for="item in banners">
      <a :href="item.link">
        <img :src="item.image">
      </a>
    </swiper-item>
  </swiper>
</template>

<script>
import { Swiper, SwiperItem } from '@/components/common/swiper'

export default {
  name: '',
  props: {
    banners: {
      type: Array,
      default() {
        return []
      }
    }
  },
  data() {
    return {}
  },
  components: {
    Swiper,
    SwiperItem
  },
  computed: {},
  beforeMount() {},
  mounted() {},
  methods: {},
  watch: {}
}
</script>

<style lang='' scoped>
</style>