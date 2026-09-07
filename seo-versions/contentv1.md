<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Discover modern web design and development services. Simple, responsive websites built for your business. Contact us for a free consultation and grow online.">
    <meta name="robots" content="index,follow">
    <title>Modern Web Design & Development Services | My Website</title>
    <link rel="canonical" href="https://www.mywebsite.com/">
    <!-- Open Graph -->
    <meta property="og:title" content="Modern Web Design & Development Services | My Website">
    <meta property="og:description" content="Discover modern web design and development services. Simple, responsive websites built for your business. Contact us for a free consultation and grow online.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.mywebsite.com/">
    <meta property="og:image" content="https://www.mywebsite.com/og-image.jpg">
    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Modern Web Design & Development Services | My Website">
    <meta name="twitter:description" content="Discover modern web design and development services. Simple, responsive websites built for your business. Contact us for a free consultation and grow online.">
    <meta name="twitter:image" content="https://www.mywebsite.com/og-image.jpg">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            color: #222;
            line-height: 1.6;
        }
        header {
            background: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
        }
        .hero {
            background: white;
            padding: 40px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 25px;
        }
        .hero h2 {
            margin-bottom: 15px;
        }
        .hero p {
            margin-bottom: 20px;
        }
        button {
            padding: 12px 24px;
            border: none;
            border-radius: 6px;
            background: #222;
            color: white;
            cursor: pointer;
        }
        button:hover {
            background: #444;
        }
        .cards {
            display: flex;
            gap: 20px;
            margin-bottom: 25px;
        }
        .card {
            flex: 1;
            background: white;
            padding: 25px;
            border-radius: 10px;
        }
        .card h3 {
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: white;
        }
    </style>
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "name": "My Website",
      "url": "https://www.mywebsite.com/",
      "logo": "https://www.mywebsite.com/logo.png",
      "contactPoint": {
        "@type": "ContactPoint",
        "telephone": "+1-555-555-5555",
        "contactType": "Customer service",
        "email": "hello@example.com"
      },
      "description": "Discover modern web design and development services. Simple, responsive websites built for your business. Contact us for a free consultation and grow online."
    }
    </script>
</head>
<body>
    <header>
        <h1>My Website</h1>
        <nav aria-label="Main navigation">
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <main id="home">
        <section class="hero">
            <h2>Welcome to My Website</h2>
            <p>This is a simple HTML, CSS and JavaScript website.</p>
            <button id="welcomeBtn" aria-label="Click to welcome">Click Me</button>
        </section>
        <section class="cards" id="services">
            <article class="card">
                <h3>Web Design</h3>
                <p>We create simple and modern websites.</p>
            </article>
            <article class="card">
                <h3>Development</h3>
                <p>We build responsive web applications.</p>
            </article>
        </section>
        <section class="hero" id="contact">
            <h2>Contact Us</h2>
            <p>Email: hello@example.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2026 My Website. All rights reserved.</p>
    </footer>
    <script>
        const button = document.getElementById("welcomeBtn");
        button.addEventListener("click", function () {
            alert("Welcome to my website!");
        });
    </script>
</body>
</html>