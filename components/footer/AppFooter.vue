<template>
    <footer>
        <div class="copyrights">
            <div class="row mx-0 align-items-center justify-content-between">
                <div class="col-auto">
                    <img src="https://the7.io/agency/wp-content/uploads/sites/43/2017/11/agency-logo-bottom.png" alt="">
                    © 2020 • Avada Consultant • Powered by WordPress
                </div>
                <div class="col-auto">
                    <span class="mx-3">
                        <span style="color:#d0544e">tel:</span> Call Us (555) 802-1234
                    </span>    
                    <span>
                        <span style="color:#d0544e">mail:</span> 
                        info@yourcompany.com
                    </span>    
                
                </div>
            </div>
        </div>
  </footer>
</template>

<script>


export default {
    name: 'AppFooter',
    components: {},
    data() {
        return {
            
        }
    },
    methods : {
        
    }
}
</script>
<style>
    .copyrights {
        padding: 15px 30px;
        margin-bottom: 0px;
        background-color: rgb(17, 17, 17);
        color: rgb(255, 255, 255);
        font-size: 13px;
        letter-spacing: normal;
        line-height: 23px
    }
    .copyrights p a{
        color: rgb(166, 166, 166);
        font-size: 12px;
        font-weight: 600;
        text-decoration: none;
    }
    
</style>