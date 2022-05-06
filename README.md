# portfolio2

<!doctype html>
<html lang="ja">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="css/custom.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&family=Potta+One&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/4e4b3bbd20.js" crossorigin="anonymous"></script>

    <title>Coporatesite</title>
  </head>
  <body>
  <header>
    <div class="top-img">
    <div class="top-text">
      <h1>Corporatesote</h1>
      <p>会社情報を伝えるサイトです。</p>
    </div>
  </div>
  </header>
  <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><h3>Corporate Site</h3></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end "id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#feature">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#service">Service</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#infomation">Infomation</a>
          </li>
        </ul>
      </div>
  </nav>
  
  <div class="night-sky" id="feature">
    <h2>Feature</h2>
    <p>弊社は株式会社○○です。<br>
      ここに企業理念が入ります。
    </p>
  </div>
  <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="img/slide01.png" class="d-block w-100 img-fluis" alt="firstslide">
        <div class="carousel-caption d-none d-md-block">
          <h5>1枚目の画像です。</h5>
          <p>説明が入ります。</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="img/slide02.png" class="d-block w-100 img-fluis" alt="secondslide">
        <div class="carousel-caption d-none d-md-block">
          <h5>2枚目のがぞうです。</h5>
          <p>説明が入ります。</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="img/slide03.png" class="d-block w-100 img-fluis" alt="thirdslide">
        <div class="carousel-caption d-none d-md-block">
          <h5>3枚目が入ります。</h5>
          <p>説明が入ります。</p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

  <!-- Service -->
  <div class="service-list" id="service">
    <h2>Service</h2>
    <div class="container">
      <div class="row service-description">
        <div class="col-md-6">
          <img src="img/service01.jpg" alt="service01" class="img-fluid">
          </div>
          <div class="col-md-6">
          <h3>サービス1</h3>
          <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
          <a href="https://getbootstrap.jp/docs/5.0/components/buttons/"><button type="button" class="btn btn-light">詳細</button></a>
        </div>
      </div>

      <div class="row service-description">
        <div class="col-md-6 order-md-2">
          <img src="img/service02.jpg" alt="service02" class="img-fluid">
        </div>
        <div class="col-md-6 order-md-1">
          <h3>サービス2</h3>
        <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        <a href="https://getbootstrap.jp/docs/5.0/components/buttons/"><button type="button" class="btn btn-light">詳細</button></a>
      </div>
      </div>
        
    <div class="row service-description">
      <div class="col-md-6">
        <img src="img/service03.jpg" alt="service03" class="img-fluid">
        </div>
        <div class="col-md-6">
        <h3>サービス3</h3>
        <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        <a href="https://getbootstrap.jp/docs/5.0/components/buttons/"><button type="button" class="btn btn-light">詳細</button></a>
      </div>
    </div>
    </div>
        </div>


      <div class="night-sky" id="infomation">
        <h2>Infomation</h2>
        <div class="container">
          <div class="row">
            <div class="col-md-4">
              <div class="info">
                <i class="fas fa-user fa-4x"></i>
                <p>ここに商品説明が入ります。<br>ここに商品説明が入ります。</p>
              </div>
            </div>
            <div class="col-md-4">
              <div class="info">
                <i class="fas fa-project-diagram fa-4x"></i>
                <p>ここに商品説明が入ります。<br>ここに商品説明が入ります。</p></div>
            </div>
            <div class="col-md-4">
              <div class="info">
                <i class="fas fa-laptop-code fa-4x"></i>
                <p>ここに商品説明が入ります。<br>ここに商品説明が入ります。</p></div>
            </div>
          </div>
        </div>
      </div>
    <!-- フッター -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <ul>
              <li><a href="#">Home</a></li>
              <li><a href="#feature">Feature</a></li>
              <li><a href="#service">Service</a></li>
              <li><a href="#infomation">Infomation</a></li>
            </ul>
          </div>
          <div class="col-md-4">
            <ul>
              <li><a href="#">サービス1</a></li>
              <li><a href="#">サービス2</a></li>
              <li><a href="#">サービス3</a></li>
            </ul>
          </div>
          <div class="col-md-4">
            <ul>
              <li><a href="#">リンク1</a></li>
              <li><a href="#">リンク2</a></li>
              <li><a href="#">リンク3</a></li>
            </ul>
          </div>
        </div>
      </div>
      <p>&copy;2022 Corpratesite</p>
    </footer>
              
              
              
         
      
          
          
      

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
  </body>
</html>
