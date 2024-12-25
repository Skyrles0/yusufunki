<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carousel with Overlay Text</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
    <style>
         .carousel-caption-custom {
            position: absolute;
            bottom: 20px; /* Resmin altına hizalar */
            left: 50%;
            transform: translateX(-50%);
            background: rgba(0, 0, 0, 0.5); /* Saydam siyah arka plan */
            color: white;
            padding: 10px 20px;
            border-radius: 8px;
            text-align: center;
        }

        .card-img-top{
            width: 293px;
            height: 200px;
        }

        /* Hover effect for images */
        .image-hover-wrapper {
            position: relative;
            overflow: hidden;
            width: 200px; /* İstediğiniz genişlik */
            height: 150px; /* İstediğiniz yükseklik */
            margin: 5px;
        }

        .image-hover-wrapper img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: grayscale(100%) brightness(50%); /* Siyah filtre ve karartma */
            transition: filter 0.3s ease; /* Hover geçişi için animasyon */
        }

        .image-hover-wrapper img:hover {
            filter: none; /* Hover ile filtreyi kaldırır */
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light fixed-top "style="opacity: 0.9 bg-light>
        <a class="navbar-brand href="#">
            <img src="resimler/f16 patch.jpg" alt="Site Logo" style="height: 40px;">
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Dropdown
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">PHP</a>
                        <a class="dropdown-item" href="#">ASP</a>
                        <a class="dropdown-item" href="#">HTML</a>
                        <div class="dropdown-divider"></div>
                    </div>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#">Disabled</a>
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
            </form>
        </div>
    </nav>

    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="d-block w-100" src="resimler/f15.jpg" alt="First slide" style="object-fit: cover; height: 500px;">
                <div class="carousel-caption-custom">F-15 Eagle - Hava Üstünlüğü Uçağı</div>
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="resimler/f18.jpeg" alt="Second slide" style="object-fit: cover; height: 500px;">
                <div class="carousel-caption-custom">F-18 Hornet - Çok Amaçlı Taarruz Uçağı</div>
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="resimler/279810.jpg" alt="Third slide" style="object-fit: cover; height: 500px;">
                <div class="carousel-caption-custom">F-16 Fighting Falcon - Dünyanın En İyi 4. Nesil</div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>

   
<div class="d-flex justify-content-around my-4 align-items-stretch">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="resimler/html5.png" alt="Card image cap">
        <div class="card-body d-flex flex-column">
            <p class="card-text">HTML 5 hakkında kısa bir bilgi.</p>
        </div>
    </div>
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="resimler/php.png" alt="Card image cap">
        <div class="card-body d-flex flex-column">
            <p class="card-text">PHP hakkında kısa bir bilgi.</p>  
        </div>
    </div>
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="resimler/asp.png" alt="Card image cap">
        <div class="card-body d-flex flex-column">
            <p class="card-text">ASP.NET hakkında kısa bir bilgi.</p>  
        </div>
    </div>
</div>
    <div class="container mt-2">
        <div class="row">
            <div class="col-12 col-md-12">
                <div class="card">
                    <div class="card-body">
                        <h2>Benzersiz Web Tasarım Hizmeti</h2>
                        <hr>
                        <p>
                            JarvisWeb,2008 yılından bu yana ihtisasını bilgisayar programcılığı ve
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="d-flex justify-content-around my-4">
        <div class="image-hover-wrapper">
            <img src="resimler/f16.jpg" class="hover-effect" alt="F-16">
        </div>
        <div class="image-hover-wrapper">
            <img src="resimler/f15.jpg" class="hover-effect" alt="F-15">
        </div>
        <div class="image-hover-wrapper">
            <img src="resimler/f18.jpeg" class="hover-effect" alt="F-18">
        </div>
        <div class="image-hover-wrapper">
            <img src="resimler/279810.jpg" class="hover-effect" alt="F-35">
        </div>
    </div>
    
</body>
</html>
