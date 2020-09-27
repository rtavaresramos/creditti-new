<template>
    <div class="footer d-flex flex-col align-center">
        <div class="logo">
            <nuxt-link to="/" class="logo">
                <img 
                src="../assets/img/logo-creditti.png" 
                alt="logo">
            </nuxt-link>
        </div>
        <div class="contact">
            <h3> Creditti, CNPJ: 36.648.875/0001-41</h3>
        </div>
        <div class="copy mt-3" style="text-align: center;"><cite>Developed by <a href="https://github.com/rtavaresramos">Rodrigo Tavares Ramos</a> © 2020-2020</cite></div>
    </div>
</template>

<style lang="css" scoped>
.logo img{
    width: 150px;
}

h3, a{
    color: #fff;
    font-weight: 500;
    text-align: center;
}

.copy {
    color: #fff;
    font-weight: 200;
    text-align: center;
}

.copy a{
    text-decoration: underline;
}

.footer{
    padding: 40px;
    background: #063860;
}
</style>