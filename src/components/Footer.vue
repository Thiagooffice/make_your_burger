<template>
    <footer id="footer">
        <p>Make Your Burder &copy; 2023</p>
    </footer>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped>
    #footer{
        height: 100px;
        background: #222;
        border-top: 4px solid #111;
        color: #fcba03;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        bottom: 0;
        position: fixed;
    }
</style>