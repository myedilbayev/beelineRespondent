<template>
            <section class="participate" id="participate">
            <div class="container">
                <h2 class="participate_title">Как принять участие?</h2>
                <div class="participate_wrapper">
                    <div class="participate_steps margin_right margin_bottom">
                        <div class="first">1</div>
                        <h3 class="first_title">Оставь <a href="https://docs.google.com/forms/d/e/1FAIpQLSfm_Yj07urIb_fF0mTRGZgl5DWt5lC2qYd4TngwXWMgMHiYMg/viewform?usp=sf_link" class="request" target="_blank">заявку</a> </h3>
                        <div class="participate_cards_descr">Заполни форму максимально честно, выбери продукты которые хочешь тестировать
                        </div>
                    </div>   
                    
                    <div class="participate_steps margin bottom">
                            <div class="second">2</div>
                            <h3 class="second_title">Ожидай приглашения на интервью</h3>
                            <div class="participate_cards_descr">Будь на связи :) Мы напишем тебе заранее и договоримся об удобном времени. Обычно интервью не занимает больше 30-40 минут. 
                            </div>
                    </div>

                    <div class="participate_steps margin_right">
                        <div class="third">3</div>
                        <h3 class="third_title">Позаботься об окружении</h3>
                        <div class="participate_cards_descr">Выбери спокойное, тихое место с хорошим интернетом. Обязательно приноси с собой хорошее настроение😉 
                        </div>
                </div>

                <div class="participate_steps">
                    <div class="fourth">4</div>
                    <h3 class="fourth_title">Получи клевую ачивку</h3>
                    <div class="participate_cards_descr">После первого интервью, в приложении
                        Мой Билайн тебе откроется новая ачивка
                        «Яркий пиздюк». Спасибо, что ты с нами!                         
                    </div>
            </div>
                </div>
            </div>
        </section>
</template>

<style>

.participate {
    height: 710px;
}

.participate_title {
    font-weight: 700;
    font-size: 40px;
    line-height: 48px;
    color: #10083F;
}

.participate_wrapper {
    margin-top: 40px;
    display: flex;
    align-items: flex-start;
    flex-wrap: wrap;
    height: 100%;
}

.participate_steps {
    width: 400px;
}

.margin_right {
    margin-right: 150px;
}

.margin_bottom {
    margin-bottom: 102px;
}

.first {
    width: 62px;
    height: 62px;
    font-weight: 700;
    font-size: 36px;
    line-height: 26px;
    text-align: center;
    vertical-align: center;
    color: #0183D4;
    background: #EAF4FF;
    border-radius: 16px;
    padding-top: 18px;
}

.first_title {
    font-weight: 500;
    font-size: 20px;
    line-height: 26px;
    color: #000000;
    margin-top: 24px;
}

.participate_cards_descr {
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    color: #858295;
    margin-top: 12px;
}

.second {
    width: 62px;
    height: 62px;
    font-weight: 700;
    font-size: 36px;
    line-height: 26px;
    text-align: center;
    vertical-align: center;
    color: #9E66FF;
    background: #F3ECFF;
    border-radius: 16px;
    padding-top: 18px;
}

.second_title {
    font-weight: 500;
    font-size: 20px;
    line-height: 26px;
    color: #000000;
    margin-top: 24px;
    width: 236px;
}

.third {
    width: 62px;
    height: 62px;
    font-weight: 700;
    font-size: 36px;
    line-height: 26px;
    text-align: center;
    vertical-align: center;
    color: #61CA45;
    background: #DFF7D9;
    border-radius: 16px;
    padding-top: 18px;
}
.third_title {
    font-weight: 500;
    font-size: 20px;
    line-height: 26px;
    color: #000000;
    margin-top: 24px;
    width: 236px;
}

.fourth {
    width: 62px;
    height: 62px;
    font-weight: 700;
    font-size: 36px;
    line-height: 26px;
    text-align: center;
    vertical-align: center;
    color: #FFBD12;
    background: #FFF7E2;
    border-radius: 16px;
    padding-top: 18px;
}

.fourth_title {
    font-weight: 500;
    font-size: 20px;
    line-height: 26px;
    color: #000000;
    margin-top: 24px;
    width: 236px;
}

@media(max-width: 1005px) {
    .participate {
        height: 100%;
    }
    .participate_title {
        margin: 0 auto;
        padding-top: 80px;
        text-align: center;
        font-size: 30px;
        line-height: 36px;
    }
    .participate_wrapper {
        display: block;
        margin: 0 auto;
    }
    .participate_steps {
        margin: 0 auto;
        margin-top: 24px;
        width: 100%;
    }
    .first, .second, .third, .fourth {
        margin: 0 auto;
    }
    .first_title, .second_title, .third_title, .fourth_title {
        margin: 0 auto;
        margin-top: 20px;
        width: 100%;
        text-align: center;
    }
    .participate_cards_descr {
        margin: 0 auto;
        margin-top: 12px;
        width: 100%;
        text-align: center;
    }
}
</style>