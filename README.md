
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, sans-serif;
        }

        body{
            background:#f4f4f4;
            color:#333;
            line-height:1.6;
        }

        .container{
            width:80%;
            margin:30px auto;
            background:#fff;
            padding:30px;
            border-radius:10px;
            box-shadow:0 0 10px rgba(0,0,0,0.1);
        }

        .header{
            text-align:center;
            margin-bottom:30px;
        }

        .header h1{
            font-size:40px;
            color:#222;
        }

        .header p{
            font-size:18px;
            color:#666;
        }

        .section{
            margin-bottom:25px;
        }

        .section h2{
            background:#222;
            color:white;
            padding:10px;
            border-radius:5px;
            margin-bottom:15px;
        }

        ul{
            padding-left:20px;
        }

        .skills li,
        .projects li{
            margin-bottom:10px;
        }

        .contact p{
            margin-bottom:8px;
        }

        .footer{
            text-align:center;
            margin-top:20px;
            color:#777;
        }

        @media(max-width:768px){
            .container{
                width:95%;
            }

            .header h1{
                font-size:30px;
            }
        }
    </style>
</head>

<body>

    <div class="container">

        <!-- Header -->
        <div class="header">
            <h1>Your Name</h1>
            <p>Student | Web Developer | Programmer</p>
        </div>

        <!-- About -->
        <div class="section">
            <h2>About Me</h2>
            <p>
                I am a passionate student interested in web development,
                programming, and technology. I love building projects and
                learning new skills.
            </p>
        </div>

        <!-- Education -->
        <div class="section">
            <h2>Education</h2>
            <p><strong>B.Tech in Computer Science</strong></p>
            <p>Your College Name</p>
            <p>2023 - 2027</p>
        </div>

        <!-- Skills -->
        <div class="section">
            <h2>Skills</h2>

            <ul class="skills">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Java</li>
                <li>Python</li>
                <li>SQL</li>
            </ul>
        </div>

        <!-- Projects -->
        <div class="section">
            <h2>Projects</h2>

            <ul class="projects">
                <li>
                    <strong>Portfolio Website</strong><br>
                    Created a personal portfolio website using HTML and CSS.
                </li>

                <li>
                    <strong>Student Management System</strong><br>
                    Developed using Java and MySQL.
                </li>

                <li>
                    <strong>Weather App</strong><br>
                    Built a weather app using JavaScript API integration.
                </li>
            </ul>
        </div>

        <!-- Contact -->
        <div class="section contact">
            <h2>Contact</h2>

            <p>Email: yourmail@gmail.com</p>
            <p>Phone: +91 XXXXXXXXXX</p>
            <p>LinkedIn: linkedin.com/in/yourprofile</p>
            <p>GitHub: github.com/yourusername</p>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p>© 2026 Your Name. All Rights Reserved.</p>
        </div>

    </div>

</body>
</html>
