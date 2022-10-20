<template>
    <section class="by_respondent">
            <div class="container respondent_wrapper">
                <div class="respondent_content">
                    <h1 class="title">Стань нашим респондентом</h1>
                    <div class="title-descr">Мы хотим услышать твое мнение, опыт и боли общения с цифровыми продуктами Beeline.
                    </div>
                    <button class="ready"><a href=" 
                        https://docs.google.com/forms/d/e/1FAIpQLSfm_Yj07urIb_fF0mTRGZgl5DWt5lC2qYd4TngwXWMgMHiYMg/viewform?usp=sf_link" target="_blank" class="ready_link">Я готов!</a></button>
                </div>
                    <div class="title_img">
                        <img src="../assets/img/first.svg" alt="title_img" class="title_img_child">
                    </div>
            </div>
        </section>
</template>

<style>

.by_respondent {
    background-color:#EBEBEB;
    height: 526px;
}

.title {
    padding-top: 130px;
    width: 283px;
    font-weight: 700;
    font-size: 40px;
    line-height: 48px;
    color: #10083F;
}

.title-descr {
    width: 340px;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    color: #504D64;
    margin-top: 24px;
}

.ready {
    width: 158px;
    height: 56px;
    display: block;
    margin-top: 24px;
    border: none;
    border-radius: 12px;
    background-color: #FFE14D;
    color: #10083F;
    font-weight: 600;
    font-size: 16px;
    line-height: 22px;
    cursor: pointer;
    outline: none;
}

.ready_link {
    color: #10083F;
    text-decoration: none;
}

.respondent_wrapper {
    display: flex;
}

.title_img {
    margin-top: 70px;
    position: relative;
    right: -5%;
}

.title_img_child {
    width: 100%;
}

@media (max-width:1005px) {
    .by_respondent {
        height: 100%;
    }
    .respondent_wrapper {
        display: block;
    }
    .title {
        margin: 0 auto;
        padding-top: 48px;
        font-size: 30px;
        line-height: 36px;
        text-align: center;
    }
    .title-descr {
        margin: 0 auto;
        margin-top: 12px;
        font-size: 18px;
        line-height: 24px;
        text-align: center;
    }
    .ready {
        margin: 0 auto;
        margin-top: 24px;
        height: 48px;
        line-height: 20px;
        text-align: center;
    }
    .respondent_wrapper {
        flex-direction: column;
    }
    .title_img {
        position: static;
        margin-top: 59px;
    }
    .title_img_child {
        height: 235px;
    }
}

@media(max-width: 350px) {
    .title {
        width: 100%;
    }
    .title-descr {
        width: 100%;
    }
}

</style>