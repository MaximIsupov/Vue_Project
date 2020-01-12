<template>
    <div class="container-fluid" id="header">   
        <div class="row mx-2 row justify-content-center"> 
            <img src="@/images/logo.jpg" alt = "logo" id="logo" class="col-1 my-auto">
            <div class="col-2 my-auto" id="greentext"> Новый век агротехнологий </div>
                <div class="col-2  column px-0 my-auto">
                    <div class="col">
                        <img id="galka" src="@/images/galka.jpg" alt="galka"> Капельное орошение
                    </div>
                    <div class="col">
                        <img id="galka" src="@/images/galka.jpg" alt="galka"> Упаковка для кормовых культур
                    </div>
                    <div class="col">
                        <img id="galka" src="@/images/galka.jpg" alt="galka"> Упаковка для овощных культур
                    </div>
                </div>
                <div class="col-2 column px-0">
                    <div class="col" id="greentext">
                        8 800 555-86-88
                    </div>
                    <div class="col">
                        Звонок по России-бесплатный
                    </div>
                    <div class="col" id="greentext">
                        info@neo-agriservis.ru
                    </div>
                    <div class="col">
                        Пн.-Пт.:8:30-17:00
                    </div>
                </div>
                <div class="col-2 my-auto column">
                    <div class="col">Мы в соц. сетях:</div>
                        <div class="col row">
                            <div class="col"> 
                                <img id="logosoc" src="@/images/youtube.png" alt=youtubelogo>
                            </div>
                            <div class="col">
                                 <img id="logosoc" src="@/images/vk.jpg" alt=vklogo>
                            </div>
                            <div class="col"> 
                                <img id="logosoc" src="@/images/inst.jpg" alt=instagramlogo>
                            </div>
                        </div>
                    </div>
                </div>  
                <hr>
               
                    <div class="row justify-content-around">
                        <div class="col-3 " id="greytext">
                            <p>1998-2019 Все права защищены владельцами торговой марки</p>
                            <p>ЗАО "Новый век агротехнологий"</p>
                        </div>
                        <div class="col-3" id="greytext2">
                            <p><a href="#" id="greytext">Положение о защите персональных данных</a></p>
                            <p>Разработка сайта - drupal-coder.ru</p>
                        </div>
                    </div>
                   
            </div>
</template>

<style scoped>
    #header{
        margin-top:100px;
    }

    #logosoc{
        width:40px;
        height:40px;
    }

    #greytext{
        color:grey;
        font-size:12px;
        text-align:left;
    }

    #greytext2{
        color:grey;
        font-size:12px;
        text-align:right;
    }
</style>