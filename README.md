<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">

    <script src="https://kit.fontawesome.com/738b56787a.js" crossorigin="anonymous"></script>
    <title>Becekin.id</title>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <a class="navbar-brand" href="index.html"><img src="InShot_20191212_130550021.jpg" width="50" alt="logo Becekin.id">Becekin.id</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ml-auto">
            <a class="nav-link active" href="#home">HOME<span class="sr-only">(current)</span></a>
            <a class="nav-link" href="#services">FEATURES</a>
            <a class="nav-link" href="#about">ABOUT</a>
            <a class="nav-link" href="#contact">CONTACT</a>
          </div>
        </div>
      </nav>
    </div>

    <div class="jumbotron jumbotron-fluid text-white text-center">
      <div class="container">
        <h1 class="display-4">Becekin.id</h1>
        <p class="lead">Cuci motor gak pake ribet. #dirumahaja</p>
      </div>
    </div>

      <div class="row">
        <div class="col-md-12">
          <h1 class="text-center">OUR SERVICE</h1>
        </div>
      </div>
    <div id="services">
      <div class="row">
        <div class="col-md-6 text-center">
          <i class="fas fa-house-user"></i>
          <p>HOME SERVICE</p>
        </div>
        <div class="col-md-6 text-center">
          <i class="far fa-smile"></i>
          <p>SATISFYING SERVICE</p>
        </div>
      </div>
    </div>

    <div id="about">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <h1 class="text-center"><strong>ABOUT<i class="fas fa-exclamation-circle"></i></strong></h1>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 offset-md-3">
            <p><strong>Becekin.id adalah</strong> Inovasi baru untuk mencuci motor menjadi lebih simpel dan mudah sesuai dengan moto kami yaitu <strong>Murah, Bersih, Gak Ribet.</strong> Tak perlu capek-capek ke tempat steam, motor andapun bisa bersih tanpa harus keluar rumah. <strong>Dengan booking jadwal melalui instagram atau whatsapp kami</strong> anda tinggal tunggu kami datang ke rumah anda. Anda tinggal duduk manis di rumah dan motor andapun bisa <strong>bersih dan kinclong</strong></p>
          </div>
        </div>
      </div>
    </div>

      <div class="row">
        <div class="container">
          <div class="col-md-12">
            <h1 class="text-center">CONTACT<i class="fas fa-phone"></i></h1>
          </div>
        </div>
      </div>
    <div id="contact">
      <div class="row">
        <div class="col-md-6 text-center">
          <a href="wa.me/6281280030575"><i class="fab fa-whatsapp"></i></a>
          <p>WHATSAPP</p>
          <a href="wa.me/6281280030575"><p>wa.me/6281280030575</p></a>
        </div>
        <div class="col-md-6 text-center">
          <a href="https://www.instagram.com/becekin.id/"><i class="fab fa-instagram"></i></a>
          <p>INSTAGRAM</p>
          <a href="https://www.instagram.com/becekin.id/"<p>@becekin.id</p></a>
        </div>
      </div>
    </div>
    
    



    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js" integrity="sha512-0QbL0ph8Tc8g5bLhfVzSqxe9GERORsKhIn1IrpxDAgUsbBGz/V7iSav2zzW325XGd1OMLdL4UiqRJj702IeqnQ==" crossorigin="anonymous"></script>
    <script>
      $('.nav-link').click(function(e){
        let tujuan = $(e.target).attr('href');

        $('html, body').animate({
          scrollTop: $(tujuan).offset().top - 500
        }, 650, 'easeInOutExpo');
      });
      e.preventDefault();
    </script>

    <!-- Option 2: jQuery, Popper.js, and Bootstrap JS
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
    -->
  </body>
</html>
