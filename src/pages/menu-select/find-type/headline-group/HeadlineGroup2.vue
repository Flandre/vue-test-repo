<template>
  <div class="headline-group2">
    <ArticleList title="" articleType="" articleSort="130241201" articleLimit="8"/>
  </div>
</template>

<script>
  import ArticleList from '@/components/ArticleList/ArticleList'
  export default {
    name: "headline-group2",
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
  .headline-group2 {

  }
</style>
