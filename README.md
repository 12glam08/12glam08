<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bienvenida a Glam Haven GT</h1>
    </header>
    <section class="productos">
        <div class="producto">
            <img src="images/labial.jpg" alt="Labial">
            <h3>Labial Mate</h3>
            <p>Q50.00</p>
        </div>
        <div class="producto">
            <img src="images/sombras.jpg" alt="Paleta de sombras">
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

body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #ffe6f2;
    color: #333;
}

header {
    background: linear-gradient(90deg, #ff69b4, #ff1493);
    color: white;
    padding: 20px;
    font-size: 26px;
    font-weight: bold;
}

.productos {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px;
}

.producto {
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin: 15px;
    width: 250px;
    background: white;
    text-align: center;
}

.producto img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

button {
    background-color: #ff69b4;
    color: white;
    border: none;
    padding: 10px 15px;
    margin-top: 10px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    transition: 0.3s;
}

button:hover {
    background-color: #ff1493;
}

footer {
    background: linear-gradient(90deg, #ff69b4, #ff1493);
    color: white;
    padding: 15px;
    margin-top: 20px;
}

.redes a {
    margin: 0 10px;
    color: white;
    text-decoration: none;
    font-size: 20px;
    font-weight: bold;
}

