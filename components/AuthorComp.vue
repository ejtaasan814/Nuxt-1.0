<template>
  <b-container class="author-row">
    <b-row>
      <b-col md="4"><pre>{{passdata}}</pre></b-col>
      <b-col md="4"><pre>{{passdata}}</pre></b-col>
      <b-col md="4"><pre>{{passdata}}</pre></b-col> 
    </b-row>
  </b-container>
</template>

<script>
export default {
     props: {
       passdata: {
         type: Object,
         required: true
       }
     }
   }
</script>