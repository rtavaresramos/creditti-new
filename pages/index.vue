<template>
 <div class="home-page">
    <div class="first-section">
    <div class="header">
      <h1>Nome sujo</h1>
      <h4>por uma dívida que <strong> não contraiu </strong> ou <strong>já pagou</strong>?</h4>
      <img class="mobile-banner" src="../assets/img/banner-header.png" alt="Mobile banner" >
      <p>Conte sua situação e em <strong>3 minutos</strong> nós fazemos seu diagnóstico gratuito. Começamos a 
        limpar seu nome e a buscar sua indenização <strong>ainda hoje, sem cobrar nada!</strong>
      </p>
      <Button class="button" :text="'Comece agora'" />
    </div>
    <div class="aside">
      <img class="aside-banner" src="../assets/img/aside-banner.png" alt="Desktop banner" >
      <h4>O que falam sobre nós na mídia?</h4>
      <div class="brand-banners">
        <a href="https://www.idinheiro.com.br/cobranca-indevida/" target="_blank">
          <svg class="brand-banner" id="Camada_7" data-name="Camada 7" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 886.45 250"><defs><style>.cls-1{fill:#3350b8}.cls-4{fill:#fff}</style></defs><path class="cls-1" d="M156.49 0H31.25A31.34 31.34 0 000 31.25v76h156.49z"/><path d="M218.75 0h-62.26v135.35l28.3-28.1H250v-76A31.34 31.34 0 00218.75 0z" fill="#ffc000"/><path d="M250 107.25h-65.21l-28.3 28.1v-28.1H0v111.5A31.34 31.34 0 0031.25 250h187.5A31.34 31.34 0 00250 218.75v-111.5z" fill="#009c49"/><path class="cls-4" d="M61.31 53.62h11.27v33.82H61.31zm22.54-23.23h11.27v57.05H83.85zM38.76 41.66h11.27v45.78H38.76zm67.63-21.85h11.27v67.63h-11.27zm22.91 154.96h-8.62a8.36 8.36 0 110-16.71h25.4v-11.13h-15.47v-9.85h-11.22V147a19.5 19.5 0 001.32 39h8.61a8.35 8.35 0 110 16.7h-25.35v11.15h15.42v9.85h11.22v-9.9a19.5 19.5 0 00-1.31-39z"/><path class="cls-4" transform="rotate(-90 203.245 43.545)" d="M197.61 19.34h11.27v48.42h-11.27z"/><path class="cls-4" transform="rotate(-90 203.245 66.095)" d="M197.61 41.88h11.27V90.3h-11.27z"/><path class="cls-1" d="M429.54 62.58v125.83h-20.76v-96l-42.07 58.11-40.18-57.76v95.65h-20.19V62.58H328l39.62 58.48 40.56-58.48zm35.37 115.83q-11.43-12.82-11.42-37.35 0-49.62 45.28-49.62 22.83 0 34.33 12.73t11.51 36.89q0 24.15-11.88 37.16t-33.77 13q-22.63.02-34.05-12.81zm59.89-37.35q0-16.6-6.22-24.81T498.77 108q-13.77 0-19.72 8.4t-5.94 24.62q0 16.22 6.13 24.8t19.53 8.59q26.04.04 26.03-33.35zm118.66-36.79q10.95 12.65 10.95 35.84 0 27.93-13.12 39.53T608 191.24q-40.56 0-40.56-21.51V55.78h19.62v41.7a59.23 59.23 0 0112.35-4.25 53.8 53.8 0 0112-1.6q21.12 0 32.05 12.64zm-15.37 60.93q6.12-8.87 6.13-24.33 0-15.85-6.51-24.15t-19.34-8.3a46.28 46.28 0 00-11 1.41 38.77 38.77 0 00-10.28 4.06v50.94q0 9.24 19.43 9.24 15.48 0 21.57-8.87zM678 94.27h19.8l.18 94.14H678zm48.47 94.14V57.86h19.62v130.55zm47.53 0V57.86h19.62v130.55zm58.59.94a88.74 88.74 0 01-14.81-5.66V165a84 84 0 0015.47 7.83 45.36 45.36 0 0015.66 2.55q8.1 0 12.73-3.3a10.11 10.11 0 004.62-8.58c0-3.4-1.26-5.91-3.77-7.55a59.29 59.29 0 00-11.7-5.28l-4.34-1.51q-13.2-3.21-21-9.25t-7.83-18.86q0-10 5.28-16.6a30.41 30.41 0 0113.3-9.62 47.59 47.59 0 0116.89-3A54.57 54.57 0 01868.34 94a90.07 90.07 0 0113.58 5.75v17a152.81 152.81 0 00-14.81-7 33.92 33.92 0 00-12-1.89q-7.74 0-12.45 2.83a8.83 8.83 0 00-4.72 7.93q0 6 4.72 8.77t14.71 5.56a116.77 116.77 0 0115 5.1 25.12 25.12 0 019.81 8q4.24 5.58 4.25 15.19-.19 15.09-11 22.55t-26.5 7.45a62.13 62.13 0 01-16.34-1.89z"/><rect class="cls-1" x="677.42" y="57.84" width="21.13" height="21.13" rx="10.56"/></svg>
        </a>
        <a target="_blank" href="https://ootimista.com.br/jornal-impresso/startup-cearense-atua-no-auxilio-a-consumidores-negativados-indevidamente/">
          <img class="brand-banner" src="../assets/img/o-otimista.png" alt="Marca O Otimista" >
        </a>
      </div>
    </div>
  </div>
  <div id="how-it-works-mobile" class="how-it-works-mobile">
      <h3>Como funciona?</h3>
  </div>
  <div id="how-it-works" class="headlines">
      <h3>Como funciona?</h3>
      <h4 class="slogan">Precisa ser simples.</h4>
      <h4 class="slogan">Precisa ser Creditti!</h4>
  </div>
  <div>
   <explanation />
  </div>
  <div class="wpt d-flex align-start flex-wrap">
    <div class="headlines-mobile d-flex align-center justify-between">
      <div class="circle">
      </div>
     <div class="content">
        <h3>O que nossos</h3>
      <h4 class="slogan">clientes dizem?</h4>
     </div>
      
    </div>
    <div class="headlines ">
      <h3>O que nossos</h3>
      <h4 class="slogan">clientes dizem?</h4>
    </div>
    <carousel />
  </div>
  <div class="mobile-brand">
    <h4>O que falam sobre nós na mídia?</h4>

    <div class="brand-banners">
          <a class="text-center" href="https://www.idinheiro.com.br/cobranca-indevida/" target="_blank">
          <svg class="brand-banner" id="Camada_7" data-name="Camada 7" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 886.45 250"><defs><style>.cls-1{fill:#3350b8}.cls-4{fill:#fff}</style></defs><path class="cls-1" d="M156.49 0H31.25A31.34 31.34 0 000 31.25v76h156.49z"/><path d="M218.75 0h-62.26v135.35l28.3-28.1H250v-76A31.34 31.34 0 00218.75 0z" fill="#ffc000"/><path d="M250 107.25h-65.21l-28.3 28.1v-28.1H0v111.5A31.34 31.34 0 0031.25 250h187.5A31.34 31.34 0 00250 218.75v-111.5z" fill="#009c49"/><path class="cls-4" d="M61.31 53.62h11.27v33.82H61.31zm22.54-23.23h11.27v57.05H83.85zM38.76 41.66h11.27v45.78H38.76zm67.63-21.85h11.27v67.63h-11.27zm22.91 154.96h-8.62a8.36 8.36 0 110-16.71h25.4v-11.13h-15.47v-9.85h-11.22V147a19.5 19.5 0 001.32 39h8.61a8.35 8.35 0 110 16.7h-25.35v11.15h15.42v9.85h11.22v-9.9a19.5 19.5 0 00-1.31-39z"/><path class="cls-4" transform="rotate(-90 203.245 43.545)" d="M197.61 19.34h11.27v48.42h-11.27z"/><path class="cls-4" transform="rotate(-90 203.245 66.095)" d="M197.61 41.88h11.27V90.3h-11.27z"/><path class="cls-1" d="M429.54 62.58v125.83h-20.76v-96l-42.07 58.11-40.18-57.76v95.65h-20.19V62.58H328l39.62 58.48 40.56-58.48zm35.37 115.83q-11.43-12.82-11.42-37.35 0-49.62 45.28-49.62 22.83 0 34.33 12.73t11.51 36.89q0 24.15-11.88 37.16t-33.77 13q-22.63.02-34.05-12.81zm59.89-37.35q0-16.6-6.22-24.81T498.77 108q-13.77 0-19.72 8.4t-5.94 24.62q0 16.22 6.13 24.8t19.53 8.59q26.04.04 26.03-33.35zm118.66-36.79q10.95 12.65 10.95 35.84 0 27.93-13.12 39.53T608 191.24q-40.56 0-40.56-21.51V55.78h19.62v41.7a59.23 59.23 0 0112.35-4.25 53.8 53.8 0 0112-1.6q21.12 0 32.05 12.64zm-15.37 60.93q6.12-8.87 6.13-24.33 0-15.85-6.51-24.15t-19.34-8.3a46.28 46.28 0 00-11 1.41 38.77 38.77 0 00-10.28 4.06v50.94q0 9.24 19.43 9.24 15.48 0 21.57-8.87zM678 94.27h19.8l.18 94.14H678zm48.47 94.14V57.86h19.62v130.55zm47.53 0V57.86h19.62v130.55zm58.59.94a88.74 88.74 0 01-14.81-5.66V165a84 84 0 0015.47 7.83 45.36 45.36 0 0015.66 2.55q8.1 0 12.73-3.3a10.11 10.11 0 004.62-8.58c0-3.4-1.26-5.91-3.77-7.55a59.29 59.29 0 00-11.7-5.28l-4.34-1.51q-13.2-3.21-21-9.25t-7.83-18.86q0-10 5.28-16.6a30.41 30.41 0 0113.3-9.62 47.59 47.59 0 0116.89-3A54.57 54.57 0 01868.34 94a90.07 90.07 0 0113.58 5.75v17a152.81 152.81 0 00-14.81-7 33.92 33.92 0 00-12-1.89q-7.74 0-12.45 2.83a8.83 8.83 0 00-4.72 7.93q0 6 4.72 8.77t14.71 5.56a116.77 116.77 0 0115 5.1 25.12 25.12 0 019.81 8q4.24 5.58 4.25 15.19-.19 15.09-11 22.55t-26.5 7.45a62.13 62.13 0 01-16.34-1.89z"/><rect class="cls-1" x="677.42" y="57.84" width="21.13" height="21.13" rx="10.56"/></svg>
        </a>
    </div>
    <div class="brand-banners">
       <a class="text-center" target="_blank" href="https://ootimista.com.br/jornal-impresso/startup-cearense-atua-no-auxilio-a-consumidores-negativados-indevidamente/">
          <img class="brand-banner" src="../assets/img/o-otimista.png" alt="Marca O Otimista" >
        </a>
    </div>
  </div>
  <div class="tell-case d-flex justify-around align-center">
    <div class="title">
      <h2>Quer começar a limpar o seu nome?</h2>
    </div>
      <Button class="button" :text="'Conte seu caso'" />
  </div>
  <div id="rights" class="rights">
    <div class="headlines">
      <h3>Quando uma </h3>
      <h4 class="slogan">negativação é indevida?</h4>
    </div>
    <div class="content">
      <p>
        Quando você é inscrito de forma indevida no Serasa, SPC ou outros cadastros 
        de devedores, o dano moral sofrido é presumido, ou seja, <strong>você não precisa 
        comprovar que foi prejudicado</strong>. De acordo com a Justiça Brasileira, o simples
        fato de estar com o nome sujo indevidamente, significa que você deve ter seu
        nome limpo imediatamente e ser indenizado. <strong><br>A Creditti faz tudo isso 
        por você!</strong>
      </p>
    </div>
    <Cards />
    <div class="descomplicando d-flex justify-between flex-wrap">
      <img src="../assets/img/home-office.png" alt="">
      <div class="list">
        <div class="headlines">
          <h3>Como </h3>
          <h4 class="slogan">descomplicamos<br> para voce?</h4>
        </div>
       <list />
      </div>
     <div class="where">
       <h4>Mas de onde <br> te atendemos?</h4>
        <img class="from-to" src="../assets/img/from-to.png" alt="">
     </div>
    </div>
  </div>
  <div id="rights-mobile" class="rights-mobile">
    <div class="headlines-mobile">
      <h3>Quando uma </h3>
      <h4 class="slogan">negativação é indevida?</h4>
    </div>
    <Cards />
    <div class="content">
      <p>
        Quando você é inscrito de forma indevida no Serasa, SPC ou outros cadastros 
        de devedores, o dano moral sofrido é presumido, ou seja, <strong>você não precisa 
        comprovar que foi prejudicado</strong>.
        <br>
        <br>
         De acordo com a Justiça Brasileira, o simples
        fato de estar com o nome sujo indevidamente, significa que você deve ter seu
        nome limpo imediatamente e ser indenizado. <strong>A Creditti faz tudo isso 
        por você!</strong>
      </p>
    </div>
  </div>
    <div class="tell-case-mobile d-flex flex-col text-center justify-around align-center">
    <div class="title">
      <h2>Quer começar a limpar o seu nome?</h2>
    </div>
      <Button class="button" :text="'Comece agora'" />
  </div>

  <div class="where-we-are d-flex justify-center text-end">
    <div class="explain">
      <div class="headline-hidden d-flex align-center">
        <i class="fas fa-map-marker-alt fa-2x"></i>
        <h4>E de onde<br> <strong>te atendemos?</strong></h4>
      </div>
      <p>
        Estamos funcionando no <strong>FB Ideias</strong>, o<br> Centro de Empreendedorismo 
        e <br>Inovação do Grupo Farias Brito,<br> no <strong>Shopping Iguatemi</strong>.
      </p>

      <div class="images-mobile">
        <WhereCarousel />
      </div>
    </div>
    <div class="images d-flex flex-col mx-5">
        <img src="../assets/img/fb-ideias.png" alt="">
        <div class="contact d-flex my-3 align-center justify-end">
          <div class="social-media d-flex">
           <a href="#"> <i class="fab fa-instagram fa-3x"></i></a>
            <span class="mx-2"></span>
            <a href="#"><i class="fab fa-facebook-f  fa-3x"></i></a>
            <span class="mx-2"></span>
          </div>

          <div class="mail d-flex flex-col text-start">
            <a class="my-2" href="mailto:contato@creditti.com.br">contato@creditti.com.br</a>
            <a href="tel:(85) 9.9802-2720">(85) 9.9802-2720</a>
          </div>
        </div>
    </div>
  </div>
  <Footer />
 </div>
</template>


<style lang="css" scoped>
i{
  color: #F05000;
}

.images{
  display: none;
}

.contact{
  width: 90%;
}

.contact a{
 color: #0072c4;
 font-weight: 600;
}

.button{
  font-size: 1.5rem!important;
  padding: 16px 40px!important;
}

.home-page{
  overflow-x: hidden!important;
}

.first-section{
  display: flex;
  min-height: 100%;
  min-width: 100%;
  background: #B3DDF4;
  padding: 30px 6px 36px;
}

.header{
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: unset;
  }
  
  .header h1{
    font-size: 4rem;
    color: #063860;
    font-weight: 900;
    text-shadow: 7px 3px 0px #508DB7;
    margin-bottom: 20px;
  }

  .how-it-works-mobile{
    width: 100%;
    background:#1572C4;
  }

  .headlines{
    display: none;
  }

  .circle::before{
    content: '';
    width: 30px;
    height: 30px;
    background: #063860;
    border-radius: 50%;
    position: absolute;
    z-index: 10;
    overflow-x: hidden;
  }

  .circle::after{
    content: '';
    background: transparent;
    border-left: 6px dotted #1572C4;
    width: 10px;
    height: 110px;
    position: absolute;
    bottom: 0;
    z-index: -1;
    left: 12px;
  }

  .circle{
    position: relative;
    width: 30px;
    height: 30px;
    background: #063860;
    border-radius: 50%;
    margin-left: -16px;
    margin-right: 24px;
  }

  .headlines-mobile{
      margin: 40px 0!important;
      margin-left: 24px!important;
    }

  .headlines-mobile h4{
      font-size: 2rem;
      color: #1572C4;
      font-weight: 900;
    }

  .headlines-mobile h3{
      margin: 6px auto;
      font-size: 2rem;
      color: #1572C4;
      font-weight: 700;
    }

  .how-it-works-mobile h3{
    font-size: 2rem;
    color: #fff;
    font-weight: 900;
    margin-bottom: 20px;
    text-align: center;
    padding: 30px 14px;
  }

  .header h4{
    font-weight: 400;
    font-size: 1.2rem;
    color: #fff;
    border-radius: 12px;
    background: #186094;
    text-align: center;
    padding: 8px 14px;
    z-index: 2;
  }

  .header p{
    font-size: 1.1rem;
    color: #474747;
    font-weight: 600;
    margin: 20px 15px;
  }

  .header img{
    width: 100%;
    margin-top: -80px;
    z-index: 0;
  }

  .aside{
    display: flex;
  }

  .aside h4{
    margin: 20px auto;
    color: #2184CB;
    font-weight: 800;
    font-size: 1.2rem;
  }
  
  a img.brand-banner, a svg.brand-banner{
    width: 100%;
  }
  .brand-banners a{
    margin: 0 4px;

  }
  .brand-banners{
    display: flex;
    align-items: center;
    justify-content: space-around;
    border-radius: 12px;
    width: 70%;
    padding: 20px;
    margin: 0 auto;
    background: #DEEEFD;
  }

  .mobile-brand{
    margin: 30px auto;
  }

  .mobile-brand .brand-banners{
    margin: 10px auto;
  }

  .mobile-brand h4{
    margin: 10px;
    text-align: center;
    color: #2184CB;
    font-weight: 800;
    font-size: 1.2rem;
  }

   .mobile-brand img.brand-banner,.mobile-brand svg.brand-banner{
    width: 70%;
  }

  .tell-case {
    display: none;
  }
 
  .rights{
    display: none;
  }

  .rights-mobile {
    background: #DDE7F7;
    padding: 20px 0;
    text-align: center;
  }
  
  .rights-mobile .headlines-mobile{
    text-align: center;
  }
  
  .rights-mobile .content{
    font-size: 1.2rem;
    padding: 40px 20px;
  }
  
  .rights-mobile .content strong{
    color: #F05000 ;
  }
  
  .tell-case-mobile{
    padding: 40px 0;
    color: #fff;
    background: #063860;
  }
  
  .tell-case-mobile .title{
    margin: 8px 0;
    padding: 0 8px;
    font-size: .8rem;
    
  }

  .list{
    flex: 1;
  }

  @media screen and (max-width: 830px) {
  .aside{
      display: none;
    }
      .header h1{
    text-align: center;
    }


  }
  @media screen and (min-width: 830px) {
    .headline-hidden{
      display: none!important;
    }

    .images{
    display: flex;
  }

    .header img.mobile-banner{
    display: none;
    }
      .header h1{
        z-index: 10;
    font-size: 6rem;
    color: #063860;
    font-weight: 900;
    text-shadow: 7px 3px 0px #508DB7;
    margin-bottom: -10px;
  }
    .header p{
    font-size: 1.1rem;
    color: #474747;
    font-weight: 600;
    margin-left: 100px;
    margin-top: 50px;
    margin-bottom: 50px;
    
    text-align: start;
  }
    .aside{
      display: flex;
      flex-direction: column;
      width:  70%;
    }
    .aside img.aside-banner{
      max-height:  70%;
      height:  auto;
      width:  100%;
    }
    .how-it-works-mobile{
      display: none;
    }
    .wpt{
      margin: 140px auto;
    }
     .headlines-mobile{
       display: none;
     }
    .headlines{
      display: block;
      margin-left: 16%!important;
      margin-top: 50px;
      margin: 0 auto;
    }
    .headlines h4{
      font-size: 2.4rem;
      color: #063860;
      font-weight: 900;
    }
    .headlines h3{
      margin: 6px auto;
      font-size: 2.4rem;
      color: #063860;
      font-weight: 700;
      text-shadow: 3px 2px 0px #508DB7;
    }

    .mobile-brand{
      display: none;
    }

    .tell-case {
      display: flex;
      height: 200px;
      background: #0072c4;
    }
    .tell-case .title{
      color: #fff;
      font-size: 1.2rem;
    }
    .tell-case .button{
     font-size: 1.2rem!important;
    padding: 12px 40px!important;
    }
    
    .rights{
      display: block;
      padding-left: 100px;
      padding-top: 50px;
      background-image: url("../assets/img/shadow.png");
      background-repeat: no-repeat;
      background-size: 1500px;
      background-position: -675px -250px;

    }
    .rights p{
      color: #000;
      font-size: 1rem;
      max-width: 700px;
      width: 80%;
    }
    .rights .headlines{
    display: block;
    margin-left: 0!important;
    margin-top: 50px;
    margin: 0 auto;
    margin-bottom: 50px;
    }
    .rights strong{
      color: #0072c4;
      font-size: 1.2rem;
      max-width: 700px;
      width: 80%;
    }

 .rights-mobile {
    display: none;
  }
  .descomplicando{
    margin-left: -100px!important;
  }

  .descomplicando img{
    width: 550px;
    height: 550px;
  }
  .where{
    position: relative;
    width: 40%;
    height: 190px;
    margin-left: 40px;
  }

  .where h4{
    position: absolute;
    bottom: 0;
    left: 40px;
    font-size: 1.4rem;
    text-align: right;
    color: #0072c4;
    margin: 20px 0;
  }

  img.from-to{
    width: 350px;
    height: 300px;
    transform: translate(195px, -113px);
  }
  
  .tell-case-mobile{
  display: none;
  }
  
  .where-we-are{
    padding: 0 20px;
    margin: 20px 0;
  }

  .explain{
    max-width: 300px;
    width: 90%;
  }
  .explain p strong{
    color: #F05000;
  }
  .images img{
    max-width: 900px;
    width: 90%;
    border: 14px solid #fff;
    border-radius: 14px;
  }
  }
  @media screen and (max-width: 600px) {
      .header img{
      width: 100%;
      margin-bottom: -55px;
    }

  }
  @media screen and (max-width: 993px) {
     .descomplicando{
       flex-direction: column;
     }

     .rights .headlines{
       margin: 0 auto !important;
       padding: 0 10% 5%;
     }

    .headline-hidden i{ 
      color: #fff;
      margin: 0 20px;
    }
    .headline-hidden{
      width: 100vw;
      padding: 20px;
      font-size: 1.4rem;
      text-align: left;
      color: #fff;
      background: #0072c4;
      margin: 20px 0;
      display: flex!important;
      justify-content: center;
    }
    
    .explain{
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    
    .explain p{
      text-align: center;
      margin: 30px 0;
    }
    
    .explain p strong{
      color: #F05000;
    }
    .where{
      display: none;
    }
  }
</style>
