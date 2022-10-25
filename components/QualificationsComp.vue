<template>
    <section data-section="qualifications" class="qualifications-container">
        <b-container> 
            <b-row>
                <h1>Qualifications</h1>
            </b-row>

            <b-row>
                <b-col md="6" cols="12">
                    <p>Education</p>
                </b-col>
                <b-col md="6" cols="12">
                    <p>Work History</p>
                </b-col>

                <ul>
                    <li v-for="user in users" :key="user.id">
                        {{ user }}
                    </li>
                </ul>
            </b-row>    

            <div class="download-btn">
                <button class="button-download">
                    <span class="download-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1.5em" height="1.5em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15V3m0 12l-4-4m4 4l4-4M2 17l.621 2.485A2 2 0 0 0 4.561 21h14.878a2 2 0 0 0 1.94-1.515L22 17"></path></svg>
                    </span>
                Download CV</button>
            </div>

        </b-container>
    </section>   
</template>
<script>

export default {
    props: {
       passdata: {
         type: Object,
         required: true
       }
     },
    data(){
        return {
            users: ''
        }
    },
    async mounted() {
        try{
            const response = await this.$axios.get('https://reqres.in/api/users?page=2');
            this.users = response.data.data;
        }catch(error){
            this.users = error;
        }
    }
    }
</script>
