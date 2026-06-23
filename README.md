<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #0078d7;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        nav {
            background: #005fa3;
            padding: 1rem;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        section {
            padding: 3rem 10%;
        }

        .hero {
            text-align: center;
            background: #f4f4f4;
            padding: 4rem 2rem;
        }

        .button {
            display: inline-block;
            background: #0078d7;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }

        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 1.5rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <p>Your tagline goes here</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <h2>Build Something Amazing</h2>
        <p>This is a simple starter template for your website.</p>
        <a href="#contact" class="button">Get Started</a>
    </section>

    <section id="about">
        <h2>About</h2>
        <p>Add information about yourself, your company, or your project here.</p>
    </section>

    <section id="services">
        <h2>Services</h2>
        <p>Describe what you offer.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: your@email.com</p>
    </section>

    <footer>
        <p>&copy; 2026 My Website. All rights reserved.</p>
    </footer>

</body>
</html>
