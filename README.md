# My-store<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Location Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
        }
        iframe {
            width: 100%;
            height: 400px;
            border: none;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Location</h1>
        <p>Check out this spot on the map below!</p>
    </header>
    <div class="container">
        <h2>Location Map</h2>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.0192!2d-122.4194!3d37.7749!2m3!1f0!2f0!3f0!3m2!1i1024!2j768!4f13.1!3m3!1m2!1s0x8085808c0c0c0c0c%3A0x0!2zMzcuNzc0OSwgLTEyMi40MTk0!5e0!3m2!1sen!2sus!4v1234567890" allowfullscreen="" loading="lazy"></iframe>
    </div>
    <footer>
        <p>&copy; 2023 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
