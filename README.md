# modul1endassignme<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>module1end assignment</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
        .navbar {
            display: flex;
            justify-content: space-between;
        }
        .hedder {
            display: flex;
        }
        .container {
            list-style: none;
            display: flex;
            gap: 50px;
        }
        span {
            color: red;
        }
        .id {
            display: flex;
        }
        nav>ul {
            display: flex;
            gap: 20px;
            list-style: none;
        }
        li>a {
            display: flex;
            list-style: none;
        }
        .div1 {
            align-items: center;
            justify-items: center;
            justify-content: space-between;
            gap: 40px;
            width: 300px;
            height: 30px;
            border: 1px solid rgb(236, 233, 233);
            font-size: 60px;
            background-color: rgb(231, 231, 227);
            border-radius: 20px;
            margin: 20px;
            margin-left: 620px;
        }
        .div2 {
            align-items: center;
            justify-items: center;
        }
        button {
            display: flex;
            background-color: rgb(41, 140, 228);
        }
        #content {
            display: flex;
        }
        button {
            float: left;
            margin: 20px;
            font-size: 20px;
            background-color: rgb(235, 230, 240);
        }
        b {
            color: rgb(138, 32, 236);
        }
        .div2 {
            font-size: 30px;
        }
        #id {
            display: flex;
            box-sizing: border-box;
            justify-content: space-around;
            align-items: center;
        }
        form.example input[type=text] {
            float: left;
            padding: 10px;
            font-size: 17px;
            border: 1px solid grey;
            justify-content: center;
            width: 600px;
            background: hwb(240 94% 4%);
            margin-left: 300px;
            border-radius: 20px;
        }
        form.example button {
            float: left;
            width: 100px;
            padding: 10px;
            background: rgb(69, 80, 235) color: white;
            font-size: 17px;
            border: 1px solid grey;
            border-left: none;
            cursor: pointer;
            border-radius: 20px;
        }
        form.example button:hover {
            float: left;
            background: hwb(246 37% 15%);
        }
        form.example::after {
            content: "";
            clear: both;
            display: table;
        }
        .icon {
            width: 10px;
            height: auto;
        }
        h6 {
            width: 200px;
            height: 30px;
            border: 1px solid grey;
            border-radius: 20px;
            justify-items: center;
            float: left;
        }
        .div8 {
            justify-items: center;
            align-items: center;
            justify-content: center;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="hedder">
            <h1>Job <span>Hunt</span></h1>
        </div>
        <nav>
            <ul>
                <li>
                    <div class="container">
                <li><a href="//Home">Home</a></li>
                <li><a href="//Jobs">Jobs</a></li>
                <li><a href="//Brose">Brose</a></li>
                </li>
            </ul>
        </nav>
        <div class="navbar">
            <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
                login
            </button>
            <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
                aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalLabel">login</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            <form action="/action_page.php">
                                <label for="fname">Email:</label><br>
                                <input type="text" id="fname" name="fname" value="srinivas@gmail.com"><br>
                                <label for="lname">Password:</label><br>
                                <input type="text" id="lname" name="lname" value="544564"><br><br>
                                <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
                                <label for="vehicle2"> student</label>
                                <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
                                <label for="vehicle3"> Recuriter</label>
                                <button>login</button>
                                <p>Dont i have an account<a href="id">sign up</a></p>
                            </form>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#signup">
                sign up
            </button>
            <div class="modal fade" id="signup" tabindex="-1" aria-labelledby="signup" aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalLabel">signup</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                            <label for="fname">Full Name:</label><br>
                            <input type="text" id="fname" name="fname" value="srinivas@gmail.com"><br>
                            <label for="lname">Email:</label><br>
                            <input type="text" id="lname" name="lname" value="544564"><br><br>
                            <label for="fname">Phone Number:</label><br>
                            <input type="text" id="fname" name="fname" value="srinivas@gmail.com"><br>
                            <label for="lname">Password:</label><br>
                            <input type="text" id="lname" name="lname" value="544564"><br><br>
                            <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
                            <label for="vehicle2"> student</label>
                            <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
                            <label for="vehicle3"> RecuriteerProfile</label>
                            <button>signup</button>
                            <p>Dont i have an account<a href="id">Login</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
    <div class="div1">
        <h5><span>no.1 job Hunt Website</span></h5>
    </div>
    <div class="div2">
        <h1>Sqarch,
            Apply&<br>Get Your<b>Dream Jobs</b></h1>
    </div>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas,
            facere quidem? Voluptatibus,
            rem minima quae quidem ratione velit dolor natus voluptates soluta magni,
            sequi sapiente !</p>
    </div>
    <div id="div7">
        <form class="example" action="/action_page.php">
            <input type="text" placeholder="Fiend your dream jobs" name="Fiend your jobs">
            <button type="submit"><i class="fa fa-search"></i></button><br>
        </form>
    </div>
    <div class="div8">
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
                    aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                    aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                    aria-label="Slide 3"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3"
                    aria-label="Slide 4"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4"
                    aria-label="Slide 5"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <text src="text" Frontend Developer... class="d-block w-100" alt="...">
                        <h6>Frontend Developer</h6>
                </div>
                <div class="carousel-item">
                    <text src="text" Backend Developer class="d-block w-100" alt="...">
                        <h6>Backend Developer</h6>
                </div>
                <div class="carousel-item">
                    <text src="text" Graphic Designer class="d-block w-100" alt="...">
                        <h6>Data Science</h6>
                </div>
                <div class="carousel-item">
                    <text src="text" Fullstock Developer class="d-block w-100" alt="...">
                        <h6>Graphic Designer</h6>
                </div>
                <div class="carousel-item">
                    <text src="text" Fullstock Developer class="d-block w-100" alt="...">
                        <h6>Fullstock Developer</h6>
                </div>
                <button class=" carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
                    data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
                    data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
        </div>
    </div>
    <div class="div3">
        <h1><b>Latest& Top</b>Job Openings</h1>
        <h5>No Job Available</h5>
    </div>
    <div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
        </script>
</body>
</html>
</body>
</html>nt
