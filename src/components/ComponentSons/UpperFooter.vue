<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-3">
                <img src="../../../public/img/logo-big/finance/finance_logo_footer.png" alt="">
            </div>
            <div class="col-3">
                <ul>
                    <li class="text-uppercase mb-3">
                        recent posts
                    </li>
                    <li class="mb-3">
                        <span>&#62; </span>
                        <span>When is it ihe right time to sell your company?</span>
                    </li>
                    <li class="mb-3">
                        <span>&#62; </span>
                        <span>Personal debt or company debt we explore your options</span>
                    </li>
                    <li class="mb-3">
                        <span>&#62; </span>
                        <span>An interview with a so-called business angel</span>
                    </li>
                </ul>
            </div>
            <div class="col-3">
                <ul>
                    <li class="text-uppercase mb-3">
                        services
                    </li>
                    <li class="text-uppercase mb-3">
                        <span>&#62; </span>
                        <span>small business loan services</span>
                    </li>
                    <li class="text-uppercase mb-3">
                        <span>&#62; </span>
                        <span>credit rating advice services</span>
                    </li>
                    <li class="text-uppercase mb-3">
                        <span>&#62; </span>
                        <span>crowd funding services</span>
                    </li>
                </ul>
            </div>
            <div class="col-3">
                <ul>
                    <li class="text-uppercase mb-3">
                        latest
                    </li>
                    <li class="mb-3">
                        <i class="fa-brands fa-twitter"></i>
                    </li>
                </ul>
            </div>
        </div>

    </div>
        
    
</template>

<script>
export default {
    name: 'UpperFooter',

    data() {
        return {
            
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style lang="scss" scoped>
    div.container-fluid{
        background-color: #2d2d2d;
        padding: 2rem;
    }

    ul{
        list-style-type: none;

        :first-line{
        color: white;
        }
    }

    span{
        color: #ebebeb;
    }
</style>