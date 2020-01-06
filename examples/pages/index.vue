<template>
  <div class="m-index">
    可能需要首页
    <router-link :to="{name: 'giud'}">开始使用</router-link>
  </div>
</template>

<script>
export default {
  data () {
    return {
      height: document.documentElement.clientHeight
    }
  }
}
</script>
<style type="text/scss" lang="scss">

</style>
