<template>
    <div>
       <div>
         <h4> None Component</h4>
         <pre>{{passdata}}</pre>
       </div>
     </div>
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