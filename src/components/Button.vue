<template>
    <div class="btn">
        <h1 class="btnText"> {{ btnType }} </h1>
    </div>
</template>

<script>
export default {
    name: 'Button',
    props: {
        btnType: String
    }
}
</script>

<style scoped>
.btn{
    border: 1pt solid black;
    display: flex;
    height: 50px;
    width: 150px;
    font-size: 8pt;
    justify-content: center;
    padding: 0.7%;
}
</style>