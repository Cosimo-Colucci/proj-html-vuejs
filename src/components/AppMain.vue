<script>
    import ClientFeedback from './ComponentSons/ClientFeedback.vue';
    import GraphMain from './ComponentSons/GraphMain.vue';

    export default{
        name: "AppMain",

        data() {
            return {
            
            };
        },

        components: {
            ClientFeedback,
            GraphMain,
        }
}
</script>

<template>
    <GraphMain/>
    <ClientFeedback/>
</template>

<style lang="scss" scoped>
    
</style>