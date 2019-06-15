<template>
    <div class="header">
        <div class="userInfo">
            <div class="avatar"></div><a href="login.html">Вход</a><a href="registration.html">Регистрация</a>
        </div>
        <div class="welcome" id="welcome">Добро пожаловать, {{user}}!</div><a href="/">
        <div class="chessIcon"></div></a>
    </div>
</template>

<script>
export default {
    name: 'Header',
    props: {
        user: String
    }
}
</script>

<style lang="scss">

</style>
