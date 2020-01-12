<template>
<div id="header">
    <div class="container my-auto">
        <div class=" row justify-content-center ">
            <ul id="menu">
                <li>
                    <a href="">Продукция</a>
                    <ul>
                        <li><a href="">КАПЕЛЬНОЕ ОРОШЕНИЕ</a></li>
                        <li><a href="">УПАКОВКА ДЛЯ ОВОЩНЫХ КУЛЬТУР</a></li>
                        <li><a href="">УПАКОВКА ДЛЯ КОРМОВЫХ КУЛЬТУР</a></li>
                    </ul>
                </li>
                <li><a href="/">УСЛУГИ</a></li>
                <li><a href="">РЕАЛИЗОВАННЫЕ ПРОЕКТЫ</a></li>
                <li><a href="">СТАТЬИ</a></li>
                <li><a href="">КЛИЕНТЫ</a></li>
                <li><a href="">О КОМПАНИИ</a></li>     
            </ul>
        </div>
    </div>
</div>
</template>

<style>

#menu, #menu ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

#menu {


 
  background-color:white;

}

#menu:before,
#menu:after {
        content: "";
        display: table;
}

#menu:after {
        clear: both;
}

#menu {
        zoom:1;
}

#menu li {
  float: left;

  position: relative;
}

#menu a {
  float: left;
  padding: 12px 30px;
  color: black;
  text-transform: uppercase;
  font: 16px Arial, Helvetica;
}

#menu li:hover > a {
  color: #0e8a0a;
}
    #menu ul {
  margin: 20px 0 0 0;
  opacity: 0;
  visibility: hidden;
  position: absolute;
  top: 38px;
  left: 0;
  z-index: 9999;
  background: rgb(255, 255, 255);
  text-align: left;
}

#menu li:hover > ul {
  opacity: 1;
  visibility: visible;
  margin: 0;
}

#menu ul ul {
  top: 0;
  left: 150px;
  margin: 0 0 0 20px; 
}

#menu ul li {
  float: none;
  display: block;

}

#menu ul li:last-child {
  -moz-box-shadow: none;
  -webkit-box-shadow: none;
  box-shadow: none;
}

#menu ul a {
  padding: 10px;
  width: 310px;
  display: block;
  white-space: nowrap;
  float: none;
  text-transform: none;
}



#menu ul li:first-child > a {
  -moz-border-radius: 3px 3px 0 0;
  -webkit-border-radius: 3px 3px 0 0;
  border-radius: 3px 3px 0 0;
}

#menu ul li:first-child > a:after {
  content: '';
  position: absolute;
  left: 40px;
  top: -6px;
  border-left: 6px solid transparent;
  border-right: 6px solid transparent;
  border-bottom: 6px solid #444;
}

#menu ul ul li:first-child a:after {
  left: -6px;
  top: 50%;
  margin-top: -6px;
  border-left: 0;
  border-bottom: 6px solid transparent;
  border-top: 6px solid transparent;
  border-right: 6px solid #3b3b3b;
}

#menu ul li:first-child a:hover:after {
  border-bottom-color: #04ec04;
}

#menu ul ul li:first-child a:hover:after {
  border-right-color: #02d313;
  border-bottom-color: transparent;
}

#menu ul li:last-child > a {
  -moz-border-radius: 0 0 3px 3px;
  -webkit-border-radius: 0 0 3px 3px;
  border-radius: 0 0 3px 3px;
}

@media (min-width: 800px) {
  
  
  .header{
    display:block;
  }
 }
</style>