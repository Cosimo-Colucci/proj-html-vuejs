<template>
    <div class="body">
        <div class="container my_container text-center">
            <h1>
                Ready to Talk?
            </h1>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores, quod ipsum? Aut repellat fugiat saepe suscipit, architecto dolorem adipisci cumque voluptatum laborum, debitis commodi eligendi tempore consequuntur animi quaerat doloribus?
            </p>
            <button>
                let's talk
            </button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Talk',

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
    div.body{
        width: 100%;
        background: url(../../../public/img/ready_to_talk_cta_bg.jpg);
        object-fit: fill;
    }

    div.my_container{
        color: white;
        padding: 5rem;
    }

    button{
        color: white;
        background-color: #5ADDCD;
    }
</style>