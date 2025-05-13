<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sorveteria Delícia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #7b2cbf;
            padding: 20px;
            text-align: center;
            color: white;
        }
        header h1 {
            margin: 0;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            color: #7b2cbf;
        }
        .produtos {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .produto {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            width: 200px;
            padding: 15px;
            text-align: center;
        }
        .produto img {
            width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #7b2cbf;
            color: white;
            text-align: center;
            padding: 15px 20px;
            margin-top: 40px;
        }
        /* Responsividade */
        @media(max-width: 600px) {
            .produtos {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Sabor Do Açaí </h1>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#produtos">Nossos Sabores</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section id="sobre">
        <h2>Bem-vindo ao Sabor Do Açaí! </h2>
        <p>Venha experimentar os melhores sabores de sorvete na nossa loja! Temos uma variedade de opções para agradar todos os gostos, desde os clássicos até os mais inovadores. Nosso compromisso é oferecer qualidade, sabor e um ambiente acolhedor para você aproveitar momentos especiais.</p>
    </section>

    <section id="produtos">
        <h2>Nossos Sabores</h2>
</body>
