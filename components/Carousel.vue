<template>
    <div class="carousel-wrapper">
        <span id="item-1"></span>
        <span id="item-2"></span>
        <span id="item-3"></span>
        <div class="carousel-item item-1 d-flex flex-col align-center justify-center">
            <img src="../assets/img/customer-1.png"/>
            <p>
              "Desde 2015 eu estava negativado por uma 
                dívida que não era minha. Entrei em contato com a 
                Creditti, contei minha história e rapidamente planejaram 
                uma estratégia de defesa. Em menos de um mês, tive meu nome 
                retirado do Serasa, voltei a ter dignidade e crédito na praça."
              </p>

              <h4>Anderson Freitas</h4>
              <h4 class="place">Recife, Pernambuco</h4>
            <a class="arrow arrow-prev" href="#item-3"></a>
            <a class="arrow arrow-next" href="#item-2"></a>
        </div>
        
        <div class="carousel-item item-2 d-flex flex-col align-center justify-center">
            <img src="../assets/img/customer-3.png"/>
            <p>
              "Até aqui, estou muito satisfeito com a Creditti. 
              Resolveram um problema que já vinha me incomodando 
              há 2 anos, além de sempre me atualizarem do processo 
              e me tratarem sempre com muita educação e carisma."
              </p>

              <h4>Renato Alves</h4>
              <h4 class="place">Barueri, São Paulo</h4>
           <a class="arrow arrow-prev" href="#item-1"></a>
            <a class="arrow arrow-next" href="#item-3"></a>
        </div>
        
        <div class="carousel-item item-3 d-flex flex-col align-center justify-center">
             <img src="../assets/img/customer-2.png"/>
            <p>
              "Gostaria de dizer muito obrigada a todos vocês da Creditti,
               pois sou sempre muito bem atendida. Fico feliz em ser cliente 
               de uma empresa séria, parabéns!"
              </p>

              <h4>Cristiane Calazans</h4>
              <h4 class="place">São Gonçalo, Rio de Janeiro</h4>
              
            <a class="arrow arrow-prev" href="#item-2"></a>
            <a class="arrow arrow-next" href="#item-1"></a>
        </div>
    </div>
</template>

<style lang="css" scoped>

img{
  width: 100px;
  height: 100px;
  margin: 10px auto;
}
p{
  font-weight: 500;
  text-align: center;
  margin: 10px;
}
.place{
  color: #F05000;
}
.carousel-wrapper{
  min-height: 400px;
  height: auto;
  position: relative;
  max-width: 500px;
  width: 75%;
  margin: 0 auto;
}
.carousel-item{
  position:absolute;
  top:0;
  bottom:0;
  left:0;
  right:0;
  padding:25px 50px;
  opacity:0;
  transition: all 0.5s ease-in-out;
}
.arrow{
  border:solid #F05000;
    border-width: 0 14px 14px 0;
    border-radius: 4px;
    display: inline-block;
    padding: 12px;
}

.arrow-prev{
  left:-30px;
  position:absolute;
  top:50%;
  transform:translateY(-50%) rotate(135deg);
}
 
.arrow-next{
    right:-30px;
  position:absolute;
  top:50%;
  transform:translateY(-50%) rotate(-45deg);
  }

.light{
  color:white;
}

@media (max-width: 480px) {
      .arrow, .light .arrow {
        background-size: 10px;
        background-position: 10px 50%;
      }
    }


/*Select every element*/
[id^="item"] {
    display: none;
  }

.item-1 {
    padding: 10px 0;
    z-index: 2;
    opacity: 1;
    background: fff;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
  }
 
.item-2{
    padding: 10px 0;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
}
  
.item-3{
    padding: 10px 0;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
}
 

*:target ~ .item-1 {
    opacity: 0;
  }

#item-1:target ~ .item-1 {
    opacity: 1;
  }

#item-2:target ~ .item-2, #item-3:target ~ .item-3 {
    z-index: 3;
    opacity: 1;
  }
  @media screen and (min-width: 830px) {
 .item-1::before{
  position: absolute;
  content: '';
  width: 20px;
  height: 20px;
  background: #e8eaeb;
  top: 30px;
  left: -10px;
  transform: rotate(45deg);
  opacity: 1;
  box-shadow: -4px 4px 10px -7px #000;
}

.item-2::before{
  position: absolute;
  content: '';
  width: 20px;
  height: 20px;
  background: #e8eaeb;
  top: 30px;
  left: -10px;
  transform: rotate(45deg);
  opacity: 1;
  box-shadow: -4px 4px 10px -7px #000;
}

.item-3::before{
  position: absolute;
  content: '';
  width: 20px;
  height: 20px;
  background: #e8eaeb;
  top: 30px;
  left: -10px;
  transform: rotate(45deg);
  opacity: 1;
  box-shadow: -4px 4px 10px -7px #000;
}
  }
</style>