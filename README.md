<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Bootstrap 101 Template</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.css" rel="stylesheet">


    <style type="text/css">
  
    .blah{
      color:red;
    } 

    .blah:hover{
      background-color:yellow;
    }

    .contactIcon{
      height: 30px;  
      width: 30px;
    }

    .igIcon{
      height: 40px;  
      width: 160px
    }

    .igIcon:hover{
      opacity:0.5;
    }

    .inIcon{
      height: 40px;  
      width: 120px
    }

    .inIcon:hover{
      opacity:0.5;
    }

    .jumbotron{
      height:600px;
    }
  
    </style>
  </head>
  

  <body >
    <!--NAVBAR-->
    <nav class="navbar-dark bg-dark">
      <button class="navbar-toggler" type= "button" data-toggle="collapse" data-target="#navContent">
        <span class="navbar-toggler-icon"></span>
      </button>
      <a class ="navbar-brand" href="#">AR</a>
    </nav>
    <!--Code for dropdown-->
    <div class = "collapse navbar navbar-collapse" id = "navContent">
      <ul class = "navbar-nav ">
        <li>
          <a class="nav-link" href="#">Home</a>
        </li>
        <li>
          <a class="nav-link" href="#">About Me</a>
        </li>
        <li>
          <a class="nav-link" href="#">Portfolio</a>
        </li>
        <li>
          <a class="nav-link" href="#">Contact Me</a>
        </li>
      </ul>
    </div>
    
    <div class = "jumbotron jumbotron-fluid text-center ">
      <div class = "container">
        <h1 class = "display-4 animated fadeIn delay-0.8s "> Hi! I'm</h1>
        <h1 class = "display-1 animated fadeInUp delay-1s"><strong> Adeeb Rahman </strong></h1>
        <h1 class = "lead animated fadeIn delay-2s"> A Student and an aspiring <span class="blah">Full Stack Web Developer</span> </h1>
      </div>
    </div>


    <div class = "container aboutMe" ">

      <h2 class=" wow fadeInLeft"> About Me </h2>

      <div class="row">
        <div class="col-md-6 wow fadeInLeft">
          <p class="lead">
            I am a second year student at the Univeristy of Toronto, majoring
            in Electrical and Computer Engineering. I look to concurrently 
            complete a mechatronics minor and businees certificate along with 
            my degree.

            I am fueled by my passion for hands-on learning. I started learning
            about web development on my own and this website is the result. 
            I take pride in learning from my mistakes and in constantly refining
            my skills.
          </p>
        </div>

        <div class="col-md-6">

          <img class="img-fluid wow zoomIn" src="jimg1.jpg">

        </div>
      </div>


    </div>






    <div class = "container">
      
      <div class = "wow fadeInLeft">  
        <h2>Portfolio</h2>
        <p class = "lead"> Here are some of the projects I have done or have been part of:</p>
      </div>

      <div class = "row">

        <!-- ESP CARD--->
        <div class = "col-lg-3 mt-3">
          <div class = "card wow zoomIn">

            <img src = "ph.jpeg" class= "card-img-top">
            <div class = "card-body">
              <h5 class = "card-title"> Engineering Projects </h5>
              <p class="card-text"> ESP Description blah blah blah blahblah blahblah blahblah blahblahblah </p>
              <a href="#" class="btn btn-primary">Learn More</a>
            </div>

          </div>
        </div>

        <!-- Web Dev Card--->
        <div class="col-lg-3 mt-3">
          <div class = "card wow zoomIn">

            <img src = "ph.jpeg" class ="card-img-top">
            <div class = "card-body">
              <h5 class = "card-title"> Danforth Community Center Website </h5>
              <p class = "card-text"> We renovated the website the local mosque/community center to make more appealing and used friendly with Bootstrap 4 </p>
              <a href="#" class="btn btn-primary">Visit Website</a>              
            </div>

          </div>
        </div>

        <!-- Software Card--->
        <div class="col-lg-3 mt-3">
          <div class = "card wow zoomIn">

            <img src = "ph.jpeg" class ="card-img-top">
            <div class = "card-body">
              <h5 class = "card-title"> Personal Website </h5>
              <p class = "card-text"> Made my own website using HTML5, CSS3 and Bootstrap 4 </p>
              <a href="#" class="btn btn-primary">Visit Website</a>              
            </div>

          </div>          
        </div>

        <!-- HardWare Card--->
        <div class="col-lg-3 mt-3">
          <div class = "card wow zoomIn">

            <img src = "ph.jpeg" class ="card-img-top">
            <div class = "card-body">
              <h5 class = "card-title"> Hardware Project: Theremin </h5>
              <p class = "card-text"> Created a musical instrument that can be played with two sonar using verilog </p>
              <a href="#" class="btn btn-primary">Visit Website</a>              
            </div>

          </div>
        </div>

      </div>

      <!-- CONTACT ME-->
      <div class="contactMe">
        
        <h2 class = " mt-4">Contact Me</h2>

        <div class ="row mt-3">
          <div class = "col-xs-1 mr-2 ml-3">
            <img src="email_icon.png" class="img-fluid contactIcon" alt="Email Adeeb Rahman">
          </div>
          <div class=" col-xs-3">
            <p> adeeb167@gmail.com</p>
          </div>
        </div>

        <div class ="row mt-2">
          <div class = "col-xs-1 mr-2 ml-3">
            <img src="phone_icon.png" class="img-fluid contactIcon" alt="Phone Number Adeeb Rahman">
          </div>
          <div class=" col-xs-3">
            <p> 647-835-5615 </p>
          </div>
        </div>

        <img src="instagram_icon.jpg" class="img-fluid igIcon mt-2" alt="Instagram of Adeeb Rahman">
        <br>

        <a href="https://www.linkedin.com/in/adeeb-rahman-0642/" target="_blank"> 
          <img src="linkedin_icon.png" class="img-fluid inIcon mt-2" alt="LinkedIn of Adeeb Rahman">
        </a>
      </div>

    </div>
    






    





    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.js"></script>

    <script>
      var wow = new WOW(
    {
      boxClass:     'wow',      // animated element css class (default is wow)
      animateClass: 'animated', // animation css class (default is animated)
      offset:       0,          // distance to the element when triggering the animation (default is 0)
      mobile:       true,       // trigger animations on mobile devices (default is true)
      live:         true,       // act on asynchronously loaded content (default is true)
      callback:     function(box) {
        // the callback is fired every time an animation is started
        // the argument that is passed in is the DOM node being animated
      },
      scrollContainer: null,    // optional scroll container selector, otherwise use window,
      resetAnimation: true,     // reset animation on end (default is true)
    }
    );
    wow.init();
    </script>


  </body> 
</html>
