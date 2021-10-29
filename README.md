# QuestionHubPage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YT trial</title>
    <style>
:root{
    --clr-neutral-900: hsl(207, 19%, 9%);
    --clr-neutral-100: hsl(0,0%,100%);
    --clr-accent-400: hsl(142, 90%, 61%);
}
*,
*::before,
*::after{
    box-sizing: border-box;
}
.mycontainer1{
    border: 1px double cyan;
    border-radius: 5px;
    box-shadow: 0 0 14px 9px rgb(23, 117, 117);
    height: 345px;
}

.card-title{
    height: 25px;
}
.card-img{
    height: 270px;
}
.mycard{
    padding: 10rem 0 0;
    max-width: 35ch;
    border-radius: 0.5rem;
    overflow: hidden;
    transition: transform 500ms ease;
}
.mycard:hover,
.mycard:focus-within{
    transform: scale(1.05);
}
.mycard-content{
    --padding: 1.5rem;
    padding: var(--padding);
    background: transparent;
}
@media (hover){
    .mycontainer1:hover {
        transform: scale(1.05);
        transition: transform 500ms ease;
    }
    .mycontainer1:hover .card-img{
        filter: blur(4px);
        opacity: 0.5;
    }
    .mycard-content{
        transform: translateY(65%);
        transition: transform 500ms ease;
    }
    .mycard-content > *:not(.mycard-title, .card-title) {
        opacity: 0;
        transition: opacity 500ms ease;
        transition-delay: 500ms;
    }
    .mycard:hover .mycard-content,
    .mycard:focus-within .mycard-content{
        transform: translateY(0);
    }
    .mycard:focus-within .mycard-content{
        transition-duration: 0ms;
    }
    .mycard:hover .mycard-content > *:not(.mycard-title, .card-title),
    .mycard:focus-within .mycard-content > *:not(.mycard-title, .card-title){
        opacity: 1;
        transition-delay: 100ms;
    }    
    .mycard-title::after{
        transform: scaleX(0);
    }
}

.mycard-title{
    position: relative;

    outline: 1px solid transparent;
}
.mycard-title::after{
    content: "";
    position: absolute;
    height: 4px;
    bottom: -2px;
    left: calc(var(--padding)*-1);
    width: calc(100% + var(--padding));
    background: var(--clr-accent-400);

    transition: transform 500ms ease;
    transform-origin: left;
}
.mycard:hover .mycard-title::after{
    transform: scaleX(1);
    transition-delay: 500ms;

}
.mycard-body{
    color: rgb(255, 255, 255 / 0);
}
.button{
    cursor: pointer;
    display: inline-block;
    text-decoration: none;
    color: hsl(207, 19%, 9%);
    background-color: var(--clr-accent-400);
    padding: 0.5em 1.25em;
    border-radius: 0.25rem;
}
.button:hover,
.button:focus{
    background-color: var(--clr-neutral-100);
    }

    </style>
<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

</head>
<body class="bg-dark">
    <!-- Image and text -->
