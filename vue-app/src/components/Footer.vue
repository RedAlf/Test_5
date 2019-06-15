<template>
    <div class="footer">
        <p>Тел.: 8(9xx)-xxx-xx-xx</p>
    </div>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>

<style lang="scss">
    .footer {
        width: 100%;
        height: 100px;
        bottom: 0%;
        background: darken($color: grey, $amount: 30);
        border-top: 2px solid grey;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>
