Aim :

To design and develop a Personal Portfolio Website using HTML and CSS to display personal details, education, technical skills, hobbies, projects, achievements and contact information.e

Procedure :

Open Visual Studio Code.

Create a folder named Personal Portfolio.

Create a file named index.html.

Write HTML code to create portfolio sections.

Use CSS to add colours, animations and styling.

Add navigation links to move between sections.

Run the program in a web browser.

. Web Development Program :

Create a file named index.html and copy this complete code.

<!DOCTYPE html>
<html>
<head>
<title>Sarika Portfolio</title>

<style>
body {
    font-family: Arial;
    margin: 0;
    background: #eaf2f8;
    text-align: center;
}

header {
    background: #172554;
    color: white;
    padding: 25px;
}

nav {
    background: #2563eb;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 12px;
}

nav a:hover {
    color: yellow;
}

section {
    background: white;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
}

h2 {
    color: #2563eb;
}

.card {
    padding: 15px;
    background: #dbeafe;
    margin: 10px;
    border-radius: 8px;
    animation: fade 2s;
}

@keyframes fade {
    from {opacity: 0;}
    to {opacity: 1;}
}

footer {
    background: #172554;
    color: white;
    padding: 15px;
}
</style>
</head>

<body>

<header>
<h1>Welcome to My Portfolio</h1>
<h2 style="color:white;">I am Sarika</h2>
<p>B.Tech CSE (AIML) Student</p>
</header>

<nav>
<a href="#about">About</a>
<a href="#education">Education</a>
<a href="#skills">Skills</a>
<a href="#hobbies">Hobbies</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<section id="about">
<h2>About Me</h2>
<p>My name is Sarika. I am a B.Tech CSE AIML student.</p>
<p>I am interested in learning new technologies.</p>
</section>

<section id="education">
<h2>Educational Qualifications</h2>
<div class="card">B.Tech – CSE (AIML)</div>
<div class="card">Intermediate</div>
<div class="card">SSC</div>
</section>

<section id="skills">
<h2>Technical Skills</h2>
<div class="card">Python</div>
<div class="card">HTML</div>
<div class="card">CSS</div>
<div class="card">JavaScript</div>
</section>

<section id="hobbies">
<h2>My Hobbies</h2>
<p>Listening to Music</p>
<p>Learning New Things</p>
<p>Exploring Technology</p>
</section>

<section id="projects">
<h2>My Projects</h2>
<div class="card">Personal Portfolio Website</div>
<div class="card">Python Programs</div>
<div class="card">College Fest Website</div>
</section>

<section>
<h2>Achievements and Resume</h2>
<p>Certificates and Achievements</p>
<p>Resume: Available on request</p>
</section>

<section id="contact">
<h2>Contact Information</h2>
<p>Name: Sarika</p>
<p>Email: sarika@example.com</p>
<p>Branch: CSE (AIML)</p>
</section>

<footer>
<p>© 2026 Sarika Portfolio</p>
</footer>

</body>
</html> 
Result : 
Thus, a responsive Personal Portfolio Website with navigation links, CSS animations, educational details, skills, hobbies, projects and contact information was developed successfully.