<nav class="navbar navbar-info bg-info">
    <a class="navbar-brand" href="#">
      <img src="/docs/4.0/assets/brand/bootstrap-solid.svg" width="30" height="30" class="d-inline-block align-top" alt="">
      Bootstrap
    </a>
  </nav>
    <!-- background: var(--clr-neutral-900);   in body 
        overflow: hidden;     in mycard-->
    <!-- <div class="mycard">
        <div class="mycard-content">
            <h2 class="mycard-title">
                Sometitle Here
            </h2>
            <p class="mycard-body">
                And whatever you do, don't forget to keep on making your corner of the internet just a little bit more awesome
            </p>
            <a href="#" class="button">Button</a>
        </div>
    </div> -->
    <br>
    <div class="container">
        <div class="row">
            <!-- 1st box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="mycontainer1 bg-dark">
                    <div class="card  bg-dark text-white"> 
                        <h5 class="card-title"> 1.Django algo<br>  <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                            ✓
                            <span class="visually-hidden">unread messages</span>
                          </span></h5>
                        <img class="card-img" src="olympiad1.jpg" alt="Card image">
                        <div class=" card-body card-img-overlay mycard">
    <!--                         <span class="mycard"> -->
                            <div class="mycard-content">
                                <h5 class="mycard-title">
                                    <!-- <div class="card-text"> -->
                                        Submissions : N <br>
                                        Accuracy : <div class="progress bg-danger progress-bar-striped progress-bar-animated">
                                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    <!-- </div> -->
                                </h5>
                                <p class="mycard-body">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                            <!-- </span> -->
                        </div>    
                    </div><div class="bg-transparent border-success"><button href="www.google.com" type="button" class="btn btn-info col-12">View</button></div>
                </div>
                <hr>
            </div>
            <!-- 1st box ends here -->
            <!-- 2nd box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="mycontainer1 bg-dark">
                    <div class="card  bg-dark text-white"> 
                        <h5 class="card-title"> 2.Django algo<br> <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                            🞩
                            <span class="visually-hidden">unread messages</span>
                          </span></h5>
                        <img class="card-img" src="rdp1.jpg" alt="Card image">
                        <div class=" card-body card-img-overlay mycard">
    <!--                         <span class="mycard"> -->
                            <div class="mycard-content">
                                <h5 class="mycard-title">
                                    <!-- <div class="card-text"> -->
                                        Submissions : N <br>
                                        Accuracy : 
                                        <div class="progress bg-danger progress-bar-striped progress-bar-animated">
                                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    <!-- </div> -->
                                </h5>
                                <p class="mycard-body">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                            <!-- </span> -->
                        </div>    
                    </div><div class="bg-transparent border-success"><button href="www.google.com" type="button" class="btn btn-info col-12">View</button></div>
                </div>
                <hr>
            </div>
            <!-- 2nd box ends here -->
            <!-- 3rd box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="mycontainer1 bg-dark">
                    <div class="card  bg-dark text-white"> 
                        <h5 class="card-title"> 3.Django algo<br><span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                            🞩
                            <span class="visually-hidden">unread messages</span>
                          </span></h5>
                        <img class="card-img" src="yi1.jpg" alt="Card image">
                        <div class=" card-body card-img-overlay mycard">
    <!--                         <span class="mycard"> -->
                            <div class="mycard-content">
                                <h5 class="mycard-title">
                                    <!-- <div class="card-text"> -->
                                        Submissions : N <br>
                                        Accuracy : 
                                        <div class="progress bg-danger progress-bar-striped progress-bar-animated">
                                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    <!-- </div> -->
                                </h5>
                                <p class="mycard-body">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                            <!-- </span> -->
                        </div>    
                    </div><div class="bg-transparent border-success"><button href="www.google.com" type="button" class="btn btn-info col-12">View</button></div>
                </div>
                <hr>
            </div>
            <!-- 3rd box ends here -->
            <!-- 4th box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="mycontainer1 bg-dark">
                    <div class="card  bg-dark text-white"> 
                        <h5 class="card-title"> 4.Django algo<br><span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                            ✓
                            <span class="visually-hidden">unread messages</span>
                          </span></h5>
                        <img class="card-img" src="webcrawler1.jpg" alt="Card image">
                        <div class=" card-body card-img-overlay mycard">
    <!--                         <span class="mycard"> -->
                            <div class="mycard-content">
                                <h5 class="mycard-title">
                                    <!-- <div class="card-text"> -->
                                        Submissions : N <br>
                                        Accuracy : 
                                        <div class="progress bg-danger progress-bar-striped progress-bar-animated">
                                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    <!-- </div> -->
                                </h5>
                                <p class="mycard-body">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                            <!-- </span> -->
                        </div>    
                    </div><div class="bg-transparent border-success"><button href="www.google.com" type="button" class="btn btn-info col-12">View</button></div>
                </div>
                <hr>
            </div>
            <!-- 4th box ends here -->           
            <!-- 5th box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="mycontainer1 bg-dark">
                    <div class="card  bg-dark text-white"> 
                        <h5 class="card-title"> 5.Django algo<br><span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                            ✓
                            <span class="visually-hidden">unread messages</span>
                          </span></h5>
                        <img class="card-img" src="webmaster1.jpg" alt="Card image">
                        <div class=" card-body card-img-overlay mycard">
    <!--                         <span class="mycard"> -->
                            <div class="mycard-content">
                                <h5 class="mycard-title">
                                    <!-- <div class="card-text"> -->
                                        Submissions : N <br>
                                        Accuracy : 
                                        <div class="progress bg-danger progress-bar-striped progress-bar-animated">
                                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    <!-- </div> -->
                                </h5>
                                <p class="mycard-body">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                            <!-- </span> -->
                        </div>    
                    </div><div class="bg-transparent border-success"><button href="www.google.com" type="button" class="btn btn-info col-12">View</button></div>
                </div>
                <hr>
            </div>
            <!-- 5th box ends here --> 
            <!-- 6th box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="mycontainer1 bg-dark">
                    <div class="card  bg-dark text-white"> 
                        <h5 class="card-title"> 6.Django algo<br><span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                            ✓
                            <span class="visually-hidden">unread messages</span>
                          </span></h5>
                        <img class="card-img" src="webcrawler1.jpg" alt="Card image">
                        <div class=" card-body card-img-overlay mycard">
    <!--                         <span class="mycard"> -->
                            <div class="mycard-content">
                                <h5 class="mycard-title">
                                    <!-- <div class="card-text"> -->
                                        Submissions : N <br>
                                        Accuracy : 
                                        <div class="progress bg-danger progress-bar-striped progress-bar-animated">
                                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    <!-- </div> -->
                                </h5>
                                <p class="mycard-body">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            </div>
                            <!-- </span> -->
                        </div>    
                    </div><div class="bg-transparent border-success"><button href="www.google.com" type="button" class="btn btn-info col-12">View</button></div>
                </div>
                <hr>
            </div>
            <!-- 6th box ends here -->                                    
        </div>
    </div>
</body>
</html>
