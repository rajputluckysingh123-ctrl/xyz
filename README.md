
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>

    <h1>Main Heading</h1>
    <p>This is a paragraph of text.</p>
    <a href="https://example.com">This is a link</a>

</body>
</html>
talwnd
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: system-ui, -apple-system, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #1e293b;
            color: #fff;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 1.5rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: #f1f5f9;
            text-align: center;
            padding: 4rem 2rem;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .btn {
            display: inline-block;
            background: #2563eb;
            color: #fff;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 6px;
            margin-top: 1rem;
        }
        main {
            max-width: 900px;
            margin: 2rem auto;
            padding: 0 2rem;
        }
        section {
            margin-bottom: 3rem;
        }
        footer {
            background: #1e293b;
            color: #cbd5e1;
            text-align: center;
            padding: 1.5rem;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <h2>BrandName</h2>
        <nav>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Welcome to My Website</h1>
        <p>A clean, responsive starter template built with HTML and CSS.</p>
        <a href="#contact" class="btn">Get Started</a>
    </div>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>Write a short introduction about who you are, what you do, or what this website is about.</p>
        </section>

        <section id="services">
            <h2>Services</h2>
            <ul>
                <li><strong>Service One:</strong> Brief description of what you offer.</li>
                <li><strong>Service Two:</strong> Brief description of your second offering.</li>
                <li><strong>Service Three:</strong> Brief description of your third offering.</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email us at: <a href="mailto:hello@example.com">hello@example.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 BrandName. All rights reserved.</p>
    </footer>

</body>
</html>
