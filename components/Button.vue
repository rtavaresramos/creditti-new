<template>
    <div class="button">
       <nuxt-link :to="to">
            {{text}}
       </nuxt-link>
    </div>
</template>

<script>
    export default {
        props: {
            text: {
                type: String,
                required: true
            },
            to: {
                type: String,
                required: true
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