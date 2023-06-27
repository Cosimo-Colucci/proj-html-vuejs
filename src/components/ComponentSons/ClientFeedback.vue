<template>
    <div class="feedback_title">
        <h1>
            Client Feedback
        </h1>
        <span></span>
    </div>
</template>

<script>
export default {
    name: 'ClientFeedback',

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
    div.feedback_title{
        background-color: #ebebeb;
        display: flex;
        flex-direction: column;
        padding: 8rem;

        h1{
            margin: auto;
        }

        span{
            height: 2px;
            background-color: black;
            width: 70px;
            margin: auto;
        }
    }
</style>