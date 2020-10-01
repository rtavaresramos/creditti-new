<template>
  <div>
    <div
      v-for="(item, index) in list"
      :key="index"
      class="align-start list d-flex"
    >
      <div class="circle"></div>
      <div class="item">
        <div class="title">
          <h4>{{ item.title }}</h4>
        </div>
        <div class="content">
          <p>{{ item.content }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      list: [
        {
          title: "Zero riscos",
          content:
            "Após assinatura da documentação necessária nossos parceiros começarão a limpar o seu nome e você recebe até R$ 500,00 em 48 horas. Todos os riscos do negócio ficam com a Creditti."
        },
        {
          title: "Totalmente Online",
          content:
            "Todo o serviço e atendimento serão feitos pela internet. Seu problema será resolvido evitando burocracias ao máximo, não se preocupe!"
        },
        {
          title: "Simples e rápido",
          content:
            "Veja seu caso ser resolvido de forma mais eficiente do que em quaisquer métodos tradicionais!"
        },
        {
          title: "Em todo o Brasil",
          content:
            "Temos parceiros por todo o país. Vamos te ajudar, independente de onde você mora!"
        }
      ]
    };
  }
};
</script>

<style lang="css" scoped>
.circle {
  position: relative;
  min-width: 20px;
  height: 20px;
  background: #1572c4;
  border-radius: 50%;
  margin-top: 6px;
  margin-right: 24px;
}

h4 {
  color: #f05000;
  font-size: 1.5rem;
  font-weight: 900;
  width: 90%;
  min-width: 400px;
}

p {
  margin: 20px 0;
  width: 90%;
  font-size: 1rem;
}
.list {
  width: 80%;
}

@media screen and (max-width: 993px) {
  .list {
    width: 80%;
    margin: 0 auto;
  }
}
</style>
