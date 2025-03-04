<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <h1>My Portfolio</h1>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Welcome to my portfolio! I am a passionate web developer with a knack for creating beautiful and functional websites. I love coding and exploring new technologies.</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <article class="project">
                <h3>Project Title 1</h3>
                <p>Description of the project goes here. It showcases my skills in HTML, CSS, and JavaScript.</p>
                <a href="https://example.com/project1" target="_blank">View Project</a>
            </article>
            <article class="project">
                <h3>Project Title 2</h3>
                <p>Description of the project goes here. It highlights my work with frameworks like React and Vue.js.</p>
                <a href="https://example.com/project2" target="_blank">View Project</a>
            </article>
            <article class="project">
                <h3>Project Title 3</h3>
                <p>Description of the project goes here. This project demonstrates my skills in backend development with Node.js.</p>
                <a href="https://example.com/project3" target="_blank">View Project</a>
            </article>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 My Portfolio. All rights reserved.</p>
    </footer>
</body>

</html>
