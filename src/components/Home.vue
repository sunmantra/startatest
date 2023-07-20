<template>
   <div class="wrapper">
        <div class="imgfon">
            <img src="../img/slidehader.png" alt="">
        </div>
        <div class="crownchoice">
            <div class="container">
                <h1 class="crownchoice__title"> THE CROWN FOR YOUR KITCHEN</h1>
                <div class="crownchoice__element">
                    <p>Reginox bv, Nederland</p>
                    <p>Reginox Rif Holding, Russia</p>
                    <p>Reginox, UK Ltd</p>
                    <p>Reginox, Singapure</p>
                </div>
            </div> 
        </div>
        <div class="catalog">
            <div class="container">
                <h2 style="margin-top: 132px;">КАТАЛОГ</h2>
                <div style="height: 1420px;" class="catalog__group">
                    <div class="catalog__elem" >1<img src="../img/group/1.png" alt=""> </div>
                    <div class="catalog__elem">2<img src="../img/group/2.png" alt=""></div>
                    <div class="catalog__elem">3<img src="../img/group/3.png" alt=""></div>
                    <div class="catalog__elem">4<img src="../img/group/4.png" alt=""></div>
                    <div class="catalog__elem">5<img src="../img/group/5.png" alt=""></div>
                    <div class="catalog__elem">6<img src="../img/group/6.png" alt=""></div>
                    <div class="catalog__elem">4<img src="../img/group/7.png" alt=""></div>
                    <div class="catalog__elem">5<img src="../img/group/8.png" alt=""></div>
                    <div class="catalog__elem">6<img src="../img/group/9.png" alt=""></div>
                </div>
                <h2 style="margin-top: 130px;">ПОПУЛЯРНЫЕ ТОВАРЫ</h2>
                <div style="height: 1000px;" class="catalog__group">
                    <div class="catalog__elem">1<img src="../img/group/1.png" alt=""> </div>
                    <div class="catalog__elem">2<img src="../img/group/2.png" alt=""></div>
                    <div class="catalog__elem">3<img src="../img/group/3.png" alt=""></div>
                    <div class="catalog__elem">4<img src="../img/group/4.png" alt=""></div>
                    <div class="catalog__elem">5<img src="../img/group/5.png" alt=""></div>
                    <div class="catalog__elem">6<img src="../img/group/6.png" alt=""></div>
                </div>
                <h2 style="margin-top: 205px;">О КОМПАНИИ</h2>
                <div  class="about">
                    <h3 style="font-weight: 600;">Добро пожаловать на сайт Компании Reginox Reef Holding(ООО «РеджиноксРиф   Холдинг») — единственного и официального   представителя производителя сантехнической продукции для кухни и ванной комнаты Reginox (Нидерланды).</h3>
                    <h3 >Основной специализацией нашей компании являются розничные и оптовые продажи кухонной сантехники по всей России. Мы предлагаем кухонные мойки из нержавеющей стали и гранитного композита,  смесители для кухни, а также оригинальную продукцию от Reginox:</h3>
                    <h3>умывальники окрашенныемойки системы газовых конфорок  PITTbyReginox многофункциональные кухонные комплексы и др.</h3>
                    <h3>Более 25 лет назад компания RRHolding представила на российском рынке кухонные мойки Reginox из нержавеющей стали, приятно удивившие покупателей отличным качеством, многообразием моделей и современным дизайном. Продукция Reginox входит в постоянный ассортимент ряда крупных фабрик-производителей мебели, введена в предложение крупнейших продавцов мебельной фурнитуры и комплектующих, и представлена вомножестве кухонных салонов по всей России. За годы нашей работы мы заключили контракты в сферах: </h3>
                    <h3>авиастроение вагоностроение</h3>
                    <h2 style="font-size: 32px;">Наши преимущества</h2>
                    <h3>список</h3>
                    <h3>Благодаря многолетнему и плодотворному тандему RRHolding и Reginox, сегодня мы имеем большое количество бизнес-партнеров, в том числе и за пределами РФ, с которыми поддерживаем и развиваем взаимовыгодные отношения, приобрели популярность среди потребителей, и сохранили за собой статус компании, предлагающей на рынке России продукцию со «стальной репутацией». Мы предлагаем лучшее качество от европейского завода-производителя (завод   расположен   в   Нидерландах,   город   Rijssen) и пожизненную гарантию на продукцию из нержавеющей стали!</h3>
                </div>
            </div>
        </div>
    </div>
   

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
h1{
    color: #FFF;
    text-align: center;
    font-family: Montserrat;
    font-size: 70px;
    font-style: normal;
    font-weight: 700;
    line-height: 150%;
    letter-spacing: 1.4px;
    text-transform: uppercase;
    margin:0px 0px 0px 0px;
}
h2{
    color: var(--grafit, #333);
    font-family: Montserrat;
    font-size: 48px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    text-transform: uppercase;
}
h3{
    color: var(--grafit, #333);
    font-family: Montserrat;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    letter-spacing: 0.4px;
}
p{
    color: var(--grafit, #333);
    font-family: Montserrat;
    font-size: 16px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
}
.imgfon{
height: 811px;
}
.imgfon img{
    max-width: 1921px;
    flex-shrink: 0;
}
.crownchoice{
    width: 1921px;
    flex-shrink: 0;
    height: 330px;
    background: var(--gray-light, #ECECEC);
}
.crownchoice__title{
    margin-top: 42px;
    margin-bottom: 23px;
}
.crownchoice__element{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}

.catalog{
    background: #FFF;
    width: 100%;
}

.catalog__group{
    margin-top: 32px;
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    
    justify-content: space-between;
}
.catalog__elem{
    width: 383px;
    height: 440px;
    flex-shrink: 0;
    background: linear-gradient(180deg, rgba(0, 0, 0, 0.00) 0%, #000 100%);

    }
.catalog__elem img{
}

.about{
    display: flex;
    width:816px ;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 200px;
}
</style>