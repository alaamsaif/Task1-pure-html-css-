<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="task.css">
    <script src="task.js"></script>
    <title>Demagh Tanya</title>
    <!--google fonts-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&family=Varela+Round&family=Work+Sans:wght@400;500&display=swap"
        rel="stylesheet">
    <!-- Load icon library -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <!--fontawesome-->
    <script src="https://kit.fontawesome.com/7aee4bb87a.js" crossorigin="anonymous"></script>

</head>

<body>
    <header>
        <nav id="largeScreenNavbar">
            <div class="nav-conatiner">
                <div>
                    <div>
                        <img id="Etisalat_Logo" src="assets\Etisalat_Logo.png" alt="Etisalat_Logo">
                    </div>
                    <ul>
                        <li> <a>Plans and Services </a></li>
                        <li> <a>shop</a></li>
                        <li> <a>help</a></li>
                    </ul>
                </div>
                <div class="search-bar">
                    <div class="search-box">
                        <input type="search" id="search" placeholder="Search" />
                        <button type="submit"><i class="fa fa-search"></i></button>
                    </div>
                    <div class="cart-button">
                        <i class="fa fa-shopping-cart"></i>
                    </div>
                </div>
            </div>
        </nav>

        <!--small screen navbar-->
        <nav id="smallnavbar">
            <div class="smallnavbar-conatiner">
                <div class="smallnavbar-conatiner-text">
                    <div>
                        <span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776;</span>
                    </div>
                    <div>
                        <img id="Etisalat_Logo" src="assets\Etisalat_Logo.png" alt="Etisalat_Logo">
                    </div>
                </div>
                <div class="smallnavbar-conatiner-search-bar">
                    <div class="search-bar">
                        <div class="search-box">
                            <input type="search" id="search" placeholder="Search" />
                            <button type="submit"><i class="fa fa-search"></i></button>
                        </div>
                        <div class="cart-button">
                            <i class="fa fa-shopping-cart"></i>
                        </div>
                    </div>
                </div>

            </div>
        </nav>
        <!--side navbar-->
        <div id="mySidenav" class="sidenav">
            <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
            <a href="#">Plans and Services</a>
            <a href="#">shop</a>
            <a href="#">help</a>
        </div>



    </header>

    <section class="container hero-wrap">
        <div class="background">
            <img src="assets/Group-of-people-using-their-cell-phones.jpg">
            <div class="transbox">
                <div class="container-middle">
                    <img id="logo_light" src="assets/logo_light.png">
                    <div>
                        <h1 class="text-style4">Join Dmagh Tanya and get <span class="Biget-text">Double your
                                Qouta</span></h1>
                        <h3 class="text-style4">Choose your uniqe number and get started</h3>
                        <h5 class="text-style4">Continue usage on social and music applications for free.</h5>
                    </div>
                    <div class="hero-btn-group">
                        <button id="hero-left-button">Locate your nearest store</button>
                        <button id="hero-right-button">Subscribe NOW</button>
                    </div>

                </div>

            </div>
        </div>

    </section>


    <section class="container">
        <div class="btn-group">
            <button id="left-button">Recommended package</button>
            <button id="right-button">Main package</button>
        </div>
    </section>

    <section class="container internet-plans">
        <p class="text-style1">Pick your voice and internet plans</p>
        <div class="container-middle">
            <div class="internet-plans-firstBar">
                <div>
                    <p class="text-style2">Choose your bundle</p>
                </div>
                <div class="validator-box">
                    <p class="text-style3">Vaildtors</p>
                    <div class="validateors-group-btn">
                        <button id="validateors-group-leftbtn">30 Days</button>
                        <button id="validateors-group-rightbtn">90 Days</button>
                    </div>
                </div>
            </div>
            <div class="container-middle">
                <p class="text-style2">Data Bundle</p>
                <div class="Data-Bundle-circles">
                    <div class="circle1">
                        <p class="text-style2"> 1 GB</p>
                    </div>
                    <div class="circle2">
                        <p class="text-style2"> 1 GB</p>
                    </div>
                    <div class="circle2">
                        <p class="text-style2"> 1 GB</p>
                    </div>

                </div>
            </div>
            <div class="container-middle">
                <p class="text-style2">Voice Bundle</p>
                <div class="Data-Bundle-circles">
                    <div class="circle2">
                        <p class="text-style2"> 200 Min</p>
                    </div>
                    <div class="circle2">
                        <p class="text-style2"> 200 Min</p>
                    </div>
                    <div class="circle1">
                        <p class="text-style2"> 200 Min</p>
                    </div>

                </div>
            </div>
            <div class="container-middle">
                <div class="social-media-btngroup">
                    <a> <img src="assets/facebook-icon.png"></a>
                    <a> <img src="assets/twitter-icon.png"></a>
                    <a> <img src="assets/whatsup-icon.png"></a>
                    <a> <img src="assets/snapchat-icon.png"></a>
                </div>
                <div class="checkPrice">
                    <button id="checkPriceBtn">
                        Check price
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section class="container features">
        <img id="featuresImage" src="assets/Phones.jpg">
        <div class="features-content">
            <h1 class="features-title">Know the features</h1>
        </div>

        <div class="features-content-circles">
            <div>
                <div class="circle">
                </div>
                <p class="text-style4">Title</p>
            </div>
            <div>
                <div class="circle">
                </div>
                <p class="text-style4">Title</p>
            </div>
            <div>
                <div class="circle">
                </div>
                <p class="text-style4">Title</p>
            </div>
            <div>
                <div class="circle">
                </div>
                <p class="text-style4">Title</p>
            </div>
        </div>

    </section>

    <section class="container Explore">
        <h1 class="Explore-title">Explore possible Add ones</h1>
        <div class="container-middle">
            <button class="exploreBtns-data">
                Data
            </button>
        </div>
        <div class="gray-container">

            <div class="data-collections">
                <div class="rectangele">
                    <div class="small-circle">
                        <p>EGP XX</p>
                    </div>
                    <p class="rectangele-style"> 9GBS</p>


                </div>

                <div class="rectangele">
                    <div class="small-circle">
                        <p>EGP XX</p>
                    </div>
                    <p class="rectangele-style"> 9GBS</p>
                </div>

                <div class="rectangele">
                    <div class="small-circle">
                        <p>EGP XX</p>
                    </div>
                    <p class="rectangele-style"> 9GBS</p>
                </div>

                <div class="rectangele">
                    <div class="small-circle">
                        <p>EGP XX</p>
                    </div>
                    <p class="rectangele-style"> 9GBS</p>
                </div>

                <div class="rectangele">
                    <div class="small-circle">
                        <p>EGP XX</p>
                    </div>
                    <p class="rectangele-style"> 9GBS</p>
                </div>
            </div>

        </div>

        <div class="container-middle">
            <button class="exploreBtns-voice">
                Voice
            </button>
        </div>
        <div class="gray-container">
            <div class="voice-coolections">
                <div class="data-collections">
                    <div class="rectangele">
                        <div class="small-circle">
                            <p>EGP XX</p>
                        </div>
                        <p class="rectangele-style"> 9GBS</p>
                    </div>

                    <div class="rectangele">
                        <div class="small-circle">
                            <p>EGP XX</p>
                        </div>
                        <p class="rectangele-style"> 9GBS</p>
                    </div>
                </div>
                <div class="data-collections">

                    <div class="rectangele">
                        <div class="small-circle">
                            <p>EGP XX</p>
                        </div>
                        <p class="rectangele-style"> 9GBS</p>
                    </div>

                    <div class="rectangele">
                        <div class="small-circle">
                            <p>EGP XX</p>
                        </div>
                        <p class="rectangele-style"> 9GBS</p>
                    </div>
                </div>


            </div>
        </div>
    </section>

    <section class="container termsAndConditions">
        <img src="assets/process_bg.jpg">
        <div class="termsAndConditions-content">
            <h1 class="termsAndConditions-title">Terms & Conditions</h1>
            <ul class="condition-list">
                <li>Condition</li>
                <li>Condition</li>
                <li>Condition</li>
                <li>Condition</li>
            </ul>
        </div>
    </section>

    <section class="container offers">
        <div class="container-middle">
            <div class="offers-content">
                <h1>Get tha latest ofeers for Dmagh Tanya</h1>
                <h4>Get tha latest ofeers for Dmagh Tanya</h4>
                <div class="social-media-large-btn-group">
                    <a><img src="assets/facebook_icon_130940.png"></a>
                    <a><img src="assets/twitter.jpg"></a>
                    <a><img src="assets/youtube.png"></a>
                    <a><img src="assets/instgram.png"></a>
                </div>
            </div>

        </div>

    </section>

    <footer class="container footer">
        <div class="footer-content">
            <div class="footer-etislat-list">
                <h4>Etislat</h4>
                <ul>
                    <li>About us </li>
                    <li>Contact us</li>
                    <li>Find a store</li>
                    <li>Coverage map</li>
                </ul>
            </div>
            <div class="footer-etislatworld-list">
                <h4>Etislat World</h4>
                <ul>
                    <li>Bill and Recharge </li>
                    <li>Request your ADSL</li>
                    <li>Careers</li>
                    <li>Corporate Social Responsibility</li>
                </ul>
            </div>
            <div class="footer-follows-list">
                <h4>Follow us on</h4>
                <div class="socialIcons">
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-youtube"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-instagram"></i>
                </div>


            </div>
        </div>

    </footer>

</body>

</html>
