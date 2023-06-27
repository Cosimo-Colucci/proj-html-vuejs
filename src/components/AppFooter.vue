<script>
    import LowerFooter from './ComponentSons/LowerFooter.vue';
    import UpperFooter from './ComponentSons/UpperFooter.vue';

    export default{
        name: "AppFooter",

        data() {
            return {
            
            };
        },

        components: {
            LowerFooter,
            UpperFooter,
        }
    }
</script>

<template>
        <UpperFooter/>
        <LowerFooter/>
</template>

<style lang="scss" scoped>
    
</style>