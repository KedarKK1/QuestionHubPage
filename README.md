<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="Kedar Kashinath Koshti" content="Your page" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    />

    <!-- ajax link, js link and css link is added here -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script type="text/javascript" src="questionHubPage/js/questionHubPage.js"></script>
    <link rel="stylesheet" href="questionHubPage/css/questionHubPage.css">

  </head>
  <body>
    <!-- Navbar goes here -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Profile</a>
            </li>

            <li class="nav-item">
              <a class="nav-link disabled">Logout</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- your code goes here -->
    <div class="containter bg-dark">
        <!-- remember this row can have 4 cards but i am closing the row only after 3 cards  -->
        <div class="row d-flex justify-content-evenly">
            <!-- 1st box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="post-module1 ">
                    <!-- btw, 1px margin-bottom here gives button and image/content kinda different (a bit of space) look -->
                    <div class='post-modules' style="margin-bottom: 1px !important;">       
                        <div class='thumbnail' style="background-image: linear-gradient(180deg, rgba(18, 25, 33, 0) 41.15%, rgba(18, 25, 33, 0.37) 54.8%, rgba(18, 25, 33, 0.63) 71.51%, rgba(18, 25, 33, 0.86) 85.37%, #121921 100%), url(https://www.howtogeek.com/wp-content/uploads/2021/05/web_crawler_header.jpg?height=200p&trim=2,2,2,2);" >
                        </div>                        
                        <div class='post-content'>
                            <h1 class='title' style="font-size: 30px; font-weight:bolder !important;">1.Backtracking Chef</h1><br>
                            <div class="sub-title" style="font-size: 17px; font-weight: lighter !important;">Submissions : N <br>

                                    <span class="col-3">Accuracy :</span>     
                                    <span class="col-9">
                                        <!-- for red part of animated progress bar -->
                                        <div class="progress    progress-bar-striped progress-bar-animated">
                                           <!-- for green part of animated progress bar -->
                                            <div class="progress-bar progress-bar-striped progress-bar-animated   " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    </span> 

                            </div>
                            <!-- the below part will only appers after hovering over post module1 -->
                            <p class='description description1'><br> Put your optimisation skills to test in order to efficiently manage passenger flow.</p>
                        </div>
                    </div>
                    <div class="row no-gutters">
                        <div class="col-12">
                            <a style="width:100%;border-radius: 0px 0px 5px 5px;color:white;" class="btn  buttonfntr" href="#">Attempt</a>
                        </div>
                    </div>    
                </div>
            </div>            
            <!-- 1st box ends here -->
            <!-- 2nd box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="post-module2 " >
                    <!-- onmouseover="bgblur1(this)"  onmouseout="bgrestore1(this)"    taken from here -->
                    <div class='post-modules' style="margin-bottom: 1px !important;">   
                        <!-- paste image url here in thumbnail      -->
                        <div class='thumbnail' style="background-image: linear-gradient(180deg, rgba(18, 25, 33, 0) 41.15%, rgba(18, 25, 33, 0.37) 54.8%, rgba(18, 25, 33, 0.63) 71.51%, rgba(18, 25, 33, 0.86) 85.37%, #121921 100%), url(https://www.parallels.com/blogs/ras/app/uploads/2020/09/rdp-meaning-bg.jpg);" >
                        </div>                        
                        <div class='post-content'>
                            <h1 class='title' style="font-size: 30px; font-weight:bolder !important;">2.Reverse The Number</h1><br>
                            <div class="sub-title" style="font-size: 17px; font-weight: lighter !important;">Submissions : N <br>

                                <span class="col-3">Accuracy :</span>     
                                <span class="col-9"><div class="progress    progress-bar-striped progress-bar-animated">
                                        <div class="progress-bar progress-bar-striped progress-bar-animated   " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                    </div>
                                </span> 

                            </div>
                            <p class='description description2'><br> Given an Integer N, write a program to reverse it.</p>
                        </div>
                    </div>
                    <div class="row no-gutters">
                        <div class="col-12">
                            <a style="width:100%;border-radius: 0px 0px 5px 5px;color:white;" class="btn  buttonfntr " href="#">Attempt</a>
                        </div>
                    </div>    
                </div>
            </div>            
            <!-- 2nd box ends here -->    
            <!-- 3rd box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="post-module3 " >
                    <div class='post-modules' style="margin-bottom: 1px !important;">       
                        <div class='thumbnail' style="background-image: linear-gradient(180deg, rgba(18, 25, 33, 0) 41.15%, rgba(18, 25, 33, 0.37) 54.8%, rgba(18, 25, 33, 0.63) 71.51%, rgba(18, 25, 33, 0.86) 85.37%, #121921 100%), url(/questionHubPage/img/webmaster1.jpg);" >
                        </div>                        
                        <div class='post-content'>
                            <h1 class='title' style="font-size: 30px; font-weight:bolder !important;">3.Packaging Cupcakes</h1><br>
                            <div class="sub-title" style="font-size: 17px; font-weight: lighter !important;">Submissions : N <br>

                                <span class="col-3">Accuracy :</span>     
                                <span class="col-9">
                                    <div class="progress    progress-bar-striped progress-bar-animated">
                                        <div class="progress-bar progress-bar-striped progress-bar-animated   " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                    </div>
                                </span> 

                            </div>
                            <p class='description description3'><br>Chef enjoys eating cupcakes very much. Help Chef choose the package size A that will let him eat as many cupcakes as possible.</p>
                        </div>
                    </div>
                    <div class="row no-gutters">
                        <div class="col-12">
                            <a style="width:100%;border-radius: 0px 0px 5px 5px;color:white;" class="btn  buttonfntr" href="#">Attempt</a>
                        </div>
                    </div>    
                </div>   
            </div>            
            <!-- 3rd box ends here -->
        </div>
        
        <!-- new row is starting here -->
        <div class="row d-flex justify-content-evenly">    
            <!-- 4th box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="post-module4 " >
                    <div class='post-modules' style="margin-bottom: 1px !important;">       
                        <div class='thumbnail' style="background-image: linear-gradient(180deg, rgba(18, 25, 33, 0) 41.15%, rgba(18, 25, 33, 0.37) 54.8%, rgba(18, 25, 33, 0.63) 71.51%, rgba(18, 25, 33, 0.86) 85.37%, #121921 100%), url(https://analyticsinsight.b-cdn.net/wp-content/uploads/2021/08/Top-8-Programming-Languages-for-Hacking-2021.jpg);" >
                        </div>                        
                        <div class='post-content'>
                            <h1 class='title' style="font-size: 30px; font-weight:bolder !important;">4.Smallest Numbers of Notes</h1><br>
                            <div class="sub-title" style="font-size: 17px; font-weight: lighter !important;">Submissions : N <br>

                                <span class="col-3">Accuracy :</span>     
                                <span class="col-9"><div class="progress    progress-bar-striped progress-bar-animated">
                                        <div class="progress-bar progress-bar-striped progress-bar-animated   " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                    </div>
                                </span> 

                            </div>
                            <p class='description description4'><br>Consider a currency system in which there are notes of six denominations, namely, Rs. 1, Rs. 2, Rs. 5, Rs. 10, Rs. 50, Rs. 100.
                                If the sum of Rs. N is input, write a program to computer smallest number of notes that will combine to give Rs. N.</p>
                        </div>
                    </div>
                    <div class="row no-gutters">
                        <div class="col-12">
                            <a style="width:100%;border-radius: 0px 0px 5px 5px;color:white;" class="btn  buttonfntr " href="#">Attempt</a>
                        </div>
                    </div>    
                </div>
            </div>            
            <!-- 4th box ends here -->
            <!-- 5th box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="post-module5 " >
                    <div class='post-modules' style="margin-bottom: 1px !important;">       
                        <div class='thumbnail' style="background-image: linear-gradient(180deg, rgba(18, 25, 33, 0) 41.15%, rgba(18, 25, 33, 0.37) 54.8%, rgba(18, 25, 33, 0.63) 71.51%, rgba(18, 25, 33, 0.86) 85.37%, #121921 100%), url(img/yi1.jpg);" >
                        </div>                        
                        <div class='post-content'>
                            <h1 class='title' style="font-size: 30px; font-weight:bolder !important;">5.Coins And Triangle</h1><br>
                            <div class="sub-title" style="font-size: 17px; font-weight: lighter !important;">Submissions : N <br>

                                <span class="col-3">Accuracy :</span>     
                                <span class="col-9"><div class="progress progress-bar-striped progress-bar-animated">
                                        <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                    </div>
                                </span> 

                            </div>
                            <p class='description description5'><br>Chef belongs to a very rich family which owns many gold mines. Today, he brought N gold coins and decided to form a triangle using these coins. Isn't it strange?
                                Chef has a unusual way of forming a triangle using gold coins.</p>
                        </div>
                    </div>
                    <div class="row no-gutters">
                        <div class="col-12">
                            <a style="width:100%;border-radius: 0px 0px 5px 5px;color:white;" class="btn  buttonfntr" href="#">Attempt</a>
                        </div>
                    </div>    
                </div>
            </div>            
            <!-- 5th box ends here -->  


            <!-- note i have tried some experiments here so be careful on 6th question , you can copy above cards to have same elements like above  -->
            <!-- 6th box starts here -->
            <div class="col-md-4 col-sm-6 col-sx-12">
                <div class="post-module6 " >
                    <div class='post-modules' style="margin-bottom: 0px !important;">       
                        <div class='thumbnail' style="background-image: linear-gradient(180deg, rgba(18, 25, 33, 0) 41.15%, rgba(18, 25, 33, 0.37) 54.8%, rgba(18, 25, 33, 0.63) 71.51%, rgba(18, 25, 33, 0.86) 85.37%, #121921 100%), url(img/webcrawler1.jpg);" >
                        </div>                        
                        <div class='post-content'>
                            <h1 class='title' style="font-size: 35px; font-weight:bolder !important;">6.Mutated Minions</h1><br>
                            <div class="sub-title" style="font-size: 19px; font-weight: lighter !important;">Submissions : N 
                                <div class="row">
                                    <span class="col-3">Accuracy:</span>     
                                    <span class="col-9"><div class="progress  progress-bar-striped progress-bar-animated">
                                            <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">75%</div>
                                        </div>
                                    </span> 
                                </div>
                            </div>
                            <p class='description description6'>Given the initial characteristic integers of N minions, all of which are then transmogrified, find out how many of them become Wolverine-like.</p>
                        </div>
                    </div>
                    <div class="row no-gutters">
                        <div class="col-12">
                            <a style="width:100%;border-radius: 0px 0px 5px 5px;color:white;" class="btn  buttonfntr " href="#">Attempt</a>
                        </div>
                    </div>    
                </div>
            </div>            
            <!-- 6th box ends here -->                                      
    
        </div>    
    </div>   
    <br><br><br>
    <!-- Footer goes here -->
    <footer class="text-center fixed-bottom bg-light">
      <div class="container-fluid">
        <div class="footer-text pt-3 pb-4">PISB <span>&copy</span></div>
      </div>
    </footer>
  </body>
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
    crossorigin="anonymous"
  ></script>
</html>
