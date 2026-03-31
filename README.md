<!DOCTYPE html>
<html>
<head>
    <title>Balapushpika Portfolio</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: #0d1117;
            color: white;
        }

        nav {
            display: flex;
            justify-content: space-between;
            padding: 15px;
            background: #161b22;
            position: sticky;
            top: 0;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin: 0 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        section {
            padding: 50px;
        }

        .home {
            text-align: center;
            padding: 100px;
            background: #161b22;
        }

        .profile {
            width: 130px;
            border-radius: 50%;
            border: 3px solid cyan;
        }

        span {
            color: cyan;
        }

        .box span {
            border: 1px solid cyan;
            padding: 8px 12px;
            margin: 5px;
            display: inline-block;
            border-radius: 5px;
        }

        .project {
            background: #161b22;
            padding: 15px;
            margin: 10px 0;
            border-radius: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #161b22;
        }
    </style>

</head>

<body>

<!-- Navbar -->
<nav>
    <h2>Balapushpika</h2>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- Home -->
<section id="home" class="home">
    <img src="yourphoto.jpg" class="profile">
    <h1>Hello, I'm <span>Balapushpika</span></h1>
    <p>Student • Developer • Learner</p>
</section>

<!-- About -->
<section id="about">
    <h2>About Me</h2>
    <p>
        I am an 18-year-old student passionate about programming,
        electronics, and problem solving.
    </p>
</section>

<!-- Skills -->
<section id="skills">
    <h2>Skills</h2>
    <div class="box">
        <span>C Programming</span>
        <span>Python</span>
        <span>HTML</span>
        <span>Digital Logic</span>
    </div>
</section>

<!-- Projects -->
<section id="projects">
    <h2>Projects</h2>

    <div class="project">
        <h3>LED Toggle Circuit</h3>
        <p>Built using Tinkercad using push button logic.</p>
    </div>

    <div class="project">
        <h3>Basic Portfolio Website</h3>
        <p>Created using HTML and CSS.</p>
    </div>
</section>

<!-- Contact -->
<section id="contact">
    <h2>Contact</h2>
    <p>Email: yourmail@gmail.com</p>
</section>

<!-- Footer -->
<footer>
    <p>© 2026 Balapushpika. All rights reserved.</p>
</footer>

</body>
</html>
