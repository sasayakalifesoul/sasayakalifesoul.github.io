<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Art Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #e0e0e0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 4rem 2rem 2rem;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 2px;
            color: #ffffff;
        }

        header p {
            color: #888888;
            font-style: italic;
            margin-top: 0.5rem;
        }

        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .art-item {
            background-color: #1e1e1e;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            transition: transform 0.3s ease;
        }

        .art-item:hover {
            transform: translateY(-5px);
        }

        .art-item img {
            width: 100%;
            height: 350px;
            object-fit: cover;
            display: block;
        }

        .art-info {
            padding: 1.5rem;
        }

        .art-info h3 {
            margin: 0 0 0.5rem 0;
            color: #ffffff;
        }

        .art-info p {
            margin: 0;
            color: #aaaaaa;
            font-size: 0.9rem;
        }

        footer {
            text-align: center;
            padding: 4rem 2rem;
            color: #666666;
            font-size: 0.85rem;
            border-top: 1px solid #222222;
            margin-top: 4rem;
        }
    </style>
</head>
<body>

   <header>
    <h1>Artist Portfolio</h1>
    <p>A collection of visual works</p>
</header>

<main>
    <section class="gallery">
        <div class="art-item">
            <img src="art 1.jpg" alt="Artwork 1">
            <div class="art-info">
                <h3>Artwork Title One</h3>
                <p>Medium / Year</p>
            </div>
        </div>

        <div class="art-item">
            <img src="art 2.jpg" alt="Artwork 2">
            <div class="art-info">
                <h3>Artwork Title Two</h3>
                <p>Medium / Year</p>
            </div>
        </div>

        <div class="art-item">
            <img src="art 3.jpg" alt="Artwork 3">
            <div class="art-info">
                <h3>Artwork Title Three</h3>
                <p>Medium / Year</p>
            </div>
        </div>

        <div class="art-item">
            <img src="art 4.jpg" alt="Artwork 4">
            <div class="art-info">
                <h3>Artwork Title Four</h3>
                <p>Medium / Year</p>
            </div>
        </div>

        <div class="art-item">
            <img src="art 5.jpg" alt="Artwork 5">
            <div class="art-info">
                <h3>Artwork Title Five</h3>
                <p>Medium / Year</p>
            </div>
        </div>

        <div class="art-item">
            <img src="art 6.jpg" alt="Artwork 6">
            <div class="art-info">
                <h3>Artwork Title Six</h3>
                <p>Medium / Year</p>
            </div>
        </div>
    </section>
</main>

<footer>
    <p>&copy; Anonymous Artist. All rights reserved.</p>
</footer>
