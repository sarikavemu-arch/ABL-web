# ABL-web
 AIM :
 
To create a Movie Review and Rating Website using HTML, CSS and JavaScript. The website displays movie posters, genres, release dates, cast details, synopsis, critic reviews and ratings.

 PROCEDURE :
 
1. Open Visual Studio Code.
2. Create a new folder named Movie Website.
3. Create a file named index.html.
4. Write the HTML, CSS and JavaScript code.
5. Save the file.
6. Open the file using Google Chrome.
7. The Movie Review Website will be displayed.
   
 PROGRAM :

<!DOCTYPE html>
<html>
<head>
    <title>Movie Review Website</title>

<style>
body {
    font-family: Arial;
    background-color: #f3f4f6;
    margin: 0;
}

header {
    background-color: navy;
    color: white;
    padding: 20px;
    text-align: center;
}

.hero {
    background-color: purple;
    color: white;
    text-align: center;
    padding: 30px;
}

.container {
    width: 85%;
    margin: auto;
}

.movies {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.card {
    background-color: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 3px 8px #aaa;
}

.poster {
    height: 150px;
    color: white;
    font-size: 22px;
    font-weight: bold;
    display: flex;
    align-items: center;
    justify-content: center;
}

.one { background-color: teal; }
.two { background-color: darkred; }
.three { background-color: purple; }

.rating {
    color: orange;
    font-weight: bold;
}

input {
    width: 95%;
    padding: 12px;
    margin: 20px 0;
}

footer {
    background-color: navy;
    color: white;
    text-align: center;
    padding: 15px;
}

@media(max-width: 700px) {
    .movies {
        grid-template-columns: 1fr;
    }
}
</style>
</head>

<body>

<header>
    <h1>MovieZone</h1>
    <p>Movie Review and Rating Website</p>
</header>

<div class="hero">
    <h2>Welcome to MovieZone</h2>
    <p>Explore Movies and Read Reviews</p>
</div>

<div class="container">

<h2>Popular Movies</h2>

<input type="text" id="search"
placeholder="Search Movie..."
onkeyup="searchMovie()">

<div class="movies" id="movieList">

<div class="card">
    <div class="poster one">THE ADVENTURE</div>
    <h3>The Adventure</h3>
    <p>Genre: Action / Adventure</p>
    <p>Release Date: 15 June 2025</p>
    <p>Cast: Arjun, Priya, Ravi</p>
    <p>Synopsis: A young hero saves his city.</p>
    <p class="rating">★ Rating: 4.5/5</p>
    <p>Critic Review: An exciting movie.</p>
</div>

<div class="card">
    <div class="poster two">LOVE STORY</div>
    <h3>Love Story</h3>
    <p>Genre: Romance / Drama</p>
    <p>Release Date: 10 August 2024</p>
    <p>Cast: Kiran, Sneha, Manoj</p>
    <p>Synopsis: A beautiful story of friendship.</p>
    <p class="rating">★ Rating: 4.2/5</p>
    <p>Critic Review: A wonderful movie.</p>
</div>

<div class="card">
    <div class="poster three">SPACE MISSION</div>
    <h3>Space Mission</h3>
    <p>Genre: Sci-Fi / Thriller</p>
    <p>Release Date: 20 January 2025</p>
    <p>Cast: Varun, Anjali, Akash</p>
    <p>Synopsis: Astronauts explore a new planet.</p>
    <p class="rating">★ Rating: 4.7/5</p>
    <p>Critic Review: An interesting movie.</p>
</div>

</div>
</div>

<footer>
    <p>© 2025 MovieZone</p>
</footer>

<script>
function searchMovie() {

    let input = document.getElementById("search")
        .value.toLowerCase();

    let cards = document.querySelectorAll(".card");

    cards.forEach(function(card) {

        let name = card.querySelector("h3")
            .innerText.toLowerCase();

        if (name.includes(input)) {
            card.style.display = "block";
        }
        else {
            card.style.display = "none";
        }

    });
}
</script>

</body>
</html>

 RESULT :
 
Thus, the Movie Review and Rating Website was successfully designed using HTML, CSS and JavaScript. It displays movie details, ratings, reviews and provides a movie search option
