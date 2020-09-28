<template>
    <div class="carousel-wrapper">
        <span id="descomplic-1"></span>
        <span id="descomplic-2"></span>
        <span id="descomplic-3"></span>
        <span id="descomplic-4"></span>

        <div class="carousel-descomplic descomplic-1 d-flex flex-col align-center justify-center">
            <div class="totally">
                <h4>Só Ganhamos se você Ganhar</h4>
            </div>
            <img src="../assets/img/get-money.png"/>
            <p>
              Caso você ganhe a indenização, ficamos com 30% do valor. 
              Caso não ganhe, não recebemos nada. A nossa prioridade 
              sempre vai ser limpar o seu nome!
              </p>
              <div class="circles d-flex justify-center">
                <div class="circle active"></div>
                <div class="circle"></div>
                <div class="circle"></div>
                <div class="circle"></div>
            </div>
            <a class="arrow arrow-prev" href="#descomplic-4"></a>
            <a class="arrow arrow-next" href="#descomplic-2"></a>
        </div>
        
        <div class="carousel-descomplic descomplic-2 d-flex flex-col align-center justify-center">
            <div class="totally">
                <h4>Totalmente Online</h4>
            </div>
            <img src="../assets/img/enter.png"/>
            <p>
            Todo o serviço e atendimento serão feitos pela internet. 
            Se problema será resolvido evitando burocracias ao máximo, 
            não se preocupe!
              </p>
              <div class="circles d-flex justify-center">
                <div class="circle"></div>
                <div class="circle active"></div>
                <div class="circle"></div>
                <div class="circle"></div>
            </div>
           <a class="arrow arrow-prev" href="#descomplic-1"></a>
            <a class="arrow arrow-next" href="#descomplic-3"></a>
        </div>
        
        <div class="carousel-descomplic descomplic-3 d-flex flex-col align-center justify-center">
            <div class="totally">
                <h4>Simples e Rápido</h4>
            </div>
             <img src="../assets/img/target.png"/>
            <p>
              Veja seu caso ser resolvido de forma mais eficiente do que em 
              quaisquer métodos tradicionais!
              </p>
              <div class="circles d-flex justify-center">
                <div class="circle"></div>
                <div class="circle"></div>
                <div class="circle active"></div>
                <div class="circle"></div>
            </div>
            <a class="arrow arrow-prev" href="#descomplic-2"></a>
            <a class="arrow arrow-next" href="#descomplic-4"></a>
        </div>

        <div class="carousel-descomplic descomplic-4 d-flex flex-col align-center justify-center">
            <div class="totally">
                <h4>Em Todo o Brasil</h4>
            </div>
             <img src="../assets/img/address.png"/>
            <p>
              Temos parceiros por todo o país. Vamos te ajudar, independente de onde você mora!
              </p>

              <div class="circles d-flex justify-center">
                <div class="circle"></div>
                <div class="circle"></div>
                <div class="circle"></div>
                <div class="circle active"></div>
            </div>
            <a class="arrow arrow-prev" href="#descomplic-3"></a>
            <a class="arrow arrow-next" href="#descomplic-1"></a>
        </div>
    </div>
</template>

<style lang="css" scoped>
@media screen and (min-width: 830px){
    .carousel-wrapper{
        display: none;
    }
}

.totally{
    position: absolute;
    top: 0;
    background: #F05000;
    color: #fff;
    width: 100%;
    text-align: center;
    border-top-left-radius: 14px;
    border-top-right-radius: 14px;
    padding: 15px 0;
}
.circles{
    position: absolute;
    bottom: 14px;
}

.circle{
    position: relative;
    min-width: 10px;
    height: 10px;
    background: #F05000;
    border-radius: 50%;
    margin: 0 4px;
  }

.circle.active{
    background: #fff;
  }
img{
  width: 100px;
  height: 100px;
  margin: 10px auto;
}

p{
    font-size: .9rem;
  font-weight: 500;
  text-align: center;
  margin: 10px;
}

h4{
  font-size: 1.1rem;
}
.place{
  font-size: 1.2rem;
  color: #F05000;
  text-align: center;
}
.carousel-wrapper{
    position: relative;
    min-height: 400px;
    padding: 10px 0;
    height: auto;
    position: relative;
    max-width: 500px;
    width: 75%;
    margin: 0 auto;
}
.carousel-descomplic{
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
[id^="descomplic"] {
    display: none;
  }

.descomplic-1 {
    padding: 10px 0;
    z-index: 2;
    opacity: 1;
    background: fff;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
  }
 
.descomplic-2{
    padding: 10px 0;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
}
  
.descomplic-3{
    padding: 10px 0;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
}

.descomplic-4{
    padding: 10px 0;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
}
 

*:target ~ .descomplic-1 {
    opacity: 0;
  }

#descomplic-1:target ~ .descomplic-1 {
    opacity: 1;
  }

#descomplic-2:target ~ .descomplic-2
, #descomplic-3:target ~ .descomplic-3
, #descomplic-4:target ~ .descomplic-4 {
    z-index: 3;
    opacity: 1;
  }

</style>