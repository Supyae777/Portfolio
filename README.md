<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Poppins', sans-serif;
            color: #333;
            background: #f3f4f6;
        }
        header {
            background: #1f2937;
            color: #fff;
            padding: 2rem 1rem;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        nav {
            margin-top: 1rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: 600;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #60a5fa;
        }
        section {
            padding: 2rem;
            max-width: 1000px;
            margin: 2rem auto;
        }
        .about, .projects, .contact {
            background: #fff;
            border-radius: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            margin-bottom: 2rem;
            transition: transform 0.3s;
        }
        .about:hover, .projects:hover, .contact:hover {
            transform: translateY(-5px);
        }
        .projects ul {
            margin-top: 1rem;
        }
        .projects li {
            margin: 0.5rem 0;
        }
        .projects a {
            color: #3b82f6;
            text-decoration: none;
        }
        .projects a:hover {
            text-decoration: underline;
        }
        .contact p {
            margin: 0.5rem 0;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #1f2937;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="about" id="about">
        <h2>About Me</h2>
        <p>Welcome to my fashion portfolio! I am a passionate fashion student with a keen eye for design, creativity, and trends. My work reflects my dedication to blending art with style.</p>
    </section>

    <section class="projects" id="projects">
        <h2>Projects</h2>
        <ul>
            <li><a href="#">Project 1: Sustainable Fashion Collection</a></li>
            <li><a href="#">Project 2: Streetwear Design Portfolio</a></li>
            <li><a href="#">Project 3: Fashion Photography Showcase</a></li>
        </ul>
    </section>

    <section class="contact" id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourname@example.com</p>
        <p>Phone: +123 456 7890</p>
        <p>Instagram: <a href="#" target="_blank">instagram.com/yourname</a></p>
    </section>

    <footer>
        &copy; 2025 Your Name. All rights reserved.
    </footer>
</body>
</html>

