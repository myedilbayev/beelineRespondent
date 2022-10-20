<template>
    <section class="who_is_respondent">
            <div class="container">
                <h2 class="who_is_respondent_title">Кто такой респондент?</h2>
                <div class="who_is_respondent_descr">Респондент - человек, принимающий участие в опросе, интервью или тестировании дизайна. Мы используем твои ответы в проектировании новых продуктов, чтобы сделать их понятнее, удобнее и приятнее для пользователей.</div>
            </div>
        </section>
</template>

<style>
.who_is_respondent {
    height: 376px;
}

.who_is_respondent_title {
    padding-top: 110px;
    text-align: center;
    font-weight: 700;
    font-size: 40px;
    line-height: 48px;
    color: #10083F;
}

.who_is_respondent_descr {
    margin: 0 auto;
    margin-top: 36px;
    width: 642px;
    text-align: center;
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    color: #504D64;
}

@media(max-width:1005px) {
    .who_is_respondent {
        height: 100%;
    }
    .who_is_respondent_title {
        padding-top: 64px;
        margin: 0 auto;
        font-size: 30px;
        line-height: 36px;
    }
    .who_is_respondent_descr {
        margin: 0 auto;
        margin-top: 12px;
        width: 100%;
        font-size: 18px;
        line-height: 24px;
    }
}
</style>