<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monisha K - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .header {
            background-color: #aaff00;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        .sub-header {
            text-align: center;
            font-size: 16px;
            color: #555;
        }
        .nav {
            background-color: #d40000;
            padding: 10px;
            text-align: center;
        }
        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            font-weight: bold;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .box {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
            box-shadow: 2px 2px 10px #ccc;
        }
        .footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .resume-btn {
            display: block;
            text-align: center;
            padding: 10px;
            margin-top: 10px;
            background-color: black;
            color: white;
            text-decoration: none;
            width: 150px;
            margin: auto;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <div class="header">Monisha K</div>
    <div class="sub-header">BCA Student | Web Designer | Programmer</div>

    <div class="nav">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">
        <div id="about" class="box">
            <h2>About Me</h2>
            <p>I am a student of Prince Shri Venkateswara Arts and Science College, currently in my 2nd year in the Department of Computer Applications.  
            I am a sincere person towards my work.</p>
        </div>

        <div id="education" class="box">
            <h2>Education</h2>
            <p>University of Madras</p>
            <p>II BCA (Bachelor of Computer Applications)</p>
        </div>

        <div id="skills" class="box">
            <h2>Skills</h2>
            <ul>
                <li>Editing</li>
                <li>Web Designing</li>
                <li>Python</li>
                <li>Data Structures</li>
            </ul>
        </div>

        <div id="projects" class="box">
            <h2>Projects</h2>
            <ul>
                <li>Hangman Game</li>
                <li>Gussa Number</li>
                <li>Digital Portfolio</li>
                <li>Pattern</li>
                <li>Calculator with AWT</li>
            </ul>
        </div>

        <div id="resume" class="box">
            <h2>Resume</h2>
            <a href="#" class="resume-btn">Download CV</a>
        </div>
    </div>

    <div class="footer">
        © 2024 Monisha K
    </div>

</body>
</html>
