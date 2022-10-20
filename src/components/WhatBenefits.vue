
<template>
    <section class="what_benefits" id="what_benefits">
            <div class="container">
                <h2 class="what_benefits_title">Какие плюсы?</h2>
                <div class="what_benefits_cards">
                    <div class="card_one">
                        <img src="../assets/img/card1.svg" alt="card1" class="card_img">
                        <div class="card_title">Будь первым</div>
                            <p class="card_descr_1">Ты первым увидишь наши новые продукты и поучаствуешь в их разработке </p>
                    </div>
                    <div class="card_two">
                        <img src="../assets/img/card1.svg" alt="card2" class="card_img">
                        <div class="card_title">Поделись опытом</div>
                        <p class="card_descr_2">Будем рады узнать о твоем опыте использования наших продуктов </p>
                    </div>
                    <div class="card_three">
                        <img src="../assets/img/card3.svg" alt="card3" class="card_img">
                        <div class="card_title_3">Получи уникальную ачивку</div>
                        <p class="card_descr_3">Блестящая, свеженькая и такая уникальная ачивка в приложении “Мой Билайн”</p>
                    </div>
                </div>
            </div>
        </section>
</template>

<style>

.card_one:hover,
.card_two:hover, 
.card_three:hover {
    scale: 1.1;
}

.card_one:hover .card_descr_1,
.card_two:hover .card_descr_2,
.card_three:hover .card_descr_3 {
    opacity: 1;
    scale: 1;
}


.what_benefits {
    height: 640px;
}

.what_benefits_title {
    font-weight: 700;
    font-size: 40px;
    line-height: 48px;
    color: #10083F;
}

.what_benefits_cards {
    margin-top: 40px;
    height: 441px;
    display: flex;
    justify-content: space-around;
}

.card_one {
    width: 314px;
    height: 441px;
    background: #FFF6CC;
    border-radius: 16px;
    transition: 0.5s;
}

.card_two {
    width: 314px;
    height: 441px;
    background: #EAF4FF;
    border-radius: 16px;
    transition: 0.5s;
}

.card_three {
    width: 314px;
    height: 441px;
    background: #000000;
    border-radius: 16px;
    transition: 0.5s;
}

.card_img {
    display: block;
    margin: 0 auto;
    margin-top: 102px;
    width: 150px;
    height: 150px;
}

.card_title {
    font-weight: 500;
    font-size: 20px;
    line-height: 26px;
    text-align: center;
    color: #000000;
    margin-top: 36px;
}

.card_descr_1, .card_descr_2 {
    margin: 0 auto;
    margin-top: 12px;
    width: 291px;
    height: 72px;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    text-align: center;
    color: #78735E;
    opacity: 0;
    transition: 1s;
}

.card_descr_3 {
    margin: 0 auto;
    margin-top: 12px;
    width: 291px;
    height: 72px;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    text-align: center;
    color: rgba(255, 255, 255, 0.8);
    opacity: 0;
    transition: 1s;
}

.card_title_3 {
    font-weight: 500;
    font-size: 20px;
    line-height: 26px;
    text-align: center;
    color: #FFFFFF;
    margin-top: 36px;
}

@media(max-width:1005px) {
    .what_benefits {
    height: 100%;
    }
    .what_benefits_title {
        margin: 0 auto;
        padding-top: 64px;
        text-align: center;
        font-size: 30px;
        line-height: 36px;
    }
    .what_benefits_cards {
        flex-direction: column;
        align-items: center;
        margin-top: 24px;
        height: 100%;
    }
    .crad_one, .card_two, .crad_three {
        width: 343px;
        height: 336px;
        margin-bottom: 24px;
    }
    .card_descr_1, .card_descr_2, .card_descr_3 {
        display: block;
        margin-top: 12px;
    }
    .card_img {
        margin-top: 24px;
    }
    .card_title {
        margin-top: 12px;
    }
}

@media(max-width: 350px) {
    .crad_one, .card_two, .crad_three {
        width: 100%;
    }
}

</style>