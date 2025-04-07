<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Cleaning Business</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            padding: 10px 20px;
            color: white;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background-image: url('your-image.jpg'); /* Replace with your image */
            height: 400px;
            background-size: cover;
            color: white;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        .hero h2 {
            font-size: 3em;
            margin: 0;
        }
        .cta-button {
            background-color: #4CAF50;
            padding: 15px 25px;
            color: white;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
        }
        .services, .about, .contact {
            padding: 40px 20px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Cleaning Business</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero" id="home">
    <h2>Professional Cleaning Services You Can Trust</h2>
    <a href="#contact" class="cta-button">Get a Free Quote</a>
</div>

<section class="services" id="services">
    <h2>Our Services</h2>
    <div>
        <h3>Residential Cleaning</h3>
        <p>We make your home shine, from top to bottom.</p>
    </div>
    <div>
        <h3>Commercial Cleaning</h3>
        <p>Your office will always be spotless and professional.</p>
    </div>
    <div>
        <h3>Deep Cleaning</h3>
        <p>For those hard-to-reach places, we’ll handle it all.</p>
    </div>
</section>

<section class="about" id="about">
    <h2>About Us</h2>
    <p>We are a dedicated team of professionals who specialize in making spaces clean, fresh, and inviting.</p>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form action="submit_form.php" method="POST">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" required></textarea><br><br>
        <input type="submit" value="Send Message">
    </form>
</section>

<footer>
    <p>Contact us: info@yourcleaningservice.com | Call: (123) 456-7890</p>
    <p>&copy; 2025 Your Cleaning Business</p>
</footer>

</body>
</html>
