<template>
    <section data-section="qualifications" class="skills-container">
        <b-container>
            <b-row>
               <h1>Skills</h1>
            </b-row>
            <div class="skills-box-container">


                <div class="skills-box">
                    <h5>Frontend Development</h5>
                    <p class="exp-text">+4 years of experience</p>
                    <div class="skills-img-container">
                        <b-row>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/130px-HTML5_logo_and_wordmark.svg.png" />
                                    <p>HTML5</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/120px-CSS3_logo_and_wordmark.svg.png" />
                                    <p>CSS</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                <img src="https://seeklogo.com/images/B/bootstrap-logo-3C30FB2A16-seeklogo.com.png" />
                                <p>Bootstrap</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/JavaScript-logo.png/600px-JavaScript-logo.png?20120221235433" />
                                    <p>Javascript</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Nuxt_logo.svg/512px-Nuxt_logo.svg.png?20201218211241" />
                                <p>Nuxt JS</p>
                            </b-col>
                        </b-row>
                    </div>  
                </div>  



                <div class="skills-box">
                    <h5>Backend Development</h5>
                    <p class="exp-text">+4 years of experience</p>
                    <div class="skills-img-container">
                        <b-row>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://cdn-icons-png.flaticon.com/512/5968/5968332.png" />
                                    <p>PHP</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Laravel.svg/121px-Laravel.svg.png" />
                                    <p>Laravel</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                <img src="https://cdn3.iconfinder.com/data/icons/social-media-2169/24/social_media_social_media_logo_codeigniter-512.png" />
                                <p>Codeigniter</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://www.freepnglogos.com/uploads/logo-mysql-png/logo-mysql-mysql-logo-png-images-are-download-crazypng-21.png" />
                                    <p>MySQL</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcThLtJQfB5EySutqgZig2Dwb_HDgY8P-3lSyAdFPlD0EPpjgrA&s" />
                                <p>Node JS</p>
                            </b-col>
                        </b-row>
                    </div>  
                </div>


                <div class="skills-box">
                    <h5>Others</h5>
                    <p class="exp-text"></p>
                    <div class="skills-img-container">
                        <b-row>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://seeklogo.com/images/G/github-logo-5F384D0265-seeklogo.com.png" />
                                    <p>GIT</p>
                            </b-col>
                            <b-col md="4" cols="3" class="skills-img">
                                    <img src="https://seeklogo.com/images/D/docker-logo-CF97D0124B-seeklogo.com.png" />
                                    <p>Docker</p>
                            </b-col>
                        </b-row>
                    </div> 
                </div>




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