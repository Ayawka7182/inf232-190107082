<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yummy</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

</head>

<body onload="load()">
    <div class="header">

        <div id="menu" onclick="change(this)" onmouseover="big(this)" onmouseout="small(this)">Menu</div>
        <div id="order" onclick="change(this)" onmouseover="big(this)" onmouseout="small(this)">About us</div>
        <div id="home" onclick="window.location.reload()" onmouseover="big(this)" onmouseout="small(this)"><img
                src="yum1.png" , width="200px"></div>
        <div id="contacts" onclick="change(this)" onmouseover="big(this)" onmouseout="small(this)">Basket</div>
    </div>
    

    <div id="demo" class="carousel slide" data-ride="carousel">

        <!-- Indicators -->
        <ul class="carousel-indicators">
          <li data-target="#demo" data-slide-to="0" class="active"></li>
          <li data-target="#demo" data-slide-to="1"></li>
          <li data-target="#demo" data-slide-to="2"></li>
        </ul>
        
        <!-- The slideshow -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="chic.jpg" alt="Los Angeles" width="500px" height="200px">
          </div>
          <div class="carousel-item">
            <img src="bur.jpg" alt="Chicago" width="500px" height="200px">
          </div>
          <div class="carousel-item">
            <img src="pizz.jpg" alt="New York" width="500px" height="200px">
          </div>
        </div>
        
        <!-- Left and right controls -->
        <a class="carousel-control-prev" href="#demo" data-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#demo" data-slide="next">
          <span class="carousel-control-next-icon"></span>
        </a>
      </div>


    <div class="main">
        <img id="img" src="https://yummy.co.ug/wp-content/uploads/2019/04/Yummy-logo.svg" alt="logo" width="400px">
    </div>
    <div id="promo">
        <p id="promo_subtitle">Everyone can try it in our <i>cozy pavilion</i> or make a <i>profitable delivery</i>
            to any place in the city!
        </p>
    </div>
    <script type="text/javascript" src="script.js"></script>
</body>

</html>
