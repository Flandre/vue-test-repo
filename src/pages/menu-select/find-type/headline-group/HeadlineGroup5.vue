<template>
  <div class="headline-group5">
    <ArticleList title="" articleGroup="normal" articleType="" articleSort="21021314" articleLimit="8"/>
  </div>
</template>

<script>
  import ArticleList from '@/components/ArticleList/ArticleList'
  export default {
    name: "headline-group5",
    components: {
      ArticleList
    },
    beforeMount() {
      /* 返回顶部 */
      window.scrollTo(0, 0)
    },
  }
</script>

<style lang="less" scoped>
  .headline-group5 {

  }
</style>
