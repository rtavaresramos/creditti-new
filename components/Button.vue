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
                default: 'https://creditti.com.br/ajuda'
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