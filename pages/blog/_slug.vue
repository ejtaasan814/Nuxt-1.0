<template>
    <article>
        <!-- <nuxt-content :document="article" /> -->
        <!-- <AuthorComp :author="article.author" /> -->
        <!-- <Lazy-WebsiteComp :website="article.website" /> -->
        <lazy-component :is="s.template" v-for="s in article.sections" :key="s.name" :passdata="s"></lazy-component>
        <!-- <pre>{{article}}</pre> -->
        <!-- <pre>{{slug}}</pre> -->
        <!-- url: http://localhost:57373/blog/second-content -->
    </article>
    
</template>

<script>  
    export default {
      layout: 'default-layout',
      async asyncData({ $content, params }) {
        const article = await $content('articles', params.slug).fetch()
        const slug = params.slug // When calling /abc the slug will be "abc"
        return { article,slug }
      },
     
    }
  </script>