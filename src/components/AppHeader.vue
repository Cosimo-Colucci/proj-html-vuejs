<script>
export default{
    name: "AppHeader",

    data() {
        return {
          
        };
    },

    components: {
    }
}
</script>

<template>
    <div>
        <h1>
            Right People. Right Investments.
        </h1>
    </div>
</template>

<style lang="scss" scoped>
    div{
        display: flex;
        width: 100%;
        border: 2px solid black;

        background: url(../../public/img/home_finance_slider_bg.jpg);

        h1{
            margin: auto;
            color: white;
            padding: 29rem;
        }
    }
</style>
