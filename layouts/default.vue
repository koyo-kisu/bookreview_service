<template>
  <div>
    <TheHeader />
      <nuxt />
    <TheFooter />
  </div>
</template>

<style>


</style>

<script>
import TheHeader from '~/layouts/TheHeader.vue';
import TheFooter from '~/layouts/TheFooter.vue';
import Detail from '~/pages/Detail.vue';
import TheBook_serch from '~/pages/Book-serch';
import TheRecommend_post from '~/pages/Recommend';
// import Searchresult from '~/pages/Searchresult.vue';

export default {
    components: {
      TheHeader,
      TheFooter
    }  
}
</script>
