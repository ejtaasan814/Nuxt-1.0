<template>
    <div>
        <div class="banner">
            <div class="bg-wave">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                    <path fill="#0099ff" fill-opacity="1" d="M0,128L48,112C96,96,192,64,288,48C384,32,480,32,576,53.3C672,75,768,117,864,128C960,139,1056,117,1152,106.7C1248,96,1344,96,1392,96L1440,96L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path>
                </svg>
            </div>
            <div class="banner-text">
                <h1>HI, My name is EJ Get started</h1>
            </div>
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