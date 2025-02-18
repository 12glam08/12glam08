<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glam Haven GT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #ff69b4;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }
        .producto {
            border: 1px solid #ddd;
            padding: 15px;
            margin: 10px;
            width: 250px;
            text-align: center;
        }
        .producto img {
            width: 100%;
            height: auto;
        }
        footer {
            background-color: #ff69b4;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .redes a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <header>
        Bienvenida a Glam Haven GT
    </header>
    <section class="productos">
        <div class="producto">
            <img src="labial.jpg" alt="Labial">
            <h3>Labial Mate</h3>
            <p>Q50.00</p>
        </div>
        <div class="producto">
            <img src="sombras.jpg" alt="Paleta de sombras">
            <h3>Paleta de Sombras</h3>
            <p>Q120.00</p>
        </div>
    </section>
    <footer>
        <p>Síguenos en nuestras redes:</p>
        <div class="redes">
            <a href="https://www.instagram.com/glam_haven_gt" target="_blank">Instagram</a>
            <a href="#">Facebook</a>
        </div>
    </footer>
</body>
</html>
