<!DOCTYPE html>
<html lang="sr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moja Lična Web Stranica</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            padding: 2rem;
        }
        .skills, .social-links, .gallery {
            margin-bottom: 2rem;
        }
        .skills ul, .social-links ul, .gallery ul {
            list-style-type: none;
            padding: 0;
        }
        .skills li, .social-links li {
            background: #fff;
            margin-bottom: 10px;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Dobrodošli na Moju Ličnu Web Stranicu</h1>
    </header>
    <div class="container">
        <section class="skills">
            <h2>Profesionalne Veštine</h2>
            <ul>
                <li>Veština 1</li>
                <li>Veština 2</li>
                <li>Veština 3</li>
                <li>Veština 4</li>
            </ul>
        </section>
        <section class="social-links">
            <h2>Pratite me na društvenim mrežama</h2>
            <ul>
                <li><a href="https://www.facebook.com" target="_blank">Facebook</a></li>
                <li><a href="https://www.twitter.com" target="_blank">Twitter</a></li>
                <li><a href="https://www.instagram.com" target="_blank">Instagram</a></li>
                <li><a href="https://www.linkedin.com" target="_blank">LinkedIn</a></li>
            </ul>
        </section>
        <section class="gallery">
            <h2>Galerija</h2>
            <ul>
                <li><img src="slika1.jpg" alt="Slika 1"></li>
                <li><img src="slika2.jpg" alt="Slika 2"></li>
                <li><img src="slika3.jpg" alt="Slika 3"></li>
                <li><img src="slika4.jpg" alt="Slika 4"></li>
            </ul>
        </section>
    </div>
</body>
</html>
