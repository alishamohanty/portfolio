<template>
    <div class="about-page">
        <div class="picture">
            <img src="../static/alisha.jpg" class="alisha-pic"/>
        </div>
        <div class="content">
            <div class="heading">
                Code-Color-Cook
            </div>
            <div class="yellow-line" />
            
            <div class="about-content">
                Hey! I am Alisha Mohanty. I am a developer at Accenture who is trying to get out of it.
                *Hoping no Accenture folks sees*. Major portion of my life I have been a nerdish introvert
                procastinating and building new situations and reliving moments. But now I dedicate most of my time
                trying new things. Thanks to Internet. Discovering new interests has become my recent passion.
                I go by the mantra, why not try everything? 
                You are most likely to find me learn something or experimenting new dishes. Also, I now into 
                digital art too so, please sponser me an ipad *if you can*.
                Sideby, I am also doing different projects, so feel free to hire me or colaborate
                on different ideas too *P.S Idea has to interesting*. Send me a message in any platforms. See you soon :)
            </div>
        </div>
    </div>
</template>

<style scoped>
.alisha-pic{
    height:350px;
    width: 280px;
}
.content{
    width: 100%;
}
.about-page{
  display: flex;
  justify-content: space-between;
  flex-direction: row-reverse;
  font-size: 17px;
  color: rgba(52,59,76,.8);
}
.picture{
    justify-content: center;
    margin: auto auto;
    width:100%;
    text-align: center;
}
.about-content{
    width:85%;
    text-align: justify;
    margin: auto;
    padding-top: 10px;
    line-height: 29px;
}
.content .heading {
    margin: auto auto;
    text-align: center;
    font-size: 30px;
    font-weight: 600;
    color: #012E51;
}
.yellow-line{
    background-color: #fbb946;
    height:7px;
    width:230px;
    margin: auto;
    bottom:14px;
    z-index: -2;
    position: relative;

}
@media (max-width: 1000px)
{
    .about-page{
        display: grid;
    }
}
</style>