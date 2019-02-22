<!DOCTYPE html>
<html lang="en">
<head>
  <title>SWIGGY</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
  body {
      font: 20px Montserrat, sans-serif;
      line-height: 1.8;
      color: #f5f6f7;
  }
  p {font-size: 20px;}
  .margin {margin-bottom: 45px;}
  .bg-1 { 
      background-color: #B8860B; /* Green */
      color: #ffffff;
  }
  .bg-2 { 
      background-color: #E9967A; /* Dark Blue */
      color: #ffffff;
  }
  .bg-3 { 
      background-color: #800080; /* White */
      color: #ffffff;
  }
  .bg-4 { 
      background-color: #2f2f2f; /* Black Gray */
      color: #fff;
  }
  .container-fluid {
      padding-top: 70px;
      padding-bottom: 70px;
  }
  .navbar {
      padding-top: 15px;
      padding-bottom: 15px;
      border: 0;
      border-radius: 0;
      margin-bottom: 0;
      font-size: 12px;
      letter-spacing: 5px;
  }
  .navbar-nav  li a:hover {
      color: #1abc9c !important;
  }
      p{
          width: 100%;
          margin: 0px;
          padding: 30px;
          border: 2px solid #000;
          display: inline-block;
          float: left;
      }
      .wrapper{
          background: #fff;
          max-width: 960px;
          margin: 0 auto;
          padding: 20px;
      }
      .wrapper:after{
          content: "";
          display: block;
          clear: both;
      }
      img{
          margin: 0px;
          padding: 10px;
          height: 250px;
          
      }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-default">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">SWIGGY</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">ORDER</a></li>
        <li><a href="#">CHECKOUT</a></li>
        <li><a href="#">PROFILE</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- First Container -->
<div class="container-fluid bg-1 text-center">
  <h2 class="margin">Who We Are?</h2>
  <img src="swiggy.jpg" class="img-responsive img-rounded margin" style="display:inline" alt="Image" width="350" height="350">
  <h2>Order your Food</h2>
</div>

<!-- Third Container (Grid) -->
<div class="container-fluid bg-3 text-center">    
  <h1 class="margin">What Sort Of Items We Offers?</h1><br>
  <div class="row">
    <div class="col-sm-4">
      <p>We offers different kinds of breakfast and our speciality is GRANGE BURGER.</p>
      <br><img src="grange.jpg" div class="thumbnail" style="width:100%" alt="Image">
    </div>
    <div class="col-sm-4"> 
      <p>Like breakfast we also have best Lunch dishes as well especially Asian dishes.</p>
     <br> <img src="lunch.jpg" div class="thumbnail" style="width:100%" alt="Image">
    </div>
    <div class="col-sm-4"> 
      <p>In Dinner we have a variety of continental dishes including Thai, Chinese, Asian, Italian, etc.</p>
      <img src="dinner.jpg" div class="thumbnail" style="width:100%" alt="Image">
    </div>
  </div>
</div>




<!-- Footer -->
<footer class="container-fluid bg-4 text-center">
  <p>Theme Made By MehwishZafar</p> 
</footer>

</body>
</html>
