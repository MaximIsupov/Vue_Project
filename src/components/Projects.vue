<template>
    <div class="container" id="Proects">
        <div class="row">
            <strong class="col"> 
                <h2>Реализованные проекты систем </h2>
                <h2>капельного орошения </h2>
            </strong>
            <a href="#" id=greentext1 class="col"> Все проекты </a>
        </div>
        <div class="card-deck">
            <div class="card">
                <img class="card-img" src="@/images/image1.jpg" alt="Card image">
                <div class="card-img-overlay">
                    <h5 class="card-text">КАПЕЛЬНЫЙ ПОЛИВ САЛАТА В ЦФО</h5>
                </div>
            </div>
            <div class="card">
                <img class="card-img" src="@/images/image2.jpg" alt="Card image">
                <div class="card-img-overlay">
                    <h5 class="card-text">КАПЕЛЬНЫЙ ПОЛИВ МАЛИНЫ В ЦФО</h5>
                </div>
            </div>
            <div class="card">
                <img class="card-img" src="@/images/image3.jpg" alt="Card image">
                <div class="card-img-overlay">
                    <h5 class="card-text">КАПЕЛЬНЫЙ ПОЛИВ МОРКОВИ В КАЗАХСТАНЕ</h5>
                </div>
            </div>
            <div class="card">
                <img class="card-img" src="@/images/a_003.jpg" alt="Card image">
                <div class="card-img-overlay  ">
                    <h5 class="card-text">КАПЕЛЬНЫЙ ПОЛИВ ОВОЩЕЙ В ПФО</h5>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
    strong{
        text-align:left;
        color:black;
    }
    
    #Proects{
         margin-top:100px;
    }

    .card-deck{
        margin-top:50px;
    }

    #greentext1{
        color:green;
        text-align:right;
    }

    .card-img-overlay{
        padding-top:180px;
    }

    .card-img-overlay{
        text-align:left;
        background-color:rgba(0,0,0,.3);
        color:white;
    }
</style>