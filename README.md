# brandon
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Pets</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Meet Our Team Pets!</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Gallery</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

.team-member {
    float: left;
    width: 45%;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    overflow: hidden; /* Clears floats */
}

.team-member img {
    width: 100%;
    height: auto;
}

.bio {
    padding: 15px;
}

h2 {
    color: #4CAF50;
}

/* Clearfix */
main::after {
    content: "";
    display: table;
    clear: both;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
    <main>
        <section class="team-member">
            <img src="images/dog.jpg" alt="Buddy the Dog">
            <div class="bio">
                <h2>Buddy</h2>
                <p>Buddy is a playful golden retriever who loves to fetch and play in the park.</p>
            </div>
        </section>

        <section class="team-member">
            <img src="images/cat.jpg" alt="Whiskers the Cat">
            <div class="bio">
                <h2>Whiskers</h2>
                <p>Whiskers is a curious tabby cat who enjoys climbing and napping in the sun.</p>
            </div>
        </section>

        <section class="team-member">
            <img src="images/parrot.jpg" alt="Polly the Parrot">
            <div class="bio">
                <h2>Polly</h2>
                <p>Polly is a colorful parrot who loves to sing and talk.</p>
            </div>
        </section>

        <section class="team-member">
            <img src="images/rabbit.jpg" alt="Fluffy the Rabbit">
            <div class="bio">
                <h2>Fluffy</h2>
                <p>Fluffy is a gentle rabbit who enjoys munching on carrots and hopping around.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Team Pets</p>
    </footer>
</body>
</html>
