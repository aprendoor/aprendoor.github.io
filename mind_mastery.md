<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Berkshire+Swash&family=Bitter&family=Chelsea+Market&family=Cinzel+Decorative:wght@900&family=Montserrat+Alternates:wght@500&family=Montserrat+Subrayada:wght@700&family=Montserrat:wght@500&family=Orbitron:wght@500&family=Righteous&family=Rubik&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/custom-bootstrap.css">
    <link rel="stylesheet" href="css/custom-style.css">
    <script src="../Aprendoor/js/lottie-player.js"></script>
    
    <title>Aprendoor</title>
</head>
<body>
    
    <nav class="navbar navbar-expand-sm navbar-light bg-light"> <!--Navigation bar-->
        <div class="container-fluid">
            <!-- <img src="media/anim-aprendoor.gif" alt=""> -->
          <!-- <a class="navbar-brand" href="#">Aprendoor</a> -->
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control mr-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav> <!--ENd of navigation bar-->


      <!--Main container-fluid-->
      <div class="container-fluid main-container ">
          <!--Slanted div-->
          <div class="container-fluid px-8 mind-mastery-color main-slanted-div">
            <svg class="mt-n2 wave" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="rgba(10, 255, 120,0.5)" fill-opacity="1" d="M0,64L30,53.3C60,43,120,21,180,37.3C240,53,300,107,360,112C420,117,480,75,540,85.3C600,96,660,160,720,176C780,192,840,160,900,128C960,96,1020,64,1080,85.3C1140,107,1200,181,1260,213.3C1320,245,1380,235,1410,229.3L1440,224L1440,0L1410,0C1380,0,1320,0,1260,0C1200,0,1140,0,1080,0C1020,0,960,0,900,0C840,0,780,0,720,0C660,0,600,0,540,0C480,0,420,0,360,0C300,0,240,0,180,0C120,0,60,0,30,0L0,0Z"></path></svg>
            
            <h1>Mind Mastery</h1>
            <p>Welcome to your mind mastery palace, here we help ypou to unlock your true potential by cleaning the clutter and sharing some of the wises advises from the experts</p>
          </div>
          <!--End of Slanted div-->

          <!--Catagory block-->
          <div class="container-fluid p-5 px-8 mm-content-container"> 
              <div class="row px-8 ">
                <div class="card">
                  <div class="card-header">
                    <h6 style="display: inline;">Last update 2 days ago</h6>
                    <h6 class="card-category-flat">Total articles 101</h6>
                  </div>
                  <div class="card-body ">
                    <div class="container">
                      <div class="row ">
                        <div class="col-lg-3 content-discription-block">
                          <img src="/assets/img/yoga.png" alt="" style="width: 200px ; height: 200px;">
                        </div>
                        <div class="col content-discription-block">
                          <h4 class="card-title">Meditation</h4>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                        </div>
                    </div>
                  </div>                    
                  </div>
                </div>
                <div class="card">
                  <div class="card-header">
                    <h6 style="display: inline;">Last update 2 days ago</h6>
                    <h6 class="card-category-flat">Total articles 101</h6>
                  </div>
                  <div class="card-body ">
                    <div class="container">
                      <div class="row ">
                        <div class="col-lg-3 content-discription-block">
                          <img src="/assets/img/philosopher.png" alt="" style="width: 200px ; height: 200px;">
                        </div>
                        <div class="col content-discription-block">
                          <h4 class="card-title">satoicism</h4>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                        </div>
                    </div>
                  </div>                    
                  </div>
                </div>
                  <!-- <div class="col content-discription-block">
                    <div class="card card-category" style="width: 22rem;">
                      <img src="../aprendoor.github.io/assets/img/yoga.png" class="card-img-top mt-3" alt="..." style="height:200;width: 200px;">
                      <div class="card-body">
                        <h4 class="card-title text-danger ">Meditation</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                     
                  </div>

                  <div class="col content-discription-block">
                    <div class="card card-category" style="width: 22rem;">
                      <img src="../aprendoor.github.io/assets/img/philosopher.png" class="card-img-top" alt="..." style="height:220;width: 220px;">
                      <div class="card-body">
                        <h4 class="card-title">Stoicism</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                    
                  </div>                
                  
                  <div class="col content-discription-block">
                    <div class="card card-category" style="width: 30rem;">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h4 class="card-title">Routines For Humans</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                    
                  </div>

                  <div class="col content-discription-block">
                    <div class="card card-category" style="width: 30rem;">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h4 class="card-title">Learning To Learn</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                    
                  </div>

                  <div class="col content-discription-block">
                    <div class="card card-category" style="width: 30rem;">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h4 class="card-title">Productivity Booster</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                    
                  </div>

                  <div class="col content-discription-block">
                    <div class="card card-category bg-warning" style="width: 30rem;">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h4 class="card-title">How To Stay Healthy</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                    
                  </div>

                  <div class="col content-discription-block">
                    <div class="card card-category" style="width: 30rem;">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h4 class="card-title">Let's Talk</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                    
                  </div>

                  <div class="col content-discription-block">
                    <div class="card card-category" style="width: 30rem;">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h4 class="card-title">Books Tips & Articles</h4>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-success">Go somewhere</a>
                      </div>
                    </div>                    
                  </div>                  -->
                  
              </div> 
              <div class="divider-mid">                    
              </div>
          </div> 
          <!--End of catagory Block-->

          <!--Featured articles section-->
          <div class="container mt-2 p-8 ">
            
            <h1 class="text-center">Recent articles</h1>
            <div class="card">
              <div class="card-header">
                Featured
              </div>
              <div class="card-body">
                <h4 class="card-title">Special title treatment</h4>
                <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                <a href="#" class="btn btn-success">Go somewhere</a>
              </div>
            </div>
            <div class="card">
              <div class="card-header">
                Featured
              </div>
              <div class="card-body">
                <h4 class="card-title">Special title treatment</h4>
                <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                <a href="#" class="btn btn-success">Go somewhere</a>
              </div>
            </div>
            <div class="card">
              <div class="card-header">
                Featured
              </div>
              <div class="card-body">
                <h4 class="card-title">Special title treatment</h4>
                <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                <a href="#" class="btn btn-success">Go somewhere</a>
              </div>
            </div>
            <div class="card">
              <div class="card-header">
                Featured
              </div>
              <div class="card-body">
                <h4 class="card-title">Special title treatment</h4>
                <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                <a href="#" class="btn btn-success">Go somewhere</a>
              </div>
            </div>
            <div class="card">
              <div class="card-header">
                Featured
              </div>
              <div class="card-body">
                <h4 class="card-title">Special title treatment</h4>
                <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                <a href="#" class="btn btn-success">Go somewhere</a>
              </div>
            </div>
          </div>          
      </div>
      <!--End of Main container-fluid-->

    <!--Footer Area-->
    <!--End of Footer Area-->

    <!--Bootstrap and main Js -->
    <script src="js/main.js"></script>
    <script src="js/bootstrap.bundle.js"></script>
</body>
</html>