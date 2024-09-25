<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Design</title>
    <link rel="stylesheet" href="bootstrap-4.6.2-dist/css/bootstrap.css">
    <link rel="stylesheet" href="home.css">
    <link rel="stylesheet" href="fontawesome-free-5.10.1-web/css/all.css">
</head>
<body>
     <!--Start navbar-->

     <nav class="navbar navbar-expand-md bg-danger navbar-dark fixed-top">

        <a class="navbar-brand" href="home.html">GeekDev</a>
        <span class="navbar-text">Learn and Implement</span>

        <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#myMenu">
            <span class="navbar-toggler-icon"></span>

        </button>

        <div class="collapse navbar-collapse" id="myMenu">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#Home">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#Services">Services</a></li>
                <li class="nav-item"><a class="nav-link" href="#Courses">Courses</a></li>
                <li class="nav-item"><a class="nav-link" href="#Team">Team</a></li>
                <li class="nav-item"><a class="nav-link" href="#Contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    <!--End navbar-->

<!--Start jumbotron-->

<section id="Home">
    <header class="jumbotron backimage">

        <div class="text-center" style="margin-top: 130px">
            <h1 class="text-uppercase text-danger font-weight-bold">Welcome To Geek Developers</h1>
            <p class="font-italic font-weight-bold mb-4">Learn and Implement</p>

            <a href="#" class="btn btn-outline-danger">Hire Us</a>
            <a href="#" class="btn btn-outline-danger">Join Us</a>

        </div>


    </header>
</section>

<!--End jumbotron-->


 <!--Start Services-->

 <div class="container text-center border-bottom" id="Services">
    <h2>Our Services</h2>

    <div class="row mt-4">
        <div class="col-sm-4 mb-4">
            <a href="#">
                <i class="fab fa-android text-success fa-10x"></i>
            </a>
            <h2 class="mt-4">Android Application</h2>
        </div>

        <div class="col-sm-4 mb-4">
            <a href="#">
                <i class="fas fa-desktop text-primary fa-10x"></i>
            </a>
            <h2 class="mt-4">Web Application</h2>
        </div>

        <div class="col-sm-4 mb-4">
            <a href="#">
                <i class="fas fa-database text-info fa-10x"></i>
            </a>
            <h2 class="mt-4">Database</h2>
        </div>
    </div>
</div>
<!--End Services-->


<!--Start Courses-->

<div class="container pt-5" id="Courses">

    <h1 class="text-center">Our Courses</h1>


    <div class="row mt-4">
        <div class="col-lg-6 mb-4">
            <img class="img-fluid" src="images/course1.jpeg" alt="Alternate Text" />
        </div>

        <div class="col-lg-6">
            <h2 class="text-center mb-4">Learn Java Programming</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum ducimus, modi aut consequatur dolore ut praesentium esse recusandae at amet. Dolorem eius obcaecati ratione, quas laborum consequatur inventore vitae nostrum! Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos asperiores magnam culpa ullam. Quasi voluptatem eveniet sed velit tempore eaque adipisci magnam recusandae quaerat praesentium illo, animi, sit ratione quo.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente nisi atque ipsam optio, iusto explicabo odit suscipit delectus quis eum adipisci quo voluptas laboriosam quisquam sit, sint asperiores eius in!</p>
        </div>
    </div>




    <div class="row mt-4">

        <div class="col-lg-6">
            <h2 class="text-center mb-4">Real World Projects</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum ducimus, modi aut consequatur dolore ut praesentium esse recusandae at amet. Dolorem eius obcaecati ratione, quas laborum consequatur inventore vitae nostrum! Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos asperiores magnam culpa ullam. Quasi voluptatem eveniet sed velit tempore eaque adipisci magnam recusandae quaerat praesentium illo, animi, sit ratione quo.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente nisi atque ipsam optio, iusto explicabo odit suscipit delectus quis eum adipisci quo voluptas laboriosam quisquam sit, sint asperiores eius in!</p>
        </div>

        <div class="col-lg-6 mb-4">
            <img class="img-fluid" src="images/course2.jpeg" alt="Alternate Text" />
        </div>
    </div>
</div>
<!--End Courses-->



<!--Start Team-->

<div class="jumbotron bg-danger" id="Team">
    <div class="container">

        <h2 class="text-center text-white mb-4">Team</h2>

        <div class="row">

            <div class="col-lg-3 col-sm-6">
                <div class="card shadow-lg mb-3">
                    <div class="card-body text-center">
                        <img style="border-radius: 50%" src="images/avtar1.jpeg" alt="Alternate Text" />
                        <h4 class="card-title">Rahul Kumar</h4>
                        <p class="card-text">
                            Itaque illo explicabo voluptatum, saepe libero rerum, ad ducimus voluptas nesciunt debitis numquam.
                        </p>
                    </div>
                </div>
            </div>


            <div class="col-lg-3 col-sm-6">
                <div class="card shadow-lg mb-3">
                    <div class="card-body text-center">
                        <img style="border-radius: 50%" src="images/avtar2.jpeg" alt="Alternate Text" />
                        <h4 class="card-title">Rahul Kumar</h4>
                        <p class="card-text">
                            Itaque illo explicabo voluptatum, saepe libero rerum, ad ducimus voluptas nesciunt debitis numquam.
                        </p>
                    </div>
                </div>
            </div>


            <div class="col-lg-3 col-sm-6">
                <div class="card shadow-lg mb-3">
                    <div class="card-body text-center">
                        <img style="border-radius: 50%" src="images/avtar3.jpeg" alt="Alternate Text" />
                        <h4 class="card-title">Rahul Kumar</h4>
                        <p class="card-text">
                            Itaque illo explicabo voluptatum, saepe libero rerum, ad ducimus voluptas nesciunt debitis numquam.
                        </p>
                    </div>
                </div>
            </div>



            <div class="col-lg-3 col-sm-6">
                <div class="card shadow-lg mb-3">
                    <div class="card-body text-center">
                        <img style="border-radius: 50%" src="images/avtar4.jpeg" alt="Alternate Text" />
                        <h4 class="card-title">Rahul Kumar</h4>
                        <p class="card-text">
                            Itaque illo explicabo voluptatum, saepe libero rerum, ad ducimus voluptas nesciunt debitis numquam.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!--End Team-->


<!--Start Contact-->

<div class="container" id="Contact">
    <h2 class="text-center">Contact Us</h2>

    <div class="row">
        <div class="col-md-8">

            <form class="row g-3">
                <div class="col-md-12">
                    <label for="inputEmail4" class="form-label">Email</label>
                    <input type="email" class="form-control" id="inputEmail4">
                </div>
                <div class="col-md-12">
                    <label for="inputPassword4" class="form-label">Password</label>
                    <input type="password" class="form-control" id="inputPassword4">
                </div>
                <div class="col-12">
                    <label for="inputAddress" class="form-label">Address</label>
                    <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
                </div>
                <div class="col-12">
                    <label for="inputAddress2" class="form-label">Address 2</label>
                    <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
                </div>
                <div class="col-md-6">
                    <label for="inputCity" class="form-label">City</label>
                    <input type="text" class="form-control" id="inputCity">
                </div>



                <div class="col-12">
                    <button type="submit" class="btn btn-primary mt-5">Sign in</button>
                </div>
            </form>


        </div>

        <div class="col-md-4 text-center">

            <strong>Headquarter:</strong><br />
            Geeky Dev Pvt Ltd,<br />
            Harmu, Ranchi<br />
            Jharkhand - 834005<br />
            Phone: +00000000<br />
            www.geekyshows.com<br />


            <strong>Kolkata Branch:</strong><br />
            Geeky Dev Pvt Ltd,<br />
            Sec V, Kolkata<br />
            WB - 804002<br />
            Phone: +00000000<br />
            www.geekyshows.com<br />



        </div>

    </div>

</div>

<!--End Contact-->

<!--Start Footer-->

<footer class="container-fluid bg-dark text-white mt-5" style="border-top: solid 3px red">

    <div class="container">
        <div class="row py-3">

            <div class="col-md-6">

                <div>
                    <span>Follow Us:</span>
                    <a href="#"><i class="fab fa-facebook px-3"></i></a>
                    <a href="#"><i class="fab fa-twitter pr-3"></i></a>

                    <a href="#"><i class="fab fa-youtube pr-3"></i></a>
                    <a href="#"><i class="fab fa-google pr-3"></i></a>
                    <a href="#"><i class="fas fa-rss pr-3"></i></a>

                </div>

            </div>

            <div class="col-md-6 text-right">

                <small>Designed by <a href="#">GeekyShows</a> &copy; 2018.</small>


            </div>


        </div>


    </div>

</footer>

  <!--End Footer-->

<div class="scroll-top d-lg-none d-md-none d-sm-inline-block">
    <a class="btn btn-primary" href="#page-top"><i class="fa fa-chevron-up"></i></a>

</div>




    <script src="bootstrap-4.6.2-dist/jQuery/jQuery.js"></script>
    <script src="bootstrap-4.6.2-dist/js/bootstrap.js"></script>
</body>
</html>


CSS Code:

*
{
    margin: 0;
    padding: 0;
}
body {
}


.navbar-brand{
    font-family:Verdana;
    font-size:2em;
    font-weight:bold;
}

.navbar #myMenu ul li a{
    color:white;
}

.navbar #myMenu ul li a:hover{
    color:pink;
}

.backimage
{
    background-image:url(images/Banner.jpeg);
    background-size:cover;
    background-position:center center;
    background-repeat:no-repeat;
    min-height:70vh;
    margin-top: 74px;
}

.scroll-top
{

    position:fixed;
    bottom:2%;
    right:2%;
    width:50px;
    height:50px;
    
}

.scroll-top .btn{
    width:50px;
    height:50px;
    border-radius:50%;
    font-size:20px;


}
