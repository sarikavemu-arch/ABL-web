AIM :

To design and develop a Digital Library Management Website using HTML and CSS. It displays book categories, book covers, author details, availability status, search options, filters, and library rules using CSS Grid and tables.

 PROCEDURE :
 . Open Visual Studio Code.
 
. Create a folder named Digital Library.

. Create a file named index.html.

. Write the HTML and CSS code.

. Save the file.

. Open the index.html file in a web browser.

. The Digital Library website will be displayed.

<!DOCTYPE html>
<html>
<head>
<title>Digital Library</title>

<style>
body {
    font-family: Arial;
    margin: 0;
    background: #f2f5f9;
}

header {
    background: #263859;
    color: white;
    text-align: center;
    padding: 25px;
}

nav {
    background: #40577e;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 15px;
}

.container {
    padding: 20px;
}

input, select {
    padding: 10px;
    margin: 8px;
    border: 1px solid gray;
    border-radius: 5px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,
    minmax(180px, 1fr));
    gap: 20px;
}

.book {
    background: white;
    padding: 15px;
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 2px 6px #ccc;
    transition: transform 0.3s;
}

.book:hover {
    transform: translateY(-5px);
}

.cover {
    height: 130px;
    background: #dce6f2;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 45px;
    border-radius: 5px;
}

.available {
    color: green;
    font-weight: bold;
}

.unavailable {
    color: red;
    font-weight: bold;
}

table {
    width: 100%;
    border-collapse: collapse;
    background: white;
}

th, td {
    border: 1px solid #aaa;
    padding: 12px;
    text-align: center;
}

th {
    background: #40577e;
    color: white;
}

footer {
    background: #263859;
    color: white;
    text-align: center;
    padding: 15px;
}

@media(max-width:600px) {
    nav a {
        display: inline-block;
        margin: 7px;
    }
}
</style>
</head>

<body>

<header>
<h1>Digital Library</h1>
<p>Welcome to Our Online Library</p>
</header>

<nav>
<a href="#home">Home</a>
<a href="#books">Books</a>
<a href="#categories">Categories</a>
<a href="#rules">Library Rules</a>
</nav>

<div class="container" id="home">

<h2>Search Books</h2>

<input type="text" id="search"
placeholder="Search book or author..."
onkeyup="filterBooks()">

<select id="category" onchange="filterBooks()">
<option value="all">All Categories</option>
<option value="Programming">Programming</option>
<option value="Science">Science</option>
<option value="Fiction">Fiction</option>
</select>

<h2 id="books">Book Collection</h2>

<div class="grid" id="bookGrid">

<div class="book" data-category="Programming">
<div class="cover">📘</div>
<h3>Python Basics</h3>
<p>Author: John Smith</p>
<p class="available">Available</p>
</div>

<div class="book" data-category="Science">
<div class="cover">📗</div>
<h3>Science World</h3>
<p>Author: David Brown</p>
<p class="unavailable">Not Available</p>
</div>

<div class="book" data-category="Fiction">
<div class="cover">📕</div>
<h3>Story Book</h3>
<p>Author: William</p>
<p class="available">Available</p>
</div>

<div class="book" data-category="Programming">
<div class="cover">📙</div>
<h3>HTML and CSS</h3>
<p>Author: Peter</p>
<p class="available">Available</p>
</div>

</div>

<h2 id="categories">Book Catalog</h2>

<table>
<tr>
<th>Book Name</th>
<th>Author</th>
<th>Category</th>
<th>Status</th>
</tr>

<tr>
<td>Python Basics</td>
<td>John Smith</td>
<td>Programming</td>
<td>Available</td>
</tr>

<tr>
<td>Science World</td>
<td>David Brown</td>
<td>Science</td>
<td>Not Available</td>
</tr>

<tr>
<td>Story Book</td>
<td>William</td>
<td>Fiction</td>
<td>Available</td>
</tr>

<tr>
<td>HTML and CSS</td>
<td>Peter</td>
<td>Programming</td>
<td>Available</td>
</tr>
</table>

<h2 id="rules">Library Rules</h2>

<ul>
<li>Maintain silence in the library.</li>
<li>Return books on time.</li>
<li>Keep books clean and safe.</li>
<li>Do not damage library books.</li>
<li>Follow library timings.</li>
</ul>

</div>

<footer>
<p>© 2026 Digital Library Management System</p>
<p>Designed by Sarika | CSE (AIML)</p>
</footer>

<script>
function filterBooks() {

let search = document.getElementById("search")
.value.toLowerCase();

let category = document.getElementById("category")
.value;

let books = document.querySelectorAll(".book");

books.forEach(function(book) {

let text = book.innerText.toLowerCase();
let type = book.dataset.category;

if (text.includes(search) &&
(category === "all" || type === category)) {
book.style.display = "block";
}
else {
book.style.display = "none";
}

});
}
 
</script>

</body>
</html>

RESULT :
  
Thus, the Digital Library Management Website was successfully designed using HTML, CSS Grid, tables, and JavaScript with book categories, search, filters, and availability labels.


