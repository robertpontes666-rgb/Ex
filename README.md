<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nossas Memórias ❤️</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #fff5f5;
            color: #4a4a4a;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        header {
            padding: 50px 0;
        }
        h1 {
            color: #d63384;
            font-size: 2.5em;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        .memory-card {
            background: white;
            padding: 15px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .memory-card:hover {
            transform: scale(1.05);
        }
        .memory-card img {
            width: 100%;
            border-radius: 10px;
            height: 200px;
            object-fit: cover;
        }
        .memory-card p {
            margin-top: 10px;
            font-style: italic;
        }
    </style>
</head>
<body>

    <header>
        <h1>Nosso Álbum de Memórias ❤️</h1>
        <p>Cada momento ao seu lado é um presente.</p>
    </header>

    <div class="gallery">
        <div class="memory-card">
            <img src="https://via.placeholder.com/300" alt="Nossa primeira foto">
            <p>Onde tudo começou... 🌹</p>
        </div>

        <div class="memory-card">
            <img src="https://via.placeholder.com/300" alt="Viagem especial">
            <p>Aquela viagem inesquecível! ✈️</p>
        </div>

        <div class="memory-card">
            <img src="https://via.placeholder.com/300" alt="Jantar">
            <p>Nosso restaurante favorito. 🍝</p>
        </div>
    </div>

</body>
</html>
