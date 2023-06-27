<template>
    <div class="lower_footer">
        <div class="copyright_info">
            copyright_info
        </div>

        <div class="social_info">
            <ul>
                <li>
                    <a href=""><i class="fa-brands fa-facebook-f"></i></a>
                </li>
                <li>
                    <a href=""><i class="fa-brands fa-twitter"></i></a>
                </li>
                <li>
                    <a href=""><i class="fa-brands fa-youtube"></i></a>
                </li>
                <li>
                    <a href=""><i class="fa-brands fa-instagram"></i></a>
                </li>
            </ul>
        </div>
    </div>
    
</template>

<script>
export default {
    name: 'LowerFooter',

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
    div.lower_footer{
        background-color: black;
        color: #ebebeb;
        display: flex;
        justify-content: space-between;
        padding: 2rem;

        div.social_info{
            ul{
                list-style-type: none;
                display: flex;

                li{
                    margin: 0 .5rem;
                    

                    a{
                        color: white;
                        padding: .5rem;
                        border-radius: 50%;
                        background-color: #5addcd;
                    }
                }
                
            }
        }
    }
</style>