<template>
    <div class="container-fluid mt-1" id="News">
        <div class="container">
            <div class="row" >
                <strong class="col" id="top"> 
                    <h2>Архив новостей </h2>
                </strong>
                <a href="#" id=greentext1 class="col"> Все новости </a>
            </div>
            <div class="card-deck">
                <div class="card">
                    <div class="card-body">
                        <p class="card-title"><span class="bigdata"> 06 </span> сентября </p>
                        <h5>Компания ЗАО "Новый век агротехнологий" впервые примет участие в "Дне поля Ставропольского края 2019"</h5>
                        <p class="card-text">C 19 по 20 сентября 2019 года на территории выставочного комплекса АПК Ставропольского края пройдёт "День поля Ставропольского края 2019"</p>
                        <a href="#" class="btn btn-primary">Подробнее</a>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <p class="card-title"> <span class="bigdata"> 26 </span> августа </p>
                        <h5>Средние оптовые цены на белокачанную капусту в России в 2019 году, данные на 2 августа 2019 г.</h5>
                        <p class="card-text">Специалисты Экспертно-аналитического центра агробизнеса "АБ-Центр" www.ab-centre.ru подготовили очередное еженедельное исследование рынка картофеля и овощей(см.)</p>
                        <a href="#" class="btn btn-primary">Подробнее</a>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <p class="card-title"><span class="bigdata"> 12 </span> августа </p>
                        <h5>Средние оптовые цены на помидоры в России в 2019 году, данные на 2 августа</h5>
                        <p class="card-text">Специалисты Экспертно-аналитического центра агробизнеса "АБ-Центр" www.ab-centre.ru подготовили очередное исследование рынка картофеля и овощей (см.)</p>
                        <a href="#" class="btn btn-primary">Подробнее</a>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body">
                        <p class="card-title"><span class="bigdata"> 01 </span> августа</p>
                        <h5>Компания ЗАО "Новый век агротехнологий" примет участие в выставке "БелгродоАгро-2019"</h5>
                        <p class="card-text">Приглашаем вас посетить стенд нашей компании No 39</p>
                        <a href="#" class="btn btn-primary">Подробнее</a>
                    </div>
                </div>
            </div>
        </div>
    </div>      
</template>

<style scope>
    #greentext1{
        color:green;
        margin-top:50px;
    }

     .card-deck{
   margin-bottom:40px;
   padding-bottom:80px;
 }

    #top{
        margin-top:50px;
    }

    #News{
        background-image:url(field.jpg);
    }

    .card{
        text-align:left;
        margin-bottom:50px;
    }

    .bigdata{
        color:green;
        font-size:40px;
        font-weight: bold;
    }
 </style>