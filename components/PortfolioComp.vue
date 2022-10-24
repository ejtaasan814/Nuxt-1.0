<template>
    <div class="portfolio-container">
      <b-container>
            <b-row>
               <h1>Portfolio</h1>
            </b-row>

            <VueSlickCarousel v-bind="settings">

            <div>
                <div class="portfolio-box">
                    <div class="portfolio-image">
                        <img src="https://skytronixsglobal.com/assets/images/footerlogo.png" />
                    </div>
                    
                </div>
            </div>


            <div>
                <div class="portfolio-box">
                    <div class="portfolio-image">
                        <img src="https://ussc.com.ph/_nuxt/img/ussclogo-2.cf60118.svg" />
                    </div>
                </div>
            </div>


            <div>
                <div class="portfolio-box">
                    <div class="portfolio-image">
                        <img src="http://www.skytronixscharities.com/assets/images/home/Lower_SClogo.png" />
                    </div>
                </div>
            </div>


             <div>
                <div class="portfolio-box">
                    <div class="portfolio-image">
                        <img src="http://www.skytronixscharities.com/assets/images/home/Lower_SClogo.png" />
                    </div>
                </div>
            </div>

            
            </VueSlickCarousel>
            
        </b-container>  
    </div>
</template>

<script>
    import VueSlickCarousel from 'vue-slick-carousel'
    import 'vue-slick-carousel/dist/vue-slick-carousel.css'
    // optional style for arrows & dots
    import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
    
export default {
      components: { VueSlickCarousel },
      props: {
        passdata: {
          type: Object,
          required: true
        }
      },
      data(){
        return {
            settings: {
            "dots": true,
            "focusOnSelect": true,
            "infinite": false,
            "speed": 500,
            "slidesToShow": 3,
            "slidesToScroll": 1,
            "touchThreshold": 5,
            responsive: [{
                breakpoint: 991.99,
                settings: {
                    swipe: true,
                    variableWidth: false,
                    centerMode: true,
                    slidesToShow: 1
                }
            }]
            }
        }
    }
}
</script>