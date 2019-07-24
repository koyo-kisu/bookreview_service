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
import TheHeader from '~/components/TheHeader.vue';
import TheFooter from '~/components/TheFooter.vue';
import Detail from '~/pages/Detail.vue';
import TheBook_serch from '~/pages/Book-serch';
import TheRecommend_post from '~/pages/Recommend';

export default {
    components: {
      TheHeader,
      TheFooter,
    }  
}
</script>
