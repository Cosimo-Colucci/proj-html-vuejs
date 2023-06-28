<script>
    import ClientFeedback from './ComponentSons/ClientFeedback.vue';
    import GraphMain from './ComponentSons/GraphMain.vue';
    import ServiseComponent from './ComponentSons/ServiseComponent.vue';

    export default{
        name: "AppMain",

        data() {
            return {
            
            };
        },

        components: {
            ClientFeedback,
            GraphMain,
            ServiseComponent,
        }
}
</script>

<template>
    <GraphMain/>
    <ServiseComponent/>
    <ClientFeedback/>
</template>

<style lang="scss" scoped>
    
</style>