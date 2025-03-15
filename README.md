<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domain Slayer</title>
    <style>
        /* Resetando margens e padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Definindo o fundo roxo escuro */
        body {
            background-color: #2C0A69;
            font-family: Arial, sans-serif;
            color: #fff;
            line-height: 1.6;
        }

        /* Centralizando o título principal */
        header {
            text-align: center;
            padding: 50px 20px;
            margin-bottom: 40px;
        }

        h1 {
            font-size: 4em;
            font-weight: bold;
            color: #ffffff;
            text-transform: uppercase;
            letter-spacing: 5px;
            text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.7);
            animation: fadeIn 2s ease-out, moveIn 2s ease-out;
        }

        /* Efeito de fade-in e 3D no título */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes moveIn {
            from {
                transform: translateY(-50px);
            }
            to {
                transform: translateY(0);
            }
        }

        /* Centralizando os produtos */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            padding: 30px;
        }

        /* Cartões de produto */
        .product {
            background-color: #1f1f1f;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }

        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .product-info {
            padding: 20px;
            text-align: center;
        }

        .product-info h3 {
            margin-bottom: 15px;
            font-size: 18px;
        }

        .product-info p {
            margin-bottom: 20px;
            font-size: 14px;
            color: #ccc;
        }

        /* Botão de compra */
        .btn-buy {
            background-color: #f44336;
            color: #fff;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .btn-buy:hover {
            background-color: #d32f2f;
        }

        .btn-buy:active {
            transform: scale(0.98);
        }

        /* Animação no hover do cartão */
        .product:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }

        /* Animação ao passar o mouse sobre a imagem */
        .product img {
            transition: transform 0.3s ease;
        }

        .product:hover img {
            transform: scale(1.05);
        }

        /* Estilo para o menu do rodapé (botão Discord) */
        footer {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        footer a {
            display: inline-block;
            background-color: #7289DA;
            color: #fff;
            font-size: 18px;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        footer a:hover {
            background-color: #5b6eae;
        }

    </style>
</head>
<body>

    <header>
        <h1>Domain Slayer</h1>
        <p>Compre bots poderosos para o seu servidor Discord</p>
    </header>

    <div class="container">
        <!-- Produto 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/400x200/000000/FFFFFF/?text=Bot+1" alt="Bot 1">
            <div class="product-info">
                <h3>Bot Discord 1</h3>
                <p>Este é um bot super útil para moderar o seu servidor Discord!</p>
                <button class="btn-buy" onclick="window.location.href='https://example.com/compra-bot-1'">Comprar - $4.00</button>
            </div>
        </div>

        <!-- Produto 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/400x200/000000/FFFFFF/?text=Bot+2" alt="Bot 2">
            <div class="product-info">
                <h3>Bot Discord 2</h3>
                <p>Com recursos avançados, este bot vai transformar seu servidor!</p>
                <button class="btn-buy" onclick="window.location.href='https://example.com/compra-bot-2'">Comprar - $4.00</button>
            </div>
        </div>

        <!-- Produto 3 -->
        <div class="product">
            <img src="https://via.placeholder.com/400x200/000000/FFFFFF/?text=Bot+3" alt="Bot 3">
            <div class="product-info">
                <h3>Bot Discord 3</h3>
                <p>Excelente para automação e integração de servidores no Discord.</p>
                <button class="btn-buy" onclick="window.location.href='https://example.com/compra-bot-3'">Comprar - $4.00</button>
            </div>
        </div>

        <!-- Produto 4 -->
        <div class="product">
            <img src="https://via.placeholder.com/400x200/000000/FFFFFF/?text=Bot+4" alt="Bot 4">
            <div class="product-info">
                <h3>Bot Discord 4</h3>
                <p>Um bot completo para gerenciar seu servidor de forma eficiente.</p>
                <button class="btn-buy" onclick="window.location.href='https://example.com/compra-bot-4'">Comprar - $4.00</button>
            </div>
        </div>
    </div>

    <!-- Menu de navegação -->
    <footer>
        <a href="https://discord.com/invite/seu_link_do_servidor" target="_blank">Entrar no Discord</a>
    </footer>

</body>
</html>
