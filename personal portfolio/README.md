Aim :

To design and develop a Personal Portfolio Website using HTML and CSS to display personal details, education, technical skills, hobbies, projects, achievements and contact information

Procedure :

1. Open Visual Studio Code.
2. Create a folder named Personal Portfolio.
3. Create a file named index.html.
4. Write HTML code to create portfolio sections.
5. Use CSS to add colours, animations and styling.
6. Add navigation links to move between sections.
7. Run the program in a web browser.
   
 . Web Development Program :
 
<!DOCTYPE html>
<html>
<head>
    <title>Sarika Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f3f0ff;
            color: #333;
        }

        header {
            background: #38236b;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #6546a5;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 12px;
            font-weight: bold;
        }

        nav a:hover {
            color: yellow;
        }

        .profile {
            text-align: center;
            padding: 45px 15px;
            animation: fade 2s;
        }

        .profile h2 {
            color: #6546a5;
            font-size: 30px;
        }

        section {
            background: white;
            margin: 20px auto;
            padding: 25px;
            max-width: 850px;
            border-radius: 12px;
            box-shadow: 0 3px 10px #ccc;
        }

        h2 {
            color: #6546a5;
            margin-bottom: 15px;
        }

        li {
            margin: 10px 0;
        }

        footer {
            background: #38236b;
            color: white;
            text-align: center;
            padding: 20px;
        }

        @keyframes fade {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media(max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 7px;
            }

            section {
                margin: 12px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>My Personal Portfolio</h1>
    <p>Welcome to My Website</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#hobbies">Hobbies</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<div class="profile" id="home">
    <h2>Hello, I am Sarika</h2>
    <p>B.Tech Student | Branch: CSM | Section: 7</p>
    <p>Welcome to my personal portfolio website.</p>
</div>

<section id="education">
    <h2>Educational Qualifications</h2>
    <ul>
        <li>B.Tech - Computer Science</li>
        <li>Intermediate</li>
        <li>SSC</li>
    </ul>
</section>

<section id="skills">
    <h2>Technical Skills</h2>
    <ul>
        <li>Python Programming</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>Basic Computer Skills</li>
    </ul>
</section>

<section id="hobbies">
    <h2>My Hobbies</h2>
    <ul>
        <li>Listening to Music</li>
        <li>Reading Books</li>
        <li>Learning New Technologies</li>
    </ul>
</section>

<section id="projects">
    <h2>My Projects</h2>
    <ul>
        <li>Personal Portfolio Website</li>
        <li>Digital Library Website</li>
        <li>Python Mini Projects</li>
    </ul>
</section>

<section>
    <h2>Achievements</h2>
    <p>Learning programming and developing web projects.</p>
</section>

<section>
    <h2>Resume</h2>
    <p>Name: Sarika</p>
    <p>Branch: CSM</p>
    <p>Section: 7</p>
    <p>Roll No: 360</p>
</section>

<section id="contact">
    <h2>Contact Information</h2>
    <p>Name: Sarika</p>
    <p>Email: sarika@example.com</p>
    <p>Location: India</p>
</section>

<footer>
    <p>© 2026 Sarika | Personal Portfolio Website</p>
</footer>

</body>
</html>
Result :
Thus, a responsive Personal Portfolio Website with navigation links, CSS animations, educational details, skills, hobbies, projects and contact information was developed successfully.


   
