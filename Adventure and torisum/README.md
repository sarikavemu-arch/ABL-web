AIM:
To design and develop a responsive Trekking and Camping Adventures website using HTML, CSS, and JavaScript. The website displays trekking routes, camping trips, difficulty levels, trip schedules, equipment checklists, safety guidelines, and package prices.

<!DOCTYPE html>
<html>
<head>
    <title>Trekking and Camping Adventures</title>
</head>

<body bgcolor="#eaf2e3">

    <center>
        <h1>🌲 TREKKING AND CAMPING ADVENTURES</h1>
        <h3>Explore Nature | Enjoy Adventure | Discover Mountains</h3>
        <hr>

        <a href="#home">Home</a> |
        <a href="#trekking">Trekking Routes</a> |
        <a href="#camping">Camping Trips</a> |
        <a href="#schedule">Schedule</a> |
        <a href="#equipment">Equipment</a> |
        <a href="#packages">Packages</a>
    </center>

    <hr>

    <h2 id="home">Welcome to Adventure World</h2>

    <center>
        <img src="https://images.unsplash.com/photo-1551632811-561732d1e306"
        width="80%" height="300">
        <h2>Adventure Begins Here!</h2>
        <p>Explore beautiful mountains, forests and camping locations.</p>
    </center>

    <hr>

    <h2 id="trekking">1. Popular Trekking Routes</h2>

    <table border="1" width="100%" cellpadding="10">
        <tr>
            <th>Image</th>
            <th>Route Name</th>
            <th>Location</th>
            <th>Difficulty</th>
            <th>Duration</th>
        </tr>

        <tr>
            <td><img src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b" width="150"></td>
            <td>Mountain Adventure</td>
            <td>Himalayas</td>
            <td>Easy</td>
            <td>2 Days</td>
        </tr>

        <tr>
            <td><img src="https://images.unsplash.com/photo-1551632811-561732d1e306" width="150"></td>
            <td>Forest Trek</td>
            <td>Western Ghats</td>
            <td>Moderate</td>
            <td>3 Days</td>
        </tr>

        <tr>
            <td><img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e" width="150"></td>
            <td>Lake Side Trek</td>
            <td>Mountain Lakes</td>
            <td>Difficult</td>
            <td>4 Days</td>
        </tr>
    </table>

    <hr>

    <h2 id="camping">2. Camping Trips</h2>

    <center>
        <img src="https://images.unsplash.com/photo-1478131143081-80f7f84ca84d"
        width="300" height="180">

        <h3>Mountain Camping</h3>
        <p>Enjoy tents, campfires and beautiful mountain views.</p>

        <img src="https://images.unsplash.com/photo-1504280390367-361c6d9f38f4"
        width="300" height="180">

        <h3>Nature Camping</h3>
        <p>Relax in nature and enjoy outdoor activities.</p>
    </center>

    <hr>

    <h2 id="schedule">3. Trip Schedule</h2>

    <table border="1" width="100%" cellpadding="10">
        <tr>
            <th>Day</th>
            <th>Activity</th>
            <th>Time</th>
        </tr>

        <tr>
            <td>Day 1</td>
            <td>Arrival and Introduction</td>
            <td>9:00 AM</td>
        </tr>

        <tr>
            <td>Day 2</td>
            <td>Trekking and Exploration</td>
            <td>7:00 AM</td>
        </tr>

        <tr>
            <td>Day 3</td>
            <td>Camping and Sightseeing</td>
            <td>6:00 AM</td>
        </tr>

        <tr>
            <td>Day 4</td>
            <td>Return Journey</td>
            <td>10:00 AM</td>
        </tr>
    </table>

    <hr>

    <h2 id="equipment">4. Equipment Checklist</h2>

    <ul>
        <li>Backpack</li>
        <li>Water Bottle</li>
        <li>First Aid Kit</li>
        <li>Trekking Shoes</li>
        <li>Sleeping Bag</li>
        <li>Torch Light</li>
        <li>Extra Clothes</li>
        <li>Food and Snacks</li>
    </ul>

    <hr>

    <h2>5. Safety Guidelines</h2>

    <ul>
        <li>Always travel with a trained guide.</li>
        <li>Carry enough drinking water and food.</li>
        <li>Wear proper trekking shoes.</li>
        <li>Follow marked trekking routes.</li>
        <li>Carry a first aid kit.</li>
        <li>Check weather conditions before travelling.</li>
        <li>Keep the environment clean.</li>
    </ul>

    <hr>

    <h2 id="packages">6. Adventure Packages and Prices</h2>

    <table border="1" width="100%" cellpadding="10">
        <tr>
            <th>Package</th>
            <th>Details</th>
            <th>Price</th>
        </tr>

        <tr>
            <td>Basic Package</td>
            <td>One Day Trekking Trip</td>
            <td>₹999</td>
        </tr>

        <tr>
            <td>Standard Package</td>
            <td>Two Days Camping Trip</td>
            <td>₹1999</td>
        </tr>

        <tr>
            <td>Premium Package</td>
            <td>Four Days Adventure Trip</td>
            <td>₹3999</td>
        </tr>
    </table>

    <hr>

    <center>
        <h2>Thank You for Visiting!</h2>
        <p>Explore Nature | Enjoy Trekking | Experience Camping</p>
        <p>Contact: adventure@example.com</p>
        <p>© 2026 Trekking and Camping Adventures</p>
    </center>

</body>
</html>
