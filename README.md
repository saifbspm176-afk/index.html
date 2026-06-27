<!DOCTYPE html>
<html>
<head>
    <title>Saif Portfolio</title>
    <style>
        body{
            margin:0;
            font-family:Arial;
            background:#f4f4f4;
        }

        header{
            background:#222;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background:#444;
            text-align:center;
            padding:15px;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
        }

        .hero{
            text-align:center;
            padding:50px;
            background:white;
        }

        .hero img{
            width:150px;
            border-radius:50%;
        }

        .section{
            padding:40px;
            text-align:center;
        }

        .skills{
            display:flex;
            justify-content:center;
            gap:20px;
            flex-wrap:wrap;
        }

        .box{
            background:white;
            padding:20px;
            width:200px;
            box-shadow:0 0 10px gray;
        }

        footer{
            background:#222;
            color:white;
            text-align:center;
            padding:20px;
        }
    </style>
</head>

<body>

<header>
    <h1>Saif Portfolio</h1>
    <p>BCA Student | Beginner Developer</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Skills</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    <img src="https://via.placeholder.com/150" alt="profile">
    <h2>Hello, I am Saif</h2>
    <p>I am learning web development and programming.</p>
</div>

<div class="section">
    <h2>About Me</h2>
    <p>
        I am a BCA student passionate about coding, data entry,
        design thinking, and learning new technologies.
    </p>
</div>

<div class="section">
    <h2>My Skills</h2>

    <div class="skills">
        <div class="box">C Programming</div>
        <div class="box">SQL</div>
        <div class="box">MS Office</div>
        <div class="box">HTML</div>
        <div class="box">Data Entry</div>
        <div class="box">Design Thinking</div>
    </div>
</div>

<div class="section">
    <h2>Contact</h2>
    <p>Email: saif@example.com</p>
    <p>LinkedIn: Your Profile Link</p>
</div>

<footer>
    <p>© 2026 Saif Portfolio. All Rights Reserved.</p>
</footer>

</body>
</html>
