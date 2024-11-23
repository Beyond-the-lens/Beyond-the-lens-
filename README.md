<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beyond the Lens</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Beyond the Lens</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Welcome to Beyond the Lens</h1>
        <p>Discover the world through a different perspective.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>"Beyond the Lens" is a place where stories come alive, captured through the art of photography and storytelling.</p>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <img src="https://via.placeholder.com/300" alt="Sample Image 1">
            <img src="https://via.placeholder.com/300" alt="Sample Image 2">
            <img src="https://via.placeholder.com/300" alt="Sample Image 3">
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>© 2024 Beyond the Lens. All rights reserved.</p>
    </footer>
</body>
</html>
