<!DOCTYPE html>

<html lang=”en”>

<head>

    <meta charset=”UTF-8”>

    <meta name=”viewport” content=”width=device-width, initial-scale=1.0”>

    <title>My Portfolio</title>

    <link rel=”stylesheet” href=”styles.css”>

</head>

<body>

    <header>

        <div class=”container”>

            <h1>Your Name</h1>

            <nav>

                <ul>

                    <li><a href=”#home”>Home</a></li>

                    <li><a href=”#about”>About</a></li>

                    <li><a href=”#portfolio”>Portfolio</a></li>

                    <li><a href=”#contact”>Contact</a></li>

                </ul>

            </nav>

        </div>

    </header>

    <main>

        <section id=”home”>

            <div class=”hero”>

                <h2>Welcome to My Portfolio</h2>

                <p>Discover my work and skills</p>

                <a href=”#portfolio” class=”btn”>View My Work</a>

            </div>

        </section>

        <section id=”about”>

            <div class=”container”>

                <h2>About Me</h2>

                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>

                <img src=”your-photo.jpg” alt=”Your Photo”>

            </div>

        </section>

        <section id=”portfolio”>

            <div class=”container”>

                <h2>My Work</h2>

                <div class=”portfolio-grid”>

                    <div class=”portfolio-item”>

                        <img src=”project1.jpg” alt=”Project 1”>

                        <h3>Project 1</h3>

                        <p>Description of Project 1</p>

                    </div>

                    <div class=”portfolio-item”>

                        <img src=”project2.jpg” alt=”Project 2”>

                        <h3>Project 2</h3>

                        <p>Description of Project 2</p>

                    </div>

                    <!—Add more projects as needed 

                </div>

            </div>

        </section>

        <section id=”contact”>

            <div class=”container”>

                <h2>Contact Me</h2>

                <form id=”contact-form”>

                    <label for=”name”>Name</label>

                    <input type=”text” id=”name” name=”name” required>

                    <label for=”email”>Email</label>

                    <input type=”email” id=”email” name=”email” required>

                    <label for=”message”>Message</label>

                    <textarea id=”message” name=”message” required></textarea>

                    <button type=”submit”>Send</button>

                </form>

            </div>

        </section>

    </main>

    <footer>

        <div class=”container”>

            <p>&copy; 2024 Your Name. All rights reserved.</p>

        </div>

    </footer>

    <script src=”scripts.js”></script>

</body>

</html>

Body {

    Font-family: Arial, sans-serif;

    Margin: 0;

    Padding: 0;

    Box-sizing: border-box;

}

Header {

    Background: #333;

    Color: #fff;

    Padding: 1rem 0;

    Text-align: center;

}

Header nav ul {

    List-style: none;

    Padding: 0;

}

Header nav ul li {

    Display: inline;

    Margin: 0 1rem;

}



Header nav ul li a {

    Color: #fff;

    Text-decoration: none;

}

.hero {

    Background: url(‘hero-image.jpg’) no-repeat center center/cover;

    Color: #fff;

    Padding: 5rem 0;

    Text-align: center;

}

.hero .btn {

    Background: #007bff;

    Color: #fff;

    Padding: 0.5rem 1rem;

    Text-decoration: none;

    Border-radius: 5px;

}

Section {

    Padding: 3rem 0;

}

.container {

    Width: 80%;

    Margin: auto;

}

.portfolio-grid {

    Display: grid;

    Grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));

    Gap: 1rem;

}

.portfolio-item {

    Background: #f9f9f9;

    Padding: 1rem;

    Text-align: center;

    Border: 1px solid #ddd;

}

Footer {

    Background: #333;

    Color: #fff;

    Text-align: center;

    Padding: 1rem 0;

}

Document.getElementById(‘contact-form’).addEventListener(‘submit’, function(event) {

    Event. Prevent default();

    Alert(‘Message sent! Thank you for contacting me.’);

});
