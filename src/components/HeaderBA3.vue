<script setup>
</script>
<template>
    <header>
        <nav class="nav-bar">
            <div class="logo">
                <h1>logo</h1>
            </div>

            <div class="login-button">
                <button>entrar</button>
            </div>
        </nav>
    </header>
</template>
<style scoped>
*{
    padding: 0;
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}
header{
    background-color: rgb(44, 44, 44);
    box-shadow: 0px 3px 10px white;
}
.nav-bar{
    display: flex;
    justify-content: space-between;
    padding: 1.5rem 6rem;
}

.logo{
    display: flex;
    align-items: center;
}

.logo h1{
    color: white;
}
</style>