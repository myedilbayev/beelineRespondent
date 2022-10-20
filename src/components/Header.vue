 <template>
     <header class="header_section">
                <div class="container">
                    <div class="header_wrapper">
                        <a href="https://beeline.kz/ru">
                            <img src="../assets/img/logo.svg" alt="logo" class="logo_img">
                        </a>
                    <nav> 
                                <ul class="menu">
                                    <li class="menu_item">
                                        <a href="#what_benefits" class="menu_link">Какие плюсы?</a>
                                    </li>
                                    <li class="menu_item">
                                        <a href="#participate" class="menu_link">Что потребуется от тебя</a>
                                    </li>
                                    <li class="menu_item">
                                        <a href="#our_mission" class="menu_link">Наша мисиия</a>
                                    </li>
                                    <li class="menu_item">
                                        <a href="https://docs.google.com/forms/d/e/1FAIpQLSfm_Yj07urIb_fF0mTRGZgl5DWt5lC2qYd4TngwXWMgMHiYMg/viewform?usp=sf_link" class="menu_link" target="_blank">Присоединиться</a>
                                    </li>
                                </ul> 
                    <button class="nav-button">
                        <img src="../assets/img/navbtn.svg" alt="Nav button">
                    </button>
                    </nav>
                    </div>
                 </div>
    </header>
</template>

<style>
    .header_section {
    height: 73px;
    background-color: #EBEBEB;
    padding-top: 32px;
}

.header_wrapper {
    display: flex;
    justify-content: space-between;
    align-items:center;
}

.menu {
    display: flex;
    height: 41px;
    list-style: none;
    font-weight: 700;
    font-size: 16px;
    line-height: 22px;
}

.nav-button {
    width: 36px;
    height: 36px;
    display: none;
    border: none;
}

.menu_item {
    margin-right: 36px;
}

.menu_link {
    display: block;
    height: 100%;
    color: #10083F;
    text-decoration: none;
}

.menu_link:hover {
    border-bottom: 1px solid #FFE14D;
}


@media (max-width:1005px) {
    .header_section {
        padding-top: 28px;
    }
}

@media(max-width: 890px) {
    .menu {
        display: none;
    }
    .nav-button {
		display: block;
	}
}



</style>
