<template>
  <article>
      <!-- <nuxt-content :document="article" /> -->
      <!-- <AuthorComp :author="article.author" /> -->
      <!-- <Lazy-WebsiteComp :website="article.website" /> -->
      <lazy-component :is="s.template" v-for="s in indexdata.sections" :key="s.name" :passdata="s"></lazy-component>
     
  </article>
  
</template>

<script>
  export default {
    name: 'IndexPage',
    layout: 'default-layout',
    async asyncData({ $content, params }) {
      const indexdata = await $content('pages', 'index').fetch()
      const slug = params.slug // When calling /abc the slug will be "abc"
      return { indexdata,slug }
    },
   
  }
</script>