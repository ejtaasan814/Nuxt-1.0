<template>
    <div class="portfolio-container">
      <b-container>
            <b-row>
               <h1>Portfolio</h1>
            </b-row>
            <div class="portfolio-box-container">

                <div class="portfolio-box">
                    <div class="portfolio-image">
                        <img src="https://skytronixsglobal.com/assets/images/footerlogo.png" />
                    </div>
                    <h5>Skytronixs Global</h5>
                    <p class="portfolio-description">Philippines-based customer service and back-office teams
                            For tech startups looking to grow, outsourcing customer service has never been a better option.</p>
                </div>  

                <div class="portfolio-box">
                    <div class="portfolio-image">
                        <img src="http://www.skytronixscharities.com/assets/images/home/Lower_SClogo.png" />
                    </div>
                    <h5>Skytronixs Charities</h5>
                    <p class="portfolio-description">Skytronixs Charity is a globally recognized non-profit organization committed in restoring hope and courage to the underprivileged by feeding the less fortunate families.</p>
                </div>

                <div class="portfolio-box">
                    <div class="portfolio-image">
                        <img src="https://ussc.com.ph/_nuxt/img/ussclogo-2.cf60118.svg" />
                    </div>
                    <h5>USSC</h5>
                    <p class="portfolio-description">USSC is a homegrown, all-Filipino corporation that aims to serve our countrymen, one person at a time—wherever in the world they may be.</p>
                </div>
            </div>
            <div class="view-more-container">
                <div class="contact-btn">
                    <button class="contact">
                        <span class="circle">
                        <span class="icon arrow"></span>
                        </span>
                        <span class="button-text">View More</span>
                    </button>
                </div>
            </div>
             

        </b-container>  
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