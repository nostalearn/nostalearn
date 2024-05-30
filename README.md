
```html
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- CSRF Token -->
    <meta name="csrf-token" content="7rFsHvU32gouERXDgDIvyo6xCkhRooRPxG6AL0DW">
    <meta name="description" content="Online Application Portal for Moi University. You can quickly and conveniently submit your admission application online and keep track of the application progress until you can download and print your admission letter.">
    <meta name="keywords" content="university,college,campus,best university in kenya,top university in kenya,best university,top university">
    <title>Login - Moi University</title>
    <style>
        #load {
            width: 100%;
            height: 100%;
            position: fixed;
            z-index: 9999;
            background: url("/storage/company/loading.gif") no-repeat center center rgba(0, 0, 0, 0.5)
        }

        p {
            width: 100% !important;
            word-wrap: break-word;
        }
    </style>
</head>

<body>
    <div id="app" class="">
        <nav class="navbar navbar-expand-md navbar-light bg-theme-color shadow-sm fixed-top p-0">
            <div class="container">
                <!-- Branding Image -->
                <div class="row navbar-brand2">
                    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 navbar-brand2-image ml-0 pl-0 text-center">
                        <a href="/" class="ml-0 pl-1" style="background-color:unset !important">
                            <img src="file:///C:/Users/NEW%20GEN/Desktop/moi%20logo.jpg" class="logo-home" alt="logo">
                        </a>
                    </div>
                </div>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <!-- Left Side Of Navbar -->
                    <ul class="navbar-nav mr-auto"></ul>
                    <!-- Right Side Of Navbar -->
                    <ul class="navbar-nav ml-auto">
                        <!-- Authentication Links -->
                        <li class="nav-item">
                            <a class="nav-link" href="/">
                                <span class="d-none d-md-block d-lg-none"><i class="fas fa-home"></i> </span>
                                <span class="d-md-none d-lg-block">Home</span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="/ssp/register">Apply</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="/our-programmes">Our Programmes</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="/enquiry">Enquiry</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="/ssp/admission-letter">Admission Letter</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link active-tab" href="/login" title="Login">
                                <span class="d-none d-md-block d-lg-none"><i class="fas fa-sign-in-alt"></i> </span>
                                <span class="d-md-none d-lg-block">Login / Create Account</span>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <div class="container-fluid" style="margin-top:12vh !important;min-height:75vh">
            <div class="container" style="max-width:75%">
                <div class="alert alert-danger notification">
                    <button type="button" class="close" data-dismiss="alert" aria-hidden="true">&times;</button>
                    <i class="fas fa-exclamation-circle"></i> The index number does not exist in our records. Please try again. If the error persists and you have already received a letter from KUCCPS, kindly contact us for help.
                </div>
            </div>
            <div class="row pt-0 mt-0">
                <div class="col-xs-6 col-sm-6 col-md-6 col-lg-6 mb-3">
                    <div class="panel border-theme-color customPanel">
                        <div class="panel-heading bg-theme-color text-center d-flex justify-content-center pl-2 pr-2">
                            Self Sponsored Students Login
                        </div>
                        <div class="panel-body pb-2" style="min-height:295px">
                            <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css" />
                            <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
                            <style>
                                form i {
                                    cursor: pointer;
                                }
                            </style>
                            <form class="form-horizontal" action="https://admissions.mu.ac.ke/ssp/log_in" method="POST" autocomplete="off">
                                <input type="hidden" name="_token" value="7rFsHvU32gouERXDgDIvyo6xCkhRooRPxG6AL0DW">
                                <div class="container-fluid div-table">
                                    <div class="text-center">
                                        <br><br><br>
                                        <div class="alert alert-info">
                                            Do You have an account with the Moi University Application Portal? If yes, <strong><a href="/signin" class="btn btn-sm btn-success">Click here to Login</a></strong> If not, <strong><a href="/ssp/register" class="btn btn-sm btn-danger"> Click here to Create an Account</a></strong>
                                        </div>
                                        <br><br><br><br>
                                    </div>
                                    <div class="row">
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 lbl">
                                            Email
                                        </div>
                                        <div class="col-xs-12 col-sm-6 col-md-8 col-lg-8 value">
                                            <input id="email" class="form-control" name="email" value="" required autofocus>
                                        </div>
                                    </div>
                                    <div class="row">
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 lbl">
                                            Password
                                        </div>
                                        <div class="col-xs-11 col-sm-5 col-md-7 col-lg-7 value">
                                            <input class="form-control" type="password" name="password" id="password" required />
                                        </div>
                                        <div class="col-xs-1 col-sm-1 col-md-1 col-lg-1 mt-2 -mr-2">
                                            <span class="input-group"><i class="bi bi-eye-slash" id="togglePassword"></i></span>
                                        </div>
                                    </div>
                                    <div class="row">
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 lbl">
                                            Security Stamp
                                        </div>
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 value">
                                            <h5 style="color: red;">20 + 26 =</h5>
                                        </div>
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 value">
                                            <input type="number" name="captcha_results" class="form-control" required>
                                            <input type="hidden" name='num1' value='20'>
                                            <input type="hidden" name='num2' value='26'>
                                        </div>
                                    </div>
                                </div>
                                <div class="form-group text-center mt-2">
                                    <div class="checkbox">
                                        <label>
                                            <input type="checkbox" name="remember"> Remember Me
                                        </label>
                                    </div>
                                </div>
                                <div class="rowx text-center">
                                    <button type="submit" class="btn btn-primary">
                                        <i class="fas fa-check"></i> Login
                                    </button>
                                </div>
                                <div class="rowx text-center mt-2 d-flex justify-content-between">
                                    <a class="btn btn-link" href="/ssp/password/reset-link-form">
                                        Forgot Your Password?
                                    </a>
                                </div>
                            </form>
                            <script>
                                window.onload = function set_variables() {
                                    document.getElementById("captcha_results").value = "";
                                }
                                const togglePassword = document.querySelector('#togglePassword');
                                const password = document.querySelector('#password');
                                togglePassword.addEventListener('click', () => {
                                    const type = password.getAttribute('type') === 'password' ? 'text' : 'password';
                                    password.setAttribute('type', type);
                                    this.classList.toggle('bi-eye');
                                });


                            </script>
                        </div>
                    </div>
                </div>
                <div class="col-xs-6 col-sm-6 col-md-6 col-lg-6">
                    <div class="panel border-theme-color customPanel">
                        <div class="panel-heading bg-theme-color text-center d-flex justify-content-center pl-2 pr-2">
                            Government Sponsored Students Login (KUCCPS)
                        </div>
                        <div class="panel-body pb-2" style="min-height:295px">
                            <i class="fas fa-info-circle"></i> Please ensure you have already received a letter from KUCCPS which indicates you have been granted an offer in Moi University
                            <br><br>
                            <i class="fas fa-info-circle"></i> Please key in your Index No in this format : 2950000000/2021
                            <form class="form-horizontal mt-2" action="https://admissions.mu.ac.ke/gsp/login" method="POST" autocomplete="off">
                                <input type="hidden" name="_token" value="7rFsHvU32gouERXDgDIvyo6xCkhRooRPxG6AL0DW">
                                <div class="container-fluid div-table mb-3">
                                    <div class="row">
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 lbl">
                                            KCSE Index No
                                        </div>
                                        <div class="col-xs-12 col-sm-6 col-md-8 col-lg-8 value">
                                            <input id="index_number" class="form-control" name="index_number" value="" placeholder="e.g 295000000/2021" required autofocus>
                                        </div>
                                    </div>
                                    <div class="row">
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 lbl">
                                            Security Stamp
                                        </div>
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 value">
                                            <h5 style="color: red;">21 + 26 =</h5>
                                        </div>
                                        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 value">
                                            <input type="number" name="captcha_results" class="form-control" required>
                                            <input type="hidden" name='num1' value='21'>
                                            <input type="hidden" name='num2' value='26'>
                                        </div>
                                    </div>
                                </div>
                                <div class="rowx text-center">
                                    <button type="submit" class="btn btn-primary">
                                        <i class="fas fa-check"></i> Login
                                    </button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <hr>
        <div class="container-fluid footer mt-3 pt-4 pb-0 bg-theme-color d-flex justify-content-center">
            <div class="m-0 p-0">
                <p class="text-center m-0">
                    <h6>&copy 2024 All rights reserved Moi University</h6>
                </p>
                <p class="text-center m-0"><i class="fas fa-code"></i> Developed by <a href="http://www.dsl.ke" style="color:white">DSL Systems & Solutions Ltd.</a></p>
            </div>
        </div>
    </div>
    <script>
        document.onreadystatechange = function() {
            var state = document.readyState;
            if (state == 'complete') {
                setTimeout(function() {
                    document.getElementById('interactive');
                    document.getElementById('load').style.visibility = "hidden";
                    document.getElementById('app').style.visibility = "visible";
                }, 1000);
            }
        }

        function toggleSidebar() {
            var sidebarActions = document.getElementById('rootWrapper');
            sidebarActions.classList.toggle("toggled");
        }
        var recaptchaResponse = '';
        var correctCaptcha = function(response) {
            recaptchaResponse = response;
            $(".btnSubmitCaptcha").show();
        };
        $("#myFormCaptcha").submit(function(event) {
            if (recaptchaResponse == '') {
                alert('You must verify you are not a bot before proceeding');
                location.reload();
                return false;
            }
        });
    </script>
</body>

</html>
