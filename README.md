# estefany-flores-tarea2.1.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carrusel</title>
    <link rel="stylesheet" href="carrusel.css">
    
</head>
<body>
  <style>
    body{
    background-color: aquamarine;
}

.carrusel{
    display: flex;
    flex-wrap: nowrap;
    overflow: scroll;

}

.elemento {
    flex: 1 0 auto;
    margin: 0 50 px;
    background-color: blue;
    width: 500px;
    height: 400px;
}
.elemento img{
    width: 500px;
    height: 400px;
}
    
</style>
  <div class="carrusel">
    <div class="elemento"><img src="https://www.muyinteresante.com/wp-content/uploads/sites/5/2023/12/28/658d3cc8a1698.jpeg" alt=""></div>
    <div class="elemento"><img src="https://www.ngenespanol.com/wp-content/uploads/2024/03/estos-son-los-animales-que-no-deberias-tener-como-mascotas.jpg" alt=""></div>
    <div class="elemento"><img src="https://files.worldwildlife.org/wwfcmsprod/images/Hawksbill_turtle_290360/story_full_width/1o10ihiftu_WEB_290360.jpg" alt=""></div>
    <div class="elemento"><img src="https://www.tiendanimal.es/articulos/wp-content/uploads/2023/05/coyote.jpg" alt=""></div>
    <div class="elemento"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXKDBAkdpwqK1yNcBhKgFRWnhQ5ca91YMSiw&s" alt=""></div>
    <div class="elemento"><img src="https://www.mundodeportivo.com/urbantecno/hero/2023/04/animales-mas-inteligentes-del-mundo.jpg?width=1200" alt=""></div>
    <div class="elemento"><img src="https://www.zotal.com/wp-content/uploads/2022/11/apareamientodeanimales.jpg" alt=""></div>
    <div class="elemento"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUDR3dwAkdxP8HebETlYVuuuYjWZ3we-__-A&s" alt=""></div>
  </div>
    
</body>
</html>
