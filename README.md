<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" 			content="width=device-width, initial-scale=1">
    <meta name="format-detection" 	content="telephone=no" />



    <title> UploadHaven - File Sharing Made Simple </title>
    <meta name="description" 		content=" UploadHaven - File Sharing Made Simple " />

    <meta name="robots"             content="index, follow" />

    <meta name="csrf-token" content="IzX7oLJz06o83Vc5rL8uZQAs3qao5WyCyZzAFAZB">

    <link rel="apple-touch-icon" sizes="120x120" href="/img/icons/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/img/icons/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/img/icons/favicon-16x16.png">
    <link rel="manifest" href="/img/icons/site.webmanifest">
    <link rel="mask-icon" href="/img/icons/safari-pinned-tab.svg" color="#5bbad5">
    <link rel="shortcut icon" href="/img/icons/favicon.ico">
    <meta name="msapplication-TileColor" content="#da532c">
    <meta name="msapplication-config" content="/img/icons/browserconfig.xml">
    <meta name="theme-color" content="#ffffff">

    <link media="all" type="text/css" rel="stylesheet" href="sa.css">

    
    <style>

        .loginForm{
            box-shadow: 0 0 0 1px rgba(0,0,0,.03), 0 2px 12px 2px rgba(0,0,0,.07);
            border-radius: 5px;
            border: none;
            background-color: white;
        }
        .loginForm .title{
            line-height: 25px;
            font-size: 25px;
            padding: 30px;
            text-align: center;
        }
        .logo{
            display: block;
            margin: 0 auto 15px;
            background-image: url('/img/logo_black_v2.png');
            background-repeat: no-repeat;
            background-position: center;
            height: 80px;
            width: auto;
        }
    </style>



    </head>
<body id="page-top">


<!-- Fixed navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="https://uploadhaven.com" style="padding-left: 30px;">
        <img src="https://uploadhaven.com/img/logo_dashboard.png"  alt="UploadHaven" height="39" style="margin-top: -4px;" />
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item">
                <a class="nav-link" href="https://uploadhaven.com">Home</a>
            </li>

            <li class="nav-item">
                <a class="nav-link" href="https://uploadhaven.com/contact">Support</a>
            </li>
	</ul>
	        <form class="form-inline my-2 ml-2 my-lg-0">
            <a class="btn btn-outline-warning" href="https://uploadhaven.com/account/login">Login</a>
        </form>
    </div>
</nav>


<style>
    .loginForm{
        box-shadow: 0 0 0 1px rgba(0,0,0,.03), 0 2px 12px 2px rgba(0,0,0,.07);
        border-radius: 5px;
        border: none;
        background-color: white;
    }

    .loginForm .title{
        line-height: 25px;
        font-size: 25px;
        padding: 30px;
        text-align: center;
    }

    .logo{
        display: block;
        margin: 0 auto 15px;
        background-image: url('/img/logo_black_v2.png');
        background-repeat: no-repeat;
        background-position: center;
        height: 80px;
        width: auto;
    }
</style>

<div class="container">
    <div class="mb-8">&nbsp;</div>

    
    
    

    
    <div class="row justify-content-center">
        <div class="col-md-7">
            <a href="https://uploadhaven.com" class="logo"></a>

            <div class="loginForm">
                <div class="title">Login to your account</div>

                <div class="row justify-content-center">
                    <div class="col-md-6">
                        <form class="form-horizontal" role="form" method="POST" action="https://uploadhaven.com/account/login">
                            <input type="hidden" name="_token" value="IzX7oLJz06o83Vc5rL8uZQAs3qao5WyCyZzAFAZB">

                            <div class="form-group">
                                <div class="col-12">
                                    <input id="email" type="email" class="form-control" name="email" value="" required autofocus placeholder="Email address">

                                                                    </div>
                            </div>

                            <div class="form-group">
                                <div class="col-12">
                                    <input id="password" type="password" class="form-control" name="password" required placeholder="Password">

                                                                    </div>
                            </div>

                            <div class="form-group">
                                <div class="col-12">
                                    <button type="submit" class="btn btn-success btn-block">Login</button>
                                </div>
                            </div>


                            <div class="form-group" >
                                <div class="col-12">
                                    <a class="btn-link small font-italic" href="https://uploadhaven.com/account/password/reset">Forgot your password?</a>
                                </div>
                            </div>

                            <input name="redirect_to" type="hidden">
                        </form>

                        <div class="form-group">
                            <div class="col-12">
                                <a class="btn btn-google btn-block d-none" style="background-color: #dd4b39; color:white;" href="https://uploadhaven.com/account/login/google"><span class="fa fa-google"></span> Login with Google</a>
                            </div>
                        </div>

                        <div class="form-group">
                            <div class="col-12">
                                <a class="btn btn-block" href="https://uploadhaven.com/account/login/discord?origin=login" style="background-color: #7289da; color:white;">Login with Discord</a>
                            </div>
                        </div>

                    </div>
                </div>


            </div>
        </div>
    </div>

    <div class="mb-8">&nbsp;</div>
</div>



<script src="https://uploadhaven.com/js/manifest.js"></script>
<script src="https://uploadhaven.com/js/vendor.js"></script>
<script src="https://uploadhaven.com/js/frontend.js?id=2875522502def4ee89e2"></script>

<script async src="https://www.googletagmanager.com/gtag/js?id=UA-111464008-1"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'UA-111464008-1');
</script>

</body>
</html>
