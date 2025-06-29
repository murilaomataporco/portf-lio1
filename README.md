<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfólio Fotográfico">
    <title>Portfólio Fotográfico</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>Meu Portfólio Fotográfico</h1>
            <nav>
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Galeria</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="gallery">
        <h2>Galeria de Fotos</h2>
        <div class="gallery-grid">
            <div class="gallery-item">
                <a href="images/foto1.jpg" target="_blank">
                    <img src="img/imagem 1.png" alt="Foto 1">
                </a>
            </div>
            <div class="gallery-item">
                <a href="images/foto2.jpg" target="_blank">
                    <img src="images/foto2_thumb.jpg" alt="Foto 2">
                </a>
            </div>
            <div class="gallery-item">
                <a href="images/foto3.jpg" target="_blank">
                    <img src="images/foto3_thumb.jpg" alt="Foto 3">
                </a>
            </div>
            <div class="gallery-item">
                <a href="images/foto4.jpg" target="_blank">
                    <img src="images/foto4_thumb.jpg" alt="Foto 4">
                </a>
            </div>
            <!-- Adicione mais imagens conforme necessário -->
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Meu Portfólio Fotográfico. Todos os direitos reservados.</p>
        </div>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to bottom right, #6a11cb, #2575fc); /* Degradê de roxo para azul */
    color: #333;
}

header {
    background-color: rgba(0, 0, 0, 0.7); /* Fundo escuro semitransparente */
    color: #fff;
    padding: 20px 0;
}

header .container {
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 2rem;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section.gallery {
    padding: 40px 0;
    text-align: center;
}

section.gallery h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    padding: 0 20px;
}

.gallery-item {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
}

.gallery-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    transition: transform 0.3s ease-in-out;
}

.gallery-item img:hover {
    transform: scale(1.1);
}

footer {
    background-color: rgba(0, 0, 0, 0.7); /* Fundo escuro semitransparente */
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

footer p {
    font-size: 0.9rem;
}
