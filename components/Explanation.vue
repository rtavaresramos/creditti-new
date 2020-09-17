<template>
    <div class="explanation">
        <div class="item" v-for="(item,index) in explain" :key="index">
            <div class="headline" :class="{'active': item.isActive}">
                <h2>{{ item.number }}</h2>
                <p @click="seeMore(index)">{{ item.title }}</p>
            </div>
            <div class="content" :class="{'active': item.isActive}" :id="`active-${item.number}`">
                <p>{{ item.description }}
                    <span v-if="item.restDescription"><a href="#"> aqui </a></span>
                    {{ item.restDescription }}
                </p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
         data() {
      return {
          isActive: 1,
        explain: [

          {
            isActive: true,
            number: 1,
            title: 'Você nos conta seu caso',
            description: 'Você nos conta a sua situação',
            restDescription: ', envia os documentos comprovantes e descobrimos se você tem direito a uma indenização.'
        },
          {
            isActive: false,
            number: 2,
            title: 'Limpamos seu nome',
            description: 'Nossa equipe monta uma estratégia de negociação contra a empresa que te negativou para conseguir um acordo e limpar seu nome.'
        },
          {
            isActive: false,
            number: 3,
            title: 'Você é indenizado',
            description: 'Você fica em casa, esperando o seu crédito ser liberado, e ainda pode receber uma indenização de mais de R$ 5.000,00. Só recebemos se você ganhar!'
        },
        ]
      }
    },
    methods: {
        seeMore(index) {
            this.explain.map(item=> item.isActive = false)
            this.explain[index].isActive = true
        }
    },
    }
</script>

<style lang="css" scoped>
h2{
    color: #0072c4;
    font-size: 4rem;
    display: flex;
    align-items: flex-end;
}
a{
    color: #F05000;
    font-weight: 700;
    text-decoration: underline;
}


.headline p{
    font-size: 1.4rem;
    background: #003860;
    color: #fff;
    margin: 8px 12px;
    padding: 12px 20px;
    border-radius: 8px;
    font-weight: 800;
}

.content p{
    font-size: 1.2rem;

}
.content{
    border-left: 6px dotted #0072c4;
    margin: 16px 10px ;
    padding-left: 24px;
    margin-left: 20px;
}
.headline{
    display: flex;
    align-items: center;
    padding: 8px;
    /* margin-left: -16px; */
    background:#E8EAEB ;
    /* margin-top: -8px; */
    overflow-x: visible!important;
}

@media screen and (min-width: 830px) {
h2{

    transform: translate( 25px, -60px );
    color: #fff;
    font-size: 5rem;
    display: flex;
    align-items: flex-end;
}
a{
    color: #F05000;
    font-weight: 700;
    text-decoration: underline;
}

.explanation{
    display: flex;
    width: 70%;
    justify-content: center;
    margin: 20px auto;
    border-radius: 16px;
    background: #0072c4;
    height: 300px;
    padding: 40px 20px;
}
.headline{
    display: flex;
    align-items: center;
    padding: 8px;
    background:transparent ;
    overflow-x: visible!important;
}
.headline.active > p{
    background:#F05000 ;
}
.headline p{
    cursor: pointer;
    font-size: 1.4rem;
    background: #003860;
    color: #fff;
    margin: 8px 12px;
    padding: 12px 20px;
    border-radius: 8px;
    font-weight: 600;
    width: 545px;
}

.content p{
    font-size: 1.2rem;
    font-weight: 500;

}
.content#active-1::before{
    position: absolute;
    z-index: 0;
    content: '';
    height: 30px;
    width: 25px;
    background: #fff;
    transform: rotate(45deg);
    top: -12px;
    margin-left: 45px;
}
.content#active-1 p{
    background: #fff;
    z-index: 1;
}
.content#active-1{
    position: relative;
    z-index: 10;
    width: 545px;
    background: #fff;
    color: #003860;
    margin: 8px 12px;
    padding: 12px 20px;
    border-radius: 8px;
}
.content.active#active-1{
    display: flex !important;
}

.content#active-2::before{
    position: absolute;
    z-index: 0;
    content: '';
    height: 30px;
    width: 25px;
    background: #fff;
    transform: rotate(45deg);
    top: -12px;
    margin-left: 195px;
}
.content#active-2 p{
    background: #fff;
    z-index: 1;
}
.content#active-2{
    position: relative;
    z-index: 10;
    width: 545px;
    background: #fff;
    color: #003860;
    margin: 8px 12px;
    padding: 12px 20px;
    border-radius: 8px;
    margin-left: -90px;
}
.content.active#active-2{
    display: flex !important;
}

.content#active-3::before{
    position: absolute;
    z-index: 0;
    content: '';
    height: 30px;
    width: 25px;
    background: #fff;
    transform: rotate(45deg);
    top: -12px;
    right: 40px;
}
.content#active-3 p{
    background: #fff;
    z-index: 1;
}
.content#active-3{
    position: relative;
    z-index: 10;
    width: 545px;
    background: #fff;
    color: #003860;
    margin: 8px 12px;
    padding: 12px 20px;
    border-radius: 8px;
    margin-left: -270px;
}
.content.active#active-3{
    display: flex !important;
}
.item{
    width: 300px;
}
.content{
    display: none;
    border-left:none;
    margin: 16px 6px ;
    padding-left: 24px;
    margin-left: 20px;
}


  }
</style>