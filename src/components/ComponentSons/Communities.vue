<template>
    <div class="my_container">
        <div class="description-bg">
            <div class="description">
                <span>
                    investment numbers
                </span>
                <h1 class="">
                    making an inpact in our communities
                </h1>
                <button>
                    learn more
                </button>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Communities',

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
    div.description-bg{
        width: 30%;
        background: url(../../../public/img/counters-bg-image.jpg);
        background-repeat: no-repeat;
        padding: 3rem;
    }
    div.description{
        color: white;
        padding: 3rem;
        text-transform: capitalize;
    }
    
    button{
        color: white;
        background-color: #5ADDCD;
    }
</style>