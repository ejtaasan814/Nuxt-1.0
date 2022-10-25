<template>
    <section data-section="banner" class="banner-container">
        <b-container>
            <div class="banner-content">
                <b-row>
                    <b-col md="6">    
                        <div class="banner-text">
                            <h1>EJ Von Taasan</h1>
                            <h6><em>Fullstack Developer</em></h6>
                            <p>I'm Experienced Fullstack Developer with a demonstrated history of working in the information technology and services industry. Highly skilled in JavaScript(React/VueJS)</p>       
                        </div>
                        <div class="contact-btn">
                            <button class="contact">
                                <span class="circle" aria-hidden="true">
                                <span class="icon arrow"></span>
                                </span>
                                <span class="button-text">Contact me</span>
                            </button>
                        </div>
                    </b-col>

                    <b-col md="6">    
                        <div class="model-container">
                            <img class="model-img" src="uploads/model.jpeg" />
                        </div>
                    </b-col>
                </b-row>
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
      }
    }
</script>