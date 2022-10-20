<template>
    <section class="our_mission" id="our_mission">
            <div class="container">
                <div class="mission_wrapper">
                    <div class="mission_img">
                        <img src="../assets/img/mission.svg" alt="mission img" class="mission_img_child">
                    </div>
                    <div class="mission_content">
                        <h2 class="mission_title">Наша миссия</h2>
                        <div class="mission_descr">
                            Тебя тоже раздражает, когда ты пользуешься приложением или сайтом и непонятно куда нажать? Когда попадаешь на пустой экран после ввода данных?
                            <br><br>
                            Нам тоже это не нравится!
                            <br><br>
                            Мы хотим улучшать наши продукты, делать их проще и удобнее для пользователя. Присоединяйся, без тебя нам не обойтись!
                        </div>
                        <button class="mission_btn">
                            <a href="https://docs.google.com/forms/d/e/1FAIpQLSfm_Yj07urIb_fF0mTRGZgl5DWt5lC2qYd4TngwXWMgMHiYMg/viewform?usp=sf_link" class="mission_link">Присоединиться</a>
                        </button>
                    </div>
                </div>
 
            </div>
        </section>
</template>

<style>
.our_mission {
    height: 596px;
}

.mission_wrapper {
    display: flex;
}

.mission_img {
    position: relative;
    left: -6%;
}

.mission_img_child {
    width: 100%;
}

.mission_title {
    margin-top: 24px;
    font-weight: 700;
font-size: 40px;
line-height: 48px;
color: #10083F;
}

.mission_descr {
    margin-top: 40px;
    width: 445px;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    color: #504D64;
}

.mission_btn {
    width: 258px;
    height: 56px;
    margin-top: 55px;
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

.mission_link {
    color: #10083F;
    text-decoration: none;
}

@media(max-width: 1005px) {
    .our_mission {
    height: 100%;
    }
    .mission_wrapper {
    flex-direction: column-reverse;
    }
    .mission_img {
    margin-top: 48px;
    position: static;
    }
    .mission_img_child {
    width: 100%;
    }
    .mission_title {
    padding-top: 80px;
    margin: 0 auto;
    text-align: center;
    font-weight: 700;
    font-size: 30px;
    line-height: 36px;
    }
    .mission_descr {
    margin: 0 auto;
    text-align: center;
    margin-top: 40px;
    width: 100%;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    }
    .mission_btn {
    display: block;
    margin: 0 auto;
    margin-top: 24px;
    text-align: center;
    height: 48px;
    font-size: 16px;
    line-height: 20px;
    }
}
@media(max-width: 350px) {
    .mission_btn {
        width: 100%;
    }
}
</style>