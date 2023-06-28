<script>
    import NavBar from './ComponentSons/NavBar.vue';
    import BrandSlider from './ComponentSons/BrandSlider.vue';

    export default{
        name: "AppHeader",

        data() {
            return {
            
            };
        },

        components: {
            NavBar,
            BrandSlider,
        }
    }
</script>

<template>
    <NavBar/>
    <div class="bg">
        <h1>
            Right People. Right Investments.
        </h1>
    </div>
    <BrandSlider/>
</template>

<style lang="scss" scoped>
    div.bg{
        display: flex;

        background: url(../../public/img/home_finance_slider_bg.jpg);
        background-repeat: no-repeat;

        h1{
            margin: auto;
            color: white;
            padding: 29rem;
        }
    }
</style>
