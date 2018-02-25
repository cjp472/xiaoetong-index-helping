<template>
  <div>
    <xheader></xheader>
    <xnav></xnav>
    <router-view/>
    <xfooter></xfooter>
    <backToTop></backToTop>
  </div>
</template>

<script>
import xfooter from 'helping/xfooter/xfooter'
import xheader from 'helping/xheader/xheader'
import xnav from 'helping/xnav/xnav'
import backToTop from '@/components/common/backToTop/backToTop'

export default {
  components: {
    xfooter,
    xheader,
    xnav,
    backToTop
  }
}
</script>
