# tamarsNails
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tamar's Nails</title>
    <link rel="html" href="login.html">
    <link rel="stylesheet" href="styles.css" />
    <script src="login.js"></script>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.14.0/css/all.css" integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc" crossorigin="anonymous" />
</head>

<body>
    <!-- Navbar Section -->
    <nav class="navbar">
        <div class="navbar__container">
            <a href="#home" id="navbar__logo">Tamar's Nails</a>
            <div class="navbar__toggle" id="mobile-menu">
                <span class="bar"></span> <span class="bar"></span>
                <span class="bar"></span>
            </div>
            <ul class="navbar__menu">
                <li class="navbar__item">
                    <a href="#home" data-text="Home" class="navbar__links" id="home-page">Home</a>
                </li>
                <li class="navbar__item">
                    <a href="#costs" data-text="Costs" class="navbar__links" id="costs-page">Costs</a>
                </li>
                <li class="navbar__item">
                    <a href="#moreAboutUs" data-text="About Me" class="navbar__links" id="moreAboutMe-page">About Me</a>
                </li>
                <li class="navbar__item">
                    <a href="#footer" data-text="Footer" class="navbar__links" id="footer-page">
                        Footer
                    </a>
                </li>
                <li class="navbar__item">
                    <a href="https://www.instagram.com/tamars_nails_/?hl=en" data-text="Gallery" class="navbar__links" id="Gallery-Page">Gallery</a>
                </li>
                <!-- <li class="navbar__item">
                    <a href="http://127.0.0.1:5500/login.html?l" data-text="Log Out" class="navbar__links" id="logOut-page">Log Out</a>
                </li> -->
            </ul>
        </div>
    </nav>
    <!-- Hero Section -->
    <div class="hero" id="home">
        <div class="hero__container">
            <h1 class="hero__heading">Choose your <span>style</span></h1>
            <p class="hero__description">Unlimited Possibilities</p>
            </a>
        </div>
    </div>

    <!-- About Section -->
    <div class="main" id="costs">
        <div class="main__container">
            <div class="container">
                <div class="box">
                    <h2 class="name">Hand / Leg Manicure</h2>
                    <div class="circle"></div>
                    <img src="handNai.webp" class="project">
                    <div class="costInfo">
                        <h2 class="cost">cost: 30 ש"ח</h2>
                    </div>
                </div>
                <div class="box">
                    <h2 class="name">Anatomical Structure</h2>
                    <div class="circle"></div>
                    <img src="Ornaments and paintings.png" class="project">
                    <div class="costInfo">
                        <h2 class="cost">cost: 80 ש"ח</h2>
                    </div>
                </div>
                <div class="box">
                    <h2 class="name">Gel nail polish</h2>
                    <div class="circle"></div>
                    <img src="anatomicalStructure.png" class="project">
                    <div class="costInfo">
                        <h2 class="cost">cost: 170 ש"ח</h2>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>

    <!-- more of us Section -->
    <div class="moreAboutUs" id="moreAboutUs">
        <h1>More About Me</h1>
        <div class="more__wrapper">

            <div class="more__card">
                <h2>Interested?</h2>
                <p>call us!</p>
            </div>
            <div class="more__card">
                <h2>Proffesional Nail Designer</h2>
                <p>5 years of internship</p>
            </div>
            <nav class="last__more">
                <h2>Infinite Colors And Types</h2>
                <p>over 50 colors and Types</p>
            </nav>
        </div>
    </div>


    <!-- Footer Section -->
    <div class="footer__container" id="footer">
        <div class="footer__links">
            <div class="footer__link--wrapper">
                <div class="footer__link--items">
                    <h2>Social Media</h2>
                    <a href="https://www.instagram.com/tamars_nails_/?hl=en">instagram</a> <a href="/">Facebook</a>
                    <a href="/">Youtube</a> <a href="/">Twitter</a>
                </div>
            </div>
            <div class="footer__link--wrapper">
                <div class="footer__link--items">
                    <h2>Contact Us</h2>
                    <a>phone num: 0586948882</a>
                    <a>mail: yourmail@gmail.com</a>
                    <a href="https://api.whatsapp.com/send/?phone=972586948882&text&type=phone_number&app_absent=0">whatsapp</a>
                </div>
            </div>
        </div>
        <section class="social__media">
            <div class="social__media--wrap">
                <div class="footer__logo">
                    <a href="/" id="footer__logo">Tamar's Nails</a>
                </div>
                <p class="website__rights">© IBS 2022 All rights reserved</p>
                <div class="social__icons">
                    <a href="/" class="social__icon--link" target="_blank"><i class="fab fa-facebook"></i></a>
                    <a href="https://www.instagram.com/tamars_nails_/?hl=en" class="social__icon--link"><i class="fab fa-instagram"></i></a>
                    <a href="/" class="social__icon--link"><i class="fab fa-youtube"></i></a>
                    <a href="/" class="social__icon--link"><i class="fab fa-linkedin"></i></a>
                    <a href="/" class="social__icon--link"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
        </section>
    </div>
    <script src="app.js"></script>
    <script src="vanilla-tilt.min.js"></script>
    <script>
        VanillaTilt.init(document.querySelectorAll(".box"), {
            max: 25,
            speed: 100
        });
    </script>
</body>

</html>
