<template>
    <div class="explanation">
        <div class="item" v-for="(item,index) in explain" :key="index">
            <div class="headline">
                <h2>{{ item.number }}</h2>
                <p>{{ item.title }}</p>
            </div>
            <div class="content">
                <p>{{ item.description }}</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
         data() {
      return {
        explain: [
          {
          number: 1,
          title: 'Você nos conta seu caso',
          description: 'Você nos conta a sua situação aqui, envia os documentos comprovantes e descobrimos se você tem direito a uma indenização.'
        },
          {
          number: 2,
          title: 'Limpamos seu nome',
          description: 'Nossa equipe monta uma estratégia de negociação contra a empresa que te negativou para conseguir um acordo e limpar seu nome.'
        },
          {
          number: 3,
          title: 'Você é indenizado',
          description: 'Você fica em casa, esperando o seu crédito ser liberado, e ainda pode receber uma indenização de mais de R$ 5.000,00. Só recebemos se você ganhar!'
        },
        ]
      }
    },
    }
</script>

<style lang="css" scoped>
h2{
    color: #0072c4;
    font-size: 2.5rem;
    margin-left: -14px;
    margin-top: -22px;
    background:#E8EAEB ;
    height: 45px;
    display: flex;
    align-items: flex-end;
}
.explanation{
    padding: 20px 0;
}
.item{
    border-left: 6px dotted #0072c4;
    margin: 30px 20px;
}
.headline p{
    background: #003860;
    color: #fff;
    margin:  12px;
    padding: 10px 20px;
    border-radius: 8px;
    margin-top: -8px;
    font-weight: 800;
}
.content{
    margin: 0 0 0 24px;
}
.headline{
    display: flex;
    align-items: center;
    margin-top: -10px;
}

@media screen and (min-width: 830px) {

  }
</style>