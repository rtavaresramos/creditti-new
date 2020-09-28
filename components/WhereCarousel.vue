<template>
    <div class="carousel-wrapper">
        <span id="photo-1"></span>
        <span id="photo-2"></span>
        <span id="photo-3"></span>
        <div class="carousel-photo photo-1 d-flex flex-col align-center justify-center">
            <div class="circles d-flex justify-center">
                <div class="circle active"></div>
                <div class="circle"></div>
                <div class="circle"></div>
            </div>
            <a class="arrow arrow-prev" href="#photo-3"></a>
            <a class="arrow arrow-next" href="#photo-2"></a>
        </div>
        
        <div class="carousel-photo photo-2 d-flex flex-col align-center justify-center">
            <div class="circles d-flex justify-center">
                <div class="circle"></div>
                <div class="circle active"></div>
                <div class="circle"></div>
            </div>
            <a class="arrow arrow-prev" href="#photo-1"></a>
            <a class="arrow arrow-next" href="#photo-3"></a>
        </div>
        
        <div class="carousel-photo photo-3 d-flex flex-col align-center justify-center">
            <div class="circles d-flex justify-center">
                <div class="circle"></div>
                <div class="circle"></div>
                <div class="circle active"></div>
            </div>
              
            <a class="arrow arrow-prev" href="#photo-2"></a>
            <a class="arrow arrow-next" href="#photo-1"></a>
        </div>
    </div>
</template>

<style lang="css" scoped>
@media screen and (min-width: 830px){
    .carousel-wrapper{
        display: none;
    }
}
.circles{
    height: 100%;
    align-items: flex-end;
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

.carousel-wrapper{
  min-height: 330px;
  max-height: 530px;
  padding: 10px 0;
  height: auto;
  position: relative;
  max-width: 500px;
  width: 100%;
  margin: 0 auto;
  margin-left: -165px;
}
.carousel-photo{
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
  border:solid rgba(255, 255, 255, .5);
    border-width: 0 14px 14px 0;
    border-radius: 4px;
    display: inline-block;
    padding: 12px;
}

.arrow-prev{
  left:10px;
  position:absolute;
  top:50%;
  transform:translateY(-50%) rotate(135deg);
}
 
.arrow-next{
    right: 10px;
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
[id^="photo"] {
    display: none;
  }

.photo-1 {
   margin: 10px;
   min-width: 310px;

    z-index: 2;
    opacity: 1;
    background: url('../assets/img/where-1.jpeg');
    background-repeat: no-repeat;
    background-size: contain;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
  }
 
.photo-2{
    margin: 10px;
    min-width: 310px;
    background: url('../assets/img/where-2.jpeg');
    background-repeat: no-repeat;
    background-size: contain;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
}
  
.photo-3{
    margin: 10px;
    min-width: 310px;
    background: url('../assets/img/where-3.jpeg');
    background-repeat: no-repeat;
    background-size: contain;
    border-radius: 14px;
    box-shadow: 0 0 10px -5px #000;
}
 

*:target ~ .photo-1 {
    opacity: 0;
  }

#photo-1:target ~ .photo-1 {
    opacity: 1;
  }

#photo-2:target ~ .photo-2, #photo-3:target ~ .photo-3 {
    z-index: 3;
    opacity: 1;
  }

</style>