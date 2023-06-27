<template>
    <div class="feedback_title">
        <h1>
            Client Feedback
        </h1>
        <span></span>
    </div>
    <div class="feedback_brands row">
        <div class="article text-center col-3">

            <div class="img-text col-12 p-3">
                <img src="../../../public/img/logo-small/client-logo-4-200x87.png" alt="">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. A, nisi? Et quibusdam delectus omnis atque a quos possimus molestiae facilis id consequatur doloremque aspernatur iusto, dignissimos, sint illo neque maxime.
                </p>
            </div>
            <div class="brand_info col-12 p-3">
                <p class="m-0">
                    Andre Mendoza
                </p>
                <sub>
                    creative market
                </sub>
            </div>

        </div>
        <div class="article text-center col-3">

            <div class="img-text col-12 p-3">
                <img src="../../../public/img/logo-small/client-logo-1-1-200x87.png" alt="">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. A, nisi? Et quibusdam delectus omnis atque a quos possimus molestiae facilis id consequatur doloremque aspernatur iusto, dignissimos, sint illo neque maxime.
                </p>
            </div>
            <div class="brand_info col-12 p-3">
                <p class="m-0">
                    Andre Mendoza
                </p>
                <sub>
                    creative market
                </sub>
            </div>

        </div>
        <div class="article text-center col-3">

            <div class="img-text col-12 p-3">
                <img src="../../../public/img/logo-small/client-logo-7-200x87.png" alt="">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. A, nisi? Et quibusdam delectus omnis atque a quos possimus molestiae facilis id consequatur doloremque aspernatur iusto, dignissimos, sint illo neque maxime.
                </p>
            </div>
            <div class="brand_info col-12 p-3">
                <p class="m-0">
                    Andre Mendoza
                </p>
                <sub>
                    creative market
                </sub>
            </div>

        </div>
        <div class="article text-center col-3">

            <div class="img-text col-12 p-3">
                <img src="../../../public/img/logo-small/client-logo-2-200x87.png" alt="">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. A, nisi? Et quibusdam delectus omnis atque a quos possimus molestiae facilis id consequatur doloremque aspernatur iusto, dignissimos, sint illo neque maxime.
                </p>
            </div>
            <div class="brand_info col-12 p-3">
                <p class="m-0">
                    Andre Mendoza
                </p>
                <sub>
                    creative market
                </sub>
            </div>

        </div>
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
    div.feedback_brands{

        div.article{
            border: 1px solid black;
            padding: 0;

            div.brand_info{
                border-top: 1px solid black;
            }
        }
    }
</style>