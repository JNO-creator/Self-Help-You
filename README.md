/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f7f7f7;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
    max-width: 1200px;
}

/* Header */
header {
    background-color: #24292f;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
}

header nav ul {
    list-style-type: none;
    padding: 10px 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* Section Styles */
.section {
    padding: 40px 0;
    background-color: #fff;
    margin-bottom: 20px;
    border-bottom: 1px solid #ddd;
}

.section h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.section p {
    font-size: 1rem;
    line-height: 1.6;
}

/* Project Cards */
.project-card {
    background-color: #f9f9f9;
    padding: 20px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.project-card h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.project-card a {
    color: #0366d6;
    text-decoration: none;
}

.project-card a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    background-color: #24292f;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer p {
    font-size: 1rem;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your GitHub Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Your Name or Project Title</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome to my personal GitHub page! I'm a software developer passionate about coding, open-source contributions, and building awesome projects. Check out my repositories below!</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <div class="container">
            <h2>My Projects</h2>
            <div class="project-card">
                <h3>Project One</h3>
                <p>A brief description of your project. <a href="https://github.com/your-username/project-one" target="_blank">View on GitHub</a></p>
            </div>
            <div class="project-card">
                <h3>Project Two</h3>
                <p>A brief description of your project. <a href="https://github.com/your-username/project-two" target="_blank">View on GitHub</a></p>
            </div>
            <!-- Add more projects as needed -->
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2>Contact</h2>
            <p>Feel free to reach out to me for collaborations or just to chat!</p>
            <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Your Name. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
