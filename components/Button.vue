<template>
    <div class="button">
       <a :id="identify" :href="to" target="_blank">
            {{text}}
       </a>
    </div>
</template>

<script>
    export default {
        props: {
            text: {
                type: String,
                default: 'Verifique grátis'
            },
            identify: {
                type: String,
                default: ''
            },
            to: {
                type: String,
                default: 'https://api.whatsapp.com/send?phone=5585998022720&text=Oi%2C%20quero%20iniciar%20meu%20atendimento!'
            },
        },
        
    }
</script>

<style lang="css" scoped>
.button{
    color: #fff;
    font-size: 1.2rem;
    font-weight: 800;
    text-transform: uppercase;
    background: #F05000;
    padding: 10px 20px;
    border-radius: 12px;
}
a{
    color: #fff;
    
}
</style>