<template>
    <div class="body">
        <div class="container">
            <div class="title text-center">
                <h1>
                    Specialty Service
                </h1>
                <span>

                </span>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Vitae dolorem corrupti voluptas quia. Minus ipsum ex porro architecto iste magnam mollitia cupiditate voluptates reprehenderit dolor fugiat libero qui, corrupti nulla.
                </p>
            </div>
            <div class="row level_services">
                <div class="card_servive text-center">                    
                    <i class="fa-solid fa-globe fa-2xl p-4" style="color: #213d65;"></i>
                    <h2>
                        Small Business Loans
                    </h2>
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus illum deserunt nulla tempora sed error dolore dolorem.
                    </p>
                    <div class="learn text-center">
                        <span>
                            Learn More
                        </span>
                    </div>
                </div>
                
                <div class="card_servive text-center">
                    <i class="fa-regular fa-gem fa-2xl p-4" style="color: #213d65;"></i>
                    <h2>
                        Creadit Rating Advice
                    </h2>
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus illum deserunt nulla tempora sed error dolore dolorem.
                    </p>
                    <div class="learn text-center">
                        <span>
                            Learn More
                        </span>
                    </div>
                </div>

                <div class="card_servive text-center">
                    <i class="fa-solid fa-chart-line fa-2xl p-4" style="color: #213d65;"></i>
                    <h2>
                        Fast Crowd Funding
                    </h2>
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus illum deserunt nulla tempora sed error dolore dolorem.
                    </p>
                    <div class="learn text-center">
                        <span>
                            Learn More
                        </span>
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
    export default {
        name: 'ServiseComponent',

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
        padding: 8rem;
        background-color: #ebebeb;
    }

    div.icon{
        width: 50px;
        height: 50px;
    }
    div.row{
        display: flex;
        justify-content: space-between;
    }
    div.card_servive{
        padding: 0;
        width: calc((100% / 3) - 15px);
        background-color: white;
    }

    div.learn{
        color: white;
        background-color: #5addcd;
    }
</style>