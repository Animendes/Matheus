# Animendes
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 1rem;
            text-decoration: none;
        }
        .container {
            padding: 2rem;
        }
        section {
            margin-bottom: 2rem;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .carousel {
            display: flex;
            overflow-x: scroll;
            scroll-snap-type: x mandatory;
        }
        .carousel::-webkit-scrollbar {
            display: none; /* Esconde a barra de rolagem no Chrome */
        }
        .carousel-item {
            flex: 0 0 auto;
            width: 300px;
            margin-right: 1rem;
            scroll-snap-align: start;
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* Proporção de 16:9 */
            height: 0;
            overflow: hidden;
            max-width: 100%;
            background: #000;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Animendes</h1>
    </header>
    <nav>
        <a href="#videos">Vídeos</a>
        <a href="#imagens">Imagens</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <section id="videos">
            <h2>Vídeos</h2>
            <div class="carousel">
                <div class="carousel-item">
                    <div class="video-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/Lsp3CeMutOc?si=mtRYZUSk_bmicuX8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="video-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/mp2xnktzmuA?si=bcrOoLfweHv7BJn-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="video-container">
                        <iframe src="https://www.youtube.com/embed/ID_DO_VIDEO3" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </div>
                <!-- Adicione mais vídeos conforme necessário -->
            </div>
        </section>
        <section id="imagens">
            <h2>Imagens</h2>
            <img src="caminho/para/sua-imagem.jpg" alt="Descrição da imagem" width="800">
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <p>Entre em contato conosco pelo telefone (00) 1234-5678 ou email@example.com.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Minha Empresa. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
