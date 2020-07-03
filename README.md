<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <!-- <link rel="stylesheet" href="stylesheet.1.css"> -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Baloo+Bhai+2&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
    <title>Hello, world!</title>
    <style>
      *{
    margin: 0px;
    padding: 0px;
    font-family: 'Baloo Bhai 2', cursive;
}

.set img{
    max-height:600px;
    object-fit: cover;
    object-position: top;
    background-size: cover;
    image-resolution: 600dpi;
    }
    .nav{
        display: flex;
        justify-content: center;
        position: absolute;
        top:20px;
    }

    .nav ul li{
        float: left;
        list-style: none;

        
        }

     .nav a {
         padding: 10px;
         font-size: 25px;
         color: blueviolet;
         text-shadow: 10px 10px 10px white;
     }  

     @media (max-width:576px)
     {
         .nav a{
             font-size: 10px;
         }
     }


     .text_1{
         position: absolute;
         left: 50%;
         top: 40%;
         transform: translate(-50%,-50%);
         color:#e74c3c;
         text-shadow: 10px 10px 10px rgb(0, 0, 0);
         }

         @media (min-width:500px){
            .text_1 p{
                font-size: 60px;
            }
            }
         

        @media (max-width:480px)
        {
            .text_1{
                
                position: absolute;
                left: 50%;
                top: 20%;
                transform: translate(-50%,-50%);
                font-size: 20px;
            }
            .text_1 button{
                font-size: 10px;
            }

        
        }
        
        @media (min-width:768px) and (max-width:1600px)
        {
            .text_1{
                position: absolute;
                left:50%;
                top:250px;
            }
        }

     .sec_2{
         padding-top: 20px;
     }
     .sec_2_1{
         font-size: 30px;
     }

     .sec_4{
         padding-top: 50px;
     }

     .sec_4_1{
         padding-top: 30px;
        }
    
     .sec_5{
         padding-top: 50px;
     }   
     .sec_5 img{
         max-height: 400px;
         width: 100%;
         object-fit: cover;
         object-position: center;
         } 
         
     .sec_6{
         display: block;
         position: absolute;
         top: 1500px;
         color: white;
         
     }    
    @media (min-width:800px)
    {
        .sec_6_1{
            font-size: 30px;    
    }
    
    }
    
    @media (max-width:480px)
    {
        .sec_6{
            position: absolute;
            top:1950px;
            font-size: 10px;
        }
        .sec_6 button{
            font-size: 10px;
        }
    }

    @media (max-width:480px)
    {
        .sec_5 img{
            height: 200px;
        }
        .sec_6_1{
            font-size: 15px;
        }
        .sec_6_2{
            font-size: 12px;
        }
        .sec_6_3{
            font-size: 5px;
        }

    }

    .sec_7{
        padding:20px;
    }

    .sec_7_1{
        font-size: 30px;
    }

    .sec_8 img{
        height: auto;

    }
    .sec_8_1 img{
        padding: 10px;
        

    }

   .sec_8_2 img{
       height: 700px;
       padding-top: 15px;
       object-fit: cover;

   } 
   
   @media (max-width:450px) and (max-width:800px)
   {
       .sec_8_2{
           display: flex;
           justify-content: center;
       }
   }

   .sec_9 img{
       width:100%;
       max-height: 500px;
       object-fit: cover;
       object-position: top;
       padding-top: 10px;
    }

    .sec_10{
        background-color: black;
        color: white;
        height: 300px;
        
    }

    @media(max-width:450px) {
      .sec_10{
        height:auto ;
        padding: 10px;
      }
      
    }
    </style>
  </head>
  <body>
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner set">
          <div class="carousel-item active">
            <img src="https://images.pexels.com/photos/1424246/pexels-photo-1424246.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://images.pexels.com/photos/3856635/pexels-photo-3856635.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://images.pexels.com/photos/807623/pexels-photo-807623.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" class="d-block w-100" alt="...">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
        <div class="container-fluid nav text-center animated bounceInLeft">
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Office</a></li>
                <li><a href="">Work</a></li>
                <li><a href="#sec_9">Welcome</a></li>
            </ul>
        </div>

        <div class="container-fluid text_1  text-center">
            <p>Lorem ipsum dolor sit amet.</p>
            <button class="btn btn-primary-outline">Welcome</button>
            <button class="btn btn-danger">Welcome</button>
        </div>

        <div class="container sec_2">
          <div class="col text-center">
          <p class="sec_2_1">Lorem ipsum dolor sit amet.</p>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sint, eum?</p>
          <button class="btn btn-primary">Welcome</button>
        </div>
        </div>
        <div class="container-fluid sec_3">
          <div class="row">
            <div class="col-md-4 col-lg-4 text-center sec_3_1">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTtpQIkhMEq9R1n7HPTiHVk0Am4yednI2dVJ965sX1AB6a_Fvlz" alt="">
              <p>Lorem ipsum dolor sit amet.</p>
              <p>Lorem ipsum dolor</p>
          </div>
          <div class="col-md-4 col-lg-4 text-center sec_3_1">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTtpQIkhMEq9R1n7HPTiHVk0Am4yednI2dVJ965sX1AB6a_Fvlz" alt="">
              <p>Lorem ipsum dolor sit amet.</p>
              <p>Lorem ipsum dolor</p>
          </div>
          <div class="col-md-4 col-lg-4 text-center sec_3_1">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTtpQIkhMEq9R1n7HPTiHVk0Am4yednI2dVJ965sX1AB6a_Fvlz" alt="">
              <p>Lorem ipsum dolor sit amet.</p>
              <p>Lorem ipsum dolor</p>
          </div>
        </div>
        </div>

        <div class="container-fluid sec_4">
          <div class="row">
            <div class="col-md-6 col-lg-6 d-flex justify-content-center">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTaglHsEGIrzdRNvbKUtlAN1i4YmVtHkJStRaNIYaZ65mllCzIU" alt="">
            </div>
            <div class="col-md-6 col-lg-6 d-flex justify-content-center text-center">
              <div class="col  sec_4_1">
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
              <p>Lorem ipsum dolor sit amet.</p>
              <p>Lorem, ipsum dolor.</p>
              <button class="btn btn-primary">Workout</button>
            </div>
          </div>
          </div>
        </div>

        <div class="container-fluid sec_5 animated bounceInLeft n">
          <div class="row">
            <img src="https://images.unsplash.com/photo-1584536014536-aec5f7da31c7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80" alt="" class="img-fluid">
          </div>
        </div>

        <div class="container-fluid sec_6 rotateInDownRight">
          <div class="col text-center">
            <p class="sec_6_1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt, suscipit.</p>
            <p class="sec_6_2">Lorem ipsum dolor sit amet.</p>
            <button class="btn btn-primary sec_6_3">Primary</button>
            <button class="btn btn-primary sec_6_3">Workout</button>
          </div>
          </div>

          <div class="container-fluid sec_7 ">
            <div class="col text-center">
              <p style="font-weight:bold" class="sec_7_1">Lorem ipsum dolor sit amet.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Assumenda, architecto.</p>
            </div>
          </div>

          <div class="container-fluid sec_8">
            <div class="row">
              <div class="col-md-6 col-lg-6 ">
                <div class="col">
                <div class=" col-sm-12 col-md-12 col-lg-12  float-md-right sec_8_1 ">
                <img src="https://images.unsplash.com/photo-1584143369293-c977706992a1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60" alt="" class="img-fluid img1 float-right">
                <img src="https://images.unsplash.com/photo-1584143369293-c977706992a1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60" alt="" class="img-fluid img1 float-right">
              </div>
              </div>
              </div>
              <div class="col-md-6 col-lg-6 sec_8_2">
              <img src="https://images.unsplash.com/flagged/photo-1551363486-ce59042b91ce?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60" alt="" class="img-fluid" >
              </div>    
            </div>
          </div>

          <div class=" container-fluid sec_9" id="sec_9">
            <img src="https://images.unsplash.com/photo-1558980394-da1f85d3b540?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=60" alt="" class="img-fluid">
          </div>
          <div class="container-fluid ">
            <div class="row sec_10 d-flex align-items-center">
            <div class="col-md-3 col-lg-3 d-block">
              <p>Lorem ipsum dolor</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, reiciendis. Voluptate laborum ad voluptatibus repudiandae!</p>
            </div>
            <div class="col-md-3 col-lg-3 d-block">
              <p>Lorem ipsum dolor</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, reiciendis. Voluptate laborum ad voluptatibus repudiandae!</p>
            </div>
            <div class="col-md-3 col-lg-3 d-block">
              <p>Lorem ipsum dolor</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, reiciendis. Voluptate laborum ad voluptatibus repudiandae!</p>
            </div>
            <div class="col-md-3 col-lg-3 d-block">
              <p>Lorem ipsum dolor</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, reiciendis. Voluptate laborum ad voluptatibus repudiandae!</p>
            </div>
            </div>
          </div>



          



    

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  </body>
</html>
