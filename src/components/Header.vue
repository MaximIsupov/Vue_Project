<template>
    <div >
        <div class="container-fluid" id="header">
            <div class="row justify-content-center">
            <img class="col-1 my-auto row" id="logo" src="@/images/logo.jpg" alt="logo">
            <div id="greentext" class="col-2 my-auto ml-1"> Новый век агротехнологий </div>
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
            <div class="col-2 my-auto">
                <router-link to="/form" class="btn">Заказать звонок</router-link>
            </div>
        </div></div>
        <div id="header2">
              <header class="container-fluid bg-light">

                  <div class="pos-f-t">
                    <nav class="navbar navbar-light bg-light row">
                        <button class="navbar-toggler col-2" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                          <span class="navbar-toggler-icon"></span>
                        </button>
                        <img class="col-2" src="@/images/logo.jpg" alt="logo">
                        <span class="col-4" id="greentext"> Новый век агротехнологий </span>
                        <button class="btn btn-outline-success col-4" type="submit">Search</button>
                        <button class="btn btn-primary" data-toggle="modal" data-target=".bd-example-modal-lg">Заказать звонок</button>
                      </nav>
                      <div class="collapse" id="navbarToggleExternalContent" >
                        <div class="bg-light p-4">
                            <div class="col my-auto"> <a href="#">КАПЕЛЬНОЕ ОРОШЕНИЕ</a> </div>
                            <div class="col my-auto"> <a href="#">УПАКОВКА ДЛЯ ОВОЩНЫХ КУЛЬТУР</a> </div>
                            <div class="col my-auto"> <a href="#">УПАКОВКА ДЛЯ КОРМОВЫХ КУЛЬТУР</a> </div>
                            <div class="col my-auto"> <a href="#">УСЛУГИ </a></div>
                            <div class="col my-auto"> <a href="#">РЕАЛИЗОВАННЫЕ ПРОЕКТЫ</a></div>
                            <div class="col my-auto"> <a href="#">СТАТЬИ</a></div>
                            <div class="col my-auto"> <a href="#">КЛИЕНТЫ</a> </div>
                            <div class="col my-auto"> <a href="#">О КОМПАНИИ</a></div>
                            <div class="col my-auto"> <a href="#">КОНТАКТЫ</a> </div>
                        </div>
                      </div>
                      
                    </div>
              </header>
            </div>
    </div>
</template>

<style>
    #galka{
        width:15px;
        height:15px;
    }

    #logo{
        width:auto;
        height:auto;
    }

    #header{
        background-color: #F8F8FF;
        text-align: left;
        display:none;
    }

    #greentext{
        color:green;
    }

    .btn {
    display: inline-block; 
    background: green; 
    color: white; 
    text-decoration: none; 
    border-radius: 3px;
    }

    @media (min-width: 800px) {
  
  
        #header{
            display:block;
        }

        #header2{
            display:none;
        }

 }

</style>