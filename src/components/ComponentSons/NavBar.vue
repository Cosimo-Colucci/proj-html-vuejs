<template>
    <div class="navbar">
        <div class="navbar_logo">
            <img src="../../../public/img/logo-big/finance/finance_logo_1x.png" alt="">
        </div>
        <div class="navbar_list">
            <ul>
                <li>home</li>
                <li>about</li>
                <li>service</li>
                <li>packages</li>
                <li>insight</li>
                <li>
                    <button>
                        contact
                    </button>
                </li>
                <li>
                    <i class="fa-solid fa-plus"></i>
                </li>

            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'NavBar',

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
    div.navbar{
        display: flex;
        justify-content: space-between;
        padding: 1.5rem;

        div.navbar_list>ul{
            display: flex;
            list-style-type: none;
            padding: 1rem;

            li, button{
                margin: 0 1rem;
                text-transform: uppercase;
            }
        }
    }
</style>