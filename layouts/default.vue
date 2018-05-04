<template>
    <div>

        <!--<header>-->

            <!--<nav class="navbar navbar-expand-lg navbar-dark brown darken-3">-->
                <!--<div class="container">-->
                    <!--<a class="navbar-brand" href="#">-->
                        <!--<div class="logo">-->
                            <!--<div class="bold">The lost Egyptian</div>-->
                            <!--<div class="small">Amun's Throne</div>-->
                        <!--</div>-->
                    <!--</a>-->
                    <!--<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">-->
                        <!--<span class="navbar-toggler-icon"></span>-->
                    <!--</button>-->
                    <!--<div class="collapse navbar-collapse" id="navbarSupportedContent">-->
                        <!--<ul class="navbar-nav mr-auto">-->
                            <!--<li class="nav-item active">-->
                                <!--<a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>-->
                            <!--</li>-->
                            <!--<li class="nav-item">-->
                                <!--<a class="nav-link" href="#">Link</a>-->
                            <!--</li>-->
                            <!--<li class="nav-item">-->
                                <!--<a class="nav-link" href="#">Profile</a>-->
                            <!--</li>-->
                        <!--</ul>-->
                    <!--</div>-->
                <!--</div>-->
            <!--</nav>-->

            <!--<div class="view intro-2">-->
                <!--<div class="full-bg-img">-->
                    <!--<div class="mask rgba-black-strong flex-center">-->
                        <!--<div class="container">-->
                            <!--<div class="white-text text-center wow fadeInUp">-->
                                <!--<h2>This Navbar isn't fixed</h2>-->
                                <!--<h5>When you scroll down it will disappear</h5>-->
                                <!--<br>-->
                                <!--<p>Full page intro with background image will be always displayed in full screen mode, regardless of device </p>-->
                            <!--</div>-->
                        <!--</div>-->
                    <!--</div>-->
                <!--</div>-->
            <!--</div>-->

        <!--</header>-->
        <!--&lt;!&ndash;Main Navigation&ndash;&gt;-->

        <!--Main Layout-->
        <main>
            <nuxt/>
        </main>
        <!--Main Layout-->

        <!--Footer-->
        <footer class="page-footer font-small brown-darken-3 pt-0">

            <!--Footer Links-->
            <div class="container">

                <!--First row-->
                <div class="row">

                    <!--First column-->
                    <div class="col-md-12 py-5">

                        <div class="mb-5 flex-center">

                            <h3 class="bolder">GameBreakers</h3>

                        </div>
                    </div>
                    <!--/First column-->
                </div>
                <!--/First row-->
            </div>
            <!--/Footer Links-->

            <!--Copyright-->
            <div class="footer-copyright py-3 text-center">
                © 2018 Copyright: GameBreakers,
                <a href="https://www.bib.de/de/standorte/paderborn.html"> bib International College</a>
                <a class="github" href="https://github.com/creazy231/thelostegyptain" target="_blank"><i class="fa fa-github"></i></a>
            </div>
            <!--/Copyright-->

        </footer>
        <!--/Footer-->

        <script src="js/jquery-3.2.1.min.js"></script>
        <script src="js/popper.min.js"></script>
        <script src="js/bootstrap.min.js"></script>
        <script src="js/mdb.min.js"></script>
    </div>
</template>

<style lang="scss" scoped>
    .view {
        background: url("https://mdbootstrap.com/img/Photos/Others/img (51).jpg")no-repeat center center;
        background-size: cover;
    }
    @media (min-width: 768px) {
        .view {
            overflow: visible;
            margin-top: -56px;
        }
    }
    .navbar {
        z-index: 1;

        .logo {
            display: flex;
            flex-direction: column;
            align-items: center;

            .bold {
                font-weight: 500;
            }

            .small {
                line-height: 10px;
                font-size: 14px;
            }
        }
    }

    .container {
        text-align: left;
    }

    footer {
        position: relative;

        .bolder {
            font-weight: 700;
        }

        .github {
            position: absolute;
            bottom: 15px;
            right: 15px;
        }
    }
</style>
