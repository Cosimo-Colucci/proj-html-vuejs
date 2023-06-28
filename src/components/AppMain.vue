<script>
    import ClientFeedback from './ComponentSons/ClientFeedback.vue';
    import GraphMain from './ComponentSons/GraphMain.vue';
    import ServiseComponent from './ComponentSons/ServiseComponent.vue';
    import Communities from './ComponentSons/Communities.vue';
    import Talk from './ComponentSons/Talk.vue';

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
            Communities,
            Talk,
        }
}
</script>

<template>
    <GraphMain/>
    <ServiseComponent/>
    <Communities/>
    <ClientFeedback/>
    <Talk/>
</template>

<style lang="scss" scoped>
    
</style>