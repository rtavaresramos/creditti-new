<template>
  <div class="card-place d-flex justify-center align-center flex-wrap">
    <div v-for="(item, index) in items" :key="index" class="card">
      <h2>{{ item.title }}</h2>
      <p>{{ item.content }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: "Vítima de fraude",
          content:
            "Usaram seus dados sem a sua autorização! Seu nome está sujo por conta de um serviço que você não contratou."
        },
        {
          title: "Dívida Prescrita",
          content:
            "Você está com o nome sujo por uma só dívida há mais de cinco anos. Depois disso, as dívidas não podem mais aparecer nos serviços de proteção ao crédito."
        },
        {
          title: "Cadastro indevido",
          content:
            "Você pagou a sua dívida, mesmo assim continuou recebendo cobranças e ainda descobriu que seu nome está negativado."
        },
        {
          title: "Manutenção indevida",
          content:
            "Você fez um acordo para limpar seu nome e já pagou a primeira parcela. Mesmo depois de cinco dias, continua negativado(a)."
        }
      ]
    };
  }
};
</script>

<style lang="css" scoped>
.card {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  max-width: 400px;
  width: 80%;
  min-height: 120px;
  background: #fff;
  margin: 20px;
  padding: 22px 12px;
  border-radius: 14px;
  box-shadow: 0 0 10px -5px #000;
}

h2 {
  color: #f05000;
  font-size: 1.5rem;
  font-weight: 900;
  position: absolute;
  top: -32px;
}

p {
  font-size: 1rem;
}

.card-place {
  margin-top: 70px;
}

@media screen and (min-width: 835px) {
  .card {
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    max-width: 400px;
    width: 80%;
    height: 120px;
    background: #fff;
    margin: 20px;
    padding: 22px 12px;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
  }

  h2 {
    color: #f05000;
    font-size: 2rem;
    font-weight: 900;
    position: absolute;
    top: -18px;
  }

  p {
    font-size: 1rem;
  }

  .card-place {
    margin-top: 70px;
  }
}
</style>
