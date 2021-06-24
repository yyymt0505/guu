# guu
<!DOCTYPE html>
<html lang="ja" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>デジタルデータ基礎 - サンプルHTML</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="carousel.css">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.bundle.min.js"></script>
  </head>

  <body>
    <header id="header">
      <nav class="navbar navbar-expand-lg navbar-dark fixed-top bg-dark"><!-- ナビゲーション始まり -->
        <span class="navbar-brand">デジタルデータ基礎innu</span>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active"><a class="nav-link" href="#">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="#small">小見出し</a></li>
            <li class="nav-item"><a class="nav-link" href="#large1">大見出し1</a></li>
            <li class="nav-item"><a class="nav-link" href="#large2">大見出し2</a></li>
          </ul>
          <form class="form-inline mt-2 mt-md-0"><!-- 検索窓 -->
            <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
          </form>
        </div>
      </nav><!-- ナビゲーション終わり -->
    </header>

    <main role="main">
      <div id="myCarousel" class="carousel slide mb-5" data-ride="carousel"><!-- カルーセル始まり -->
        <ol class="carousel-indicators">
          <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
          <li data-target="#myCarousel" data-slide-to="1"></li>
          <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active"><!-- カルーセル要素1始まり -->
            <img src="https://via.placeholder.com/1.png/555" width="100%" height="100%">
            <div class="container">
              <section class="carousel-caption text-left">
                <h1>カルーセル1</h1>
                <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                <p><a class="btn btn-lg btn-success" href="#" role="button">View details &raquo;</a></p>
              </section>
            </div>
          </div><!-- カルーセル要素1終わり -->
          <div class="carousel-item"><!-- カルーセル要素2始まり -->
            <img src="https://via.placeholder.com/1.png/666" width="100%" height="100%">
            <div class="container">
              <section class="carousel-caption">
                <h1>カルーセル見出し2</h1>
                <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                <p><a class="btn btn-lg btn-success" href="#" role="button">View details &raquo;</a></p>
              </section>
            </div>
          </div><!-- カルーセル要素2終わり -->
          <div class="carousel-item"><!-- カルーセル要素3始まり -->
            <img src="https://via.placeholder.com/1.png/777" width="100%" height="100%">
            <div class="container">
              <section class="carousel-caption text-right">
                <h1>カルーセル見出し3</h1>
                <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                <p><a class="btn btn-lg btn-success" href="#" role="button">View details &raquo;</a></p>
              </section>
            </div>
          </div><!-- カルーセル要素3終わり -->
        </div>
        <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span><!-- カルーセルの左矢印 -->
        </a>
        <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span><!-- カルーセルの右矢印 -->
        </a>
      </div><!-- カルーセル終わり -->

      <article class="container marketing">
        <div id="small" class="row"><!-- 3つのカラム始まり -->
          <section class="col-lg-4 text-center">
            <img src="https://via.placeholder.com/140.png/777" width="140" height="140" class="rounded-circle mb-2">
            <h2>小見出し1</h2>
            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod. Nullam id dolor id nibh ultricies vehicula ut id elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.</p>
            <p><a class="btn btn-outline-success bg-dark" href="#" role="button">View details &raquo;</a></p>
          </section>
          <section class="col-lg-4 text-center">
            <img src="https://via.placeholder.com/140.png/666" width="140" height="140" class="rounded-circle mb-2">
            <h2>小見出し2</h2>
            <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
            <p><a class="btn btn-outline-success bg-dark" href="#" role="button">View details &raquo;</a></p>
          </section>
          <section class="col-lg-4 text-center">
            <img src="https://via.placeholder.com/140.png/555" width="140" height="140" class="rounded-circle mb-2">
            <h2>小見出し3</h2>
            <p>Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
            <p><a class="btn btn-outline-success bg-dark" href="#" role="button">View details &raquo;</a></p>
          </section>
        </div><!-- 3つのカラム終わり -->

        <hr class="featurette-divider"><!-- 水平線 -->

        <section id="large1" class="row featurette">
          <div class="col-md-7">
            <h2 class="featurette-heading">大見出し1</h2>
            <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
          </div>
          <img src="https://via.placeholder.com/500.png/555" width="500" height="500" class="bd-placeholder-img-lg featurette-image img-fluid mx-auto col-md-5" >
        </section>

        <hr class="featurette-divider"><!-- 水平線 -->

        <section id="large2" class="row featurette">
          <div class="col-md-7 order-md-2">
            <h2 class="featurette-heading">大見出し2</h2>
            <p class="lead">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
          </div>
          <img src="https://via.placeholder.com/500.png/555" width="500" height="500" class="bd-placeholder-img-lg featurette-image img-fluid mx-auto col-md-5 order-md-1" >
        </section>

        <hr class="featurette-divider mb-5"><!-- 水平線 -->
      </article>
    </main>

    <footer class="container">
      <p class="float-right"><a class="btn btn-outline-success" href="#header" role="button">Back To Top</a></p>
      <p>&copy; 2017-<script type="text/javascript">document.write(new Date().getFullYear())</script> Company, Inc.</p>
    </footer>
  </body>
</html>
