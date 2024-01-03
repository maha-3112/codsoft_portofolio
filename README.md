<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="portofolio.css">
    <style>
        body {
            background-color: rgb(0, 0, 0);
            display: flexbox;
        }
        @media screen and (max-width: 800px) {
            body {
                width: 700px;
            }
        }
        .header {
            margin-top: -2.5%;
        }
        section:hover,.image:hover,.project1:hover,.project2:hover,.project3:hover,.view:hover {
            box-shadow: 2px 5px 40px rgb(255, 255, 255);
        }
        h1 {
            font-family: cursive;
            padding-left: 5%;
            margin-top: -5%;
            padding-bottom: 5%;
        }
        .container {
            height: 100px;
            background-color: rgb(7, 18, 47);
        }
        @media screen and (max-width: 800px) {
            .container {
                margin-right: 0%;
            }
        }
        @media screen and (max-width: 800px) {
            .header {
                text-align: center;
                font-size: medium;
                margin-top: -9%;
            }
        }
        .info {
            padding: 5%;
            padding-top: 5%;
            padding-right: 50%;
            text-indent: 15px;
            line-height: 30px;
            font-size: large;
        }
        h2 {
            block-size: 0;
            padding-left: 15%;
            color: bisque;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }
        .image {
            align-self: center;
            height: 300px;
            width: 300px;
            background-color: rgb(23, 42, 79);
            border-radius: 50%;
            margin-left: 150%;
        }
        .im0 {
            align-self: center;
            height: 300px;
            width: 300px;
            background-color: rgb(23, 42, 79);
            border-radius: 50%;
            margin-left: -5%;
        }
        .part1 {
            padding: 1%;
            color: white;
            height: 450px;
            display: flexbox;
        }
        .im1 {
            height: 100px;
            width: 100px;
            margin-bottom: -4%;
            margin-left: 2%;
        }
        .about {
            margin-top: -50%;
        }
        @media screen and (max-width: 800px) {
            .part1 {
              height: 800px;
            }
        }
        @media screen and (max-width: 800px) {
            .info {
              margin-top: 30%;
              width: 600px;
            }
        }
        @media screen and (max-width: 800px) {
            .image {
              margin-left: 20%;
              margin-top: -30%;
            }
        }
        @media screen and (max-width: 800px) {
            .im0 {
              margin-left: -5%;
            }
        }
        @media screen and (max-width: 800px) {
            .about {
              margin-top: 15%;
            }
          }
        .part2 {
            color: white;
            height: 450px;
            padding: 5%;
            padding-left: 15%;
            font-size: x-large;
        }
        @media screen and (max-width: 800px) {
            .part2 {
              font-size: larger;
              height: 450px;
            }
        }
        @media screen and (max-width: 800px) {
            .topics {
                margin-top: 10%;
                margin-left: -8%;
                line-height: 32px;
            }
        }
        h3 {
            margin: auto;
        }
        .my_lvl {
            height: 410px;
            width: 400px;
            margin-left: 30%;
            margin-top: -29%;
        }
        @media screen and (max-width: 800px) {
            .my_lvl {
              margin-top: -62%;
            }
        }
        .box {
            height: 20px;
            width: 300px;
            background-color: white;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        .c {
            height:20px;
            width: 100px;
            background-color: rgb(53,83, 142);
            border-radius: 10px;
        }
        .dsa {
            height:20px;
            width: 100px;
            background-color: rgb(53,83, 142);
            border-radius: 10px;
        }
        .frontend {
            height:20px;
            width: 150px;
            background-color: rgb(53,83, 142);
            border-radius: 10px;
        }
        .python {
            height:20px;
            width: 100px;
            background-color: rgb(53,83, 142);
            border-radius: 10px;
        }
        .figma {
            height:20px;
            width: 200px;
            background-color: rgb(53, 83, 142);
            border-radius: 10px;
        }
        .communication {
            height:20px;
            width: 275px;
            background-color: rgb(53, 83, 142);
            border-radius: 10px;
        }
        .teamwork {
            height:20px;
            width: 290px;
            background-color: rgb(53, 83, 142);
            border-radius: 10px;
        }
        .part3 {
            color: white;
            height: 800px;
            padding: 5%;
            padding-left: 10%;
            font-size: x-large;
        }
        @media screen and (max-width: 800px) {
            .part3 {
                height: 1200px;
            }
        }
        .project1 {
            height: 300px;
            width: 700px;
            margin-top: -10%;
            margin-bottom: 15%;
            border-radius: 15px;
            margin-left: 20%;
            text-align: center;
            box-shadow: 2px 5px 10px black;
        }
        .im4 {
            height: 300px;
            width: 700px;
            border-radius: 15px;
            text-align: center;
        }
        @media screen and (max-width: 800px) {
            .project1 {
              height: 500px;
              width: 500px;
              margin-left: 3%;
            }
        }
        @media screen and (max-width: 800px) {
            .im4 {
                height: 500px;
                width: 500px;
                margin-left: 0%;
                object-fit: cover;
            }
        }
        .project2 {
            height: 300px;
            width: 700px;
            border-radius: 15px;
            margin-top: -25%;
            margin-left: 20%;
            text-align: center;
            box-shadow: 2px 5px 10px black;
        }
        @media screen and (max-width: 800px) {
            .project2 {
                height: 500px;
                width: 500px;
                margin-left: 0%;
            }
        }
        .im5 {
            height: 300px;
            width: 700px;
            border-radius: 15px;
            text-align: center;
        }
        @media screen and (max-width: 800px) {
            .im5 {
                height: 500px;
                width: 500px;
                margin-left: 0%;
                object-fit: cover;
            }
        }
        .view {
            background-color: rgb(191, 191, 207);
            color: rgb(27, 25, 21);
            box-shadow: 2px 5px 30px rgb(204, 209, 211);
            height: 70px;
            width:200px;
            margin-left: 5%;
            margin-top: 5%;
            text-align: center;
            border-radius: 15px;
        }
        .view:hover {
            box-shadow: 2px 2px 30px grey;
            cursor: pointer;
        }
        a {
            color: black;
            text-decoration: none;
        }
        a:hover {
            text-decoration: none;
            cursor: pointer;
        }
        @media screen and (max-width: 800px) {
            .view {
                margin-left: 30%;
            }
        }
        .footer {
            height: 100px;
            background-color: rgb(4, 5, 33);
            padding-left: 40%;
            padding-top: 2%;
        }
        @media screen and (max-width: 800px) {
            .footer {
              margin-left: 0%;
            }
        }
        .fa {
            padding: 20px;
            font-size: 30px;
            width: 30px;
            border-radius: 40px;
            text-align: center;
            text-decoration: none;
            margin: 5px 2px;
            color: white;
        }
        @media screen and (max-width: 800px) {
            .fa-twitter {
                margin-left: -20%;
            }
        }
        .fa:hover {
            text-decoration: none;
            box-shadow: 2px 2px 5px white;
        }
        .fa-arrow-right {
            margin-left: 80%;
            margin-top: 13%;
        }
        .fa-arrow-left {
            margin-top: 10%;
            margin-left: 6%;
        }
        @media screen and (max-width: 800px) {
            .fa-arrow-left {
                margin-left: -10%;
            }
        }
        @media screen and (max-width: 800px) {
            .fa-arrow-right {
                margin-left: 90%;
            }
        }
    </style>
    <title>Portofolio</title>
</head>

<body>
    <section class="container">
        <div>
            <img class="im1" src="https://cdn3d.iconscout.com/3d/premium/thumb/web-developer-4506461-3738664.png"
                alt="sde">
        </div>
        <div class="header">
            <h2>
                Software developer
            </h2>
        </div>
    </section>
    <section class="part1">
        <div class="info">
            <div class="image">
                <img class="im0" src="C:\Users\mahal\OneDrive\Documents\clg stuff\Internship stuffs\codsoft-web dev\portofolio\mypic.jpg" alt="mypic">
            </div>
            <p class="about">
                <h1>Hello all! This is Mahalakshmi</h1>
                A passionate software developer who is in the intermediate level of building of web applications. I
                mainly
                focus on front-end development which includes html, css, js and frameworks like react.js. I am currently
                an
                undergraduate in
                National institute of Technology tiruchirappalli pursuing b.tech metallurgical and materials
                engineering.
                I work well in design softwares like figma too.
            </p>
            <button class="view">
                <h3><a href="https://drive.google.com/file/d/1uNddlZwICULGaLkiLiTDLBJwsoVKF94n/view?usp=sharing">Download CV</a></h3>
            </button>
        </div>
    </section>
    <section class="part2">
        <h3>MY SKILLS</h3>
        <div class="topics">
            <p>C++ language</p>
            <p>DSA</p>
            <p>Front-end web dev</p>
            <p>Python</p>
            <p>Figma</p>
            <p>communication</p>
            <p>Team work</p>
        </div>
        <div class="my_lvl">
            <div class="box">
                <div class="c"></div>
            </div>
            <div class="box">
                <div class="dsa"></div>
            </div>
            <div class="box">
                <div class="frontend"></div>
            </div>
            <div class="box">
                <div class="python"></div>
            </div>
            <div class="box">
                <div class="figma"></div>
            </div>
            <div class="box">
                <div class="communication"></div>
            </div>
            <div class="box">
                <div class="teamwork"></div>
            </div>
        </div>
    </section>
    <section class="part3">
        <h3>Here are some of my projects...</h3>
        <a href="C:\Users\mahal\OneDrive\Documents\clg stuff\Internship stuffs\codsoft-web dev\Landing page\landing.html" class="fa fa-arrow-left"></a>
        <div class="project1">
            <img class="im4" src="C:\Users\mahal\OneDrive\Documents\clg stuff\Internship stuffs\codsoft-web dev\Landing page\Screenshot 2023-12-31 224159.png" alt="lp">
        </div>
        <a href="C:\Users\mahal\OneDrive\Documents\clg stuff\Internship stuffs\codsoft-web dev\Calculator\calc.html" class="fa fa-arrow-right"></a>
        <div class="project2">
            <img class="im5" src="C:\Users\mahal\OneDrive\Documents\clg stuff\Internship stuffs\codsoft-web dev\Calculator\calc.png" alt="cal">
        </div>
    </section>
    <section class="footer">
        <a href="https://twitter.com/Maha_tweees" class="fa fa-twitter"></a>
        <a href="https://www.instagram.com/mahhyy_31/" class="fa fa-instagram"></a>
        <a href="https://www.linkedin.com/in/mahalakshmi-r-60178520a/" class="fa fa-linkedin"></a>
        <a href="https://www.facebook.com/profile.php?id=61552217487227" class="fa fa-facebook"></a>
    </section>
</body>

</html># codsoft_portofolio
