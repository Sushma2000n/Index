<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>My Chat App</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Questrial">
    <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=News+Cycle">
    <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Amatic+SC">
    <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Coming+Soon">
    <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Alegreya+Sans+SC">
    <style>
        header {
            background-color: #34262B;
            background: url(https://picjumbo.imgix.net/HNCK7769.jpg?q=40&w=1650&sharp=30) no-repeat center center fixed;
            -webkit-background-size: cover;
            -moz-background-size: cover;
            -o-background-size: cover;
            background-size: cover;
        }
        
        .more-space {
            margin-bottom: 20%;
        }
        
        header h1 {
            color: #34262B;
            font-size: 150px;
        }
        
        h1 {
            font-family: "Amatic SC", sans-serif;
        }
        
        .break1,
        .break2,
        .contact h2,
        .contact h3,
        p,
        header h4 {
            font-family: "Coming Soon", sans-serif;
        }
        
        .social-media {
            margin-top: 7%;
        }
        
        .intro {
            margin-top: 12%;
        }
        
        header h4 {
            color: #fff;
            font-size: 28px;
            font-weight: bold;
        }
        
        .red {
            color: #4285F4;
            font-weight: bold;
        }
        /**Navbar customs**/
        
        nav ul li {
            font-size: 17px;
            font-family: "News Cycle";
        }
        
        .about-us a {
            font-family: "News Cycle", serif;
        }
        
        .navbar-brand {
            font-size: 25px;
            font-family: "News Cycle";
        }
        
        .navbar-default {
            background-color: #FDFFFC;
            border: 0;
        }
        
        .navbar-default .navbar-brand {
            margin-left: 5%;
            color: #34262B;
        }
        
        .navbar-default .navbar-brand:hover,
        .navbar-default .navbar-brand:focus {
            color: #FDFFFC;
            background-color: transparent;
        }
        
        .navbar-default .navbar-text {
            color: #210A2A;
        }
        
        .navbar-default .navbar-nav>li>a {
            color: #210A2A;
        }
        
        .navbar-default .navbar-nav>li>a:hover,
        .navbar-default .navbar-nav>li>a:focus {
            color: #F9F2F6;
            background-color: transparent;
            border-bottom: 1px solid #F9F2F6;
        }
        
        .navbar-default .navbar-nav>.active>a,
        .navbar-default .navbar-nav>.active>a:hover,
        .navbar-default .navbar-nav>.active>a:focus {
            color: #F9F2F6;
            background-color: #e7e7e7;
        }
        
        .navbar-default .navbar-nav>.disabled>a,
        .navbar-default .navbar-nav>.disabled>a:hover,
        .navbar-default .navbar-nav>.disabled>a:focus {
            color: #F9F2F6;
            background-color: transparent;
        }
        
        .navbar-default .navbar-toggle {
            border-color: #ddd;
        }
        
        .navbar-default .navbar-toggle:hover,
        .navbar-default .navbar-toggle:focus {
            background-color: #ddd;
        }
        
        .navbar-default .navbar-toggle .icon-bar {
            background-color: #888;
        }
        
        .navbar-default .navbar-collapse,
        .navbar-default .navbar-form {
            border-color: #e7e7e7;
        }
        
        .navbar-default .navbar-nav>.open>a,
        .navbar-default .navbar-nav>.open>a:hover,
        .navbar-default .navbar-nav>.open>a:focus {
            color: #555;
            background-color: #e7e7e7;
        }
        
        .navbar-inner {
            background: rgba(0, 0, 0, 0);
        }
        /**Navbar customs end**/
        /***Services***/
        
        .works {}
        
        .tabs {
            background-color: #F26430;
            border: 1px solid #210A20;
        }
        
        .works p {
            margin-top: 10%;
        }
        
        .works h1 {
            font-size: 100px;
            margin-top: 7%;
            margin-bottom: 5%;
        }
        
        .thumbnail {
            margin-bottom: 12%
        }
        
        .thumbnail:hover {
            -webkit-box-shadow: 2px 2px 2px 1px #ccc;
            /* Safari 3-4, iOS 4.0.2 - 4.2, Android 2.3+ */
            -moz-box-shadow: 2px 2px 2px 1px #ccc;
            /* Firefox 3.5 - 3.6 */
            box-shadow: 2px 2px 2px 1px #ccc;
            /* Opera 10.5, IE 9, Firefox 4+, Chrome 6+, iOS 5 */
        }
        
        .space {
            margin-bottom: 10%;
        }
        
        .break1 {
            background: url(https://images.unsplash.com/photo-1432836431433-925d3cc0a5cd?fit=crop&fm=jpg&h=700&q=80&w=1050) center center fixed;
            -webkit-background-size: cover;
            -moz-background-size: cover;
            -o-background-size: cover;
            background-size: cover;
        }
        
        .break2 {
            background: url(https://unsplash.imgix.net/photo-1430760814266-9c81759e5e55?fit=crop&fm=jpg&h=750&q=75&w=1050) center center fixed;
            -webkit-background-size: cover;
            -moz-background-size: cover;
            -o-background-size: cover;
            background-size: cover;
        }
        
        .break2 h3 {
            color: #fff;
            font-size: 70px;
            margin-top: 15%;
            margin-bottom: 15%;
        }
        
        .break1 h3 {
            color: #fff;
            font-size: 70px;
            margin-top: 15%;
            margin-bottom: 15%;
        }
        /**End of Services stylus***/
        /***About us****/
        
        .about-us {
            background-color: #34262B;
        }
        
        .about-us h1 {
            color: #4285F4;
            font-size: 100px;
            margin-top: 7%;
        }
        
        .about-us-p {
            font-size: 20px;
            color: #FDFFFC;
            margin-left: 12%;
            margin-right: 12%;
            margin-top: 7%;
            margin-bottom: 10%;
        }
        
        .descript {
            margin-bottom: 15%;
        }
        
        .team {
            margin-top: 25%;
            border: 1px solid #FDFFFC;
            padding: 20px 50px 20px 50px;
            text-decoration: none;
            color: #F9F2F6;
        }
        
        .team:hover {
            text-decoration: none;
            background: rgba(193, 41, 46, 0.4);
            color: #F9F2F6;
        }
        /* Contact */
        
        .contact {
            background-color: #4285F4;
        }
        
        .contact h1 {
            font-size: 100px;
            margin-top: 7%;
        }
        
        .social-media-row-1 {
            margin-top: 10%;
        }
        
        .contact i {
            font-size: 1000%;
            padding: 20% 0% 20% 0%;
        }
        
        .contact .icon {
            border: 1px solid black;
        }
        
        .icon a {
            color: #fff;
        }
        
        .icon:hover {
            background-color: rgba(0, 0, 0, 0.5);
        }
        /* Footer */
        
        footer {
            background-color: #34292b;
        }
        
        .go-up-icon i {
            color: white;
            font-size: 400%;
            margin-top: 15%;
            border: 1px solid white;
            padding: 2% 4% 3% 4%;
            border-radius: 10%;
        }
        
        .go-up-icon i:hover {
            background-color: rgba(100, 100, 100, 0.3);
        }
        
        footer p {
            color: white;
            padding-top: 37%;
        }
        
        @media screen and (max-width: 500px) {
            header h1,
            .about-us h1,
            .works h1,
            .contact h1 {
                font-size: 50px;
                margin-bottom: 15%;
            }
            header h4 {
                font-size: 20px;
                margin-bottom: 15%;
            }
            .about-us-p {
                font-size: 14px;
            }
            .contact i {
                font-size: 500%;
            }
            .intro {
                margin-top: 50%;
            }
        }
    </style>
</head>

<body>
    <div>
        <header>
            <nav class="navbar navbar-default navbar-fixed-top navbar-inner">
                <div class="container-fluid">
                    <!-- Brand and toggle get grouped for better mobile display -->
                    <div class="navbar-header">
                        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
                        <a class="navbar-brand brand" href="#">Developer Student Clubs-TOCE</a>
                    </div>

                    <!-- Collect the nav links, forms, and other content for toggling -->
                    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                        <ul class="nav navbar-nav navbar-right">
                            {% if current_user.is_authenticated %}
                            <li><a href="/test">Test</a></li>
                            <li><a href="/score">Results</a></li>
                            {% else %}
                            <li><a href="/signup">Signup</a></li>
                            <li><a href="/login">Login</a></li>
                            {% endif %}
                        </ul>
                    </div>
                    <!-- /.navbar-collapse -->
                </div>
                <!-- /.container-fluid -->
            </nav>
        </header>
    </div>
    <div class="container-fluid">
        <div class="more-space row">
            <div class="col-md-12">
                <div class="text-center intro">
                    <h1 style="font-size:200px">Hello {% if current_user.is_authenticated %}{{ current_user.username }}{% else %}Guest{% endif %}!,</h1>
                    <h4 style="color:black">Student's Forum</h4>
                    <h4 class="red">A creative bunch who love code and design.</h4>
                </div>
            </div>
        </div>
    </div>
    <div>
        <h3>Available Rooms for sharing love!!!</h3>
        {% if current_user.is_authenticated %}
        <table class="table table-striped table-dark">
            <thead>
                <tr>
                    <th scope="col">#</th>
                    <th scope="col">Available Rooms</th>
                </tr>
            </thead>
            <tbody>
                {% for room in rooms %}
                <tr>
                    <th scope="row">1</th>
                    <td><a href="/rooms/{{ room._id.room_id }}">{{ room.room_name }}</a></td>
                </tr>
                {% endfor %}
            </tbody>
        </table>
        {% endif %}


    </div>
    <div class="about-us" id="startchange">
        <a name="about"></a>
        <div class="container-fluid">
            <div class="row text-center">
                <div class="descript col-xs-12 col-sm-12 col-md-12">
                    <h1>ABOUT US</h1>
                    <p class="about-us-p">Developer Student Clubs are university based community groups for students interested in Google developer technologies. By joining a DSC, students grow their knowledge in a peer-to-peer learning environment and build solutions for
                        local businesses and their community.</p>
                        <a href="team.html" class="btn btn-primary">Our Team</a>
                </div>
            </div>
        </div>
    </div>

</body>

</html>
