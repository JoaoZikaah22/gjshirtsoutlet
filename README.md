<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GJ OUTLET</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            position: relative;
            overflow-x: hidden;
        }
        header {
            padding: 20px;
            position: relative;
        }
        img.logo {
            max-width: 150px;
            height: auto;
        }
        .product {
            margin: 40px 0;
            border-top: 1px solid white;
            padding-top: 20px;
            position: relative;
        }
        .buy-button {
            display: inline-block;
            background-color: white;
            color: black;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 10px;
        }
        footer {
            margin-top: 30px;
            padding: 20px;
            border-top: 1px solid white;
            position: relative;
        }
        /* Detalhes de fundo */
        .background-detail {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0.05;
        }
        .line-detail {
            width: 100%;
            height: 4px;
            background: linear-gradient(to right, transparent 20%, white 40%, transparent 60%);
            margin: 30px 0;
            opacity: 0.2;
        }
        .wavy-line {
            width: 100%;
            height: 4px;
            background: url('linha-ondulada.png') repeat-x;
            margin: 20px 0;
            opacity: 0.3;
        }
        .football-shirt-icon, .team-icon, .football-stadium-icon {
            position: absolute;
            font-size: 80px;
            color: white;
            opacity: 0.15;
        }
        .football-shirt-icon {
            top: 150px;
            left: 10%;
        }
        .team-icon {
            bottom: 200px;
            right: 15%;
        }
        .football-stadium-icon {
            top: 450px;
            right: 60%;
         }
        }
    </style>
</head>
<body>
    <div class="background-detail"></div>

    <header>
        <img src="logo.jpg" alt="Logo GJ OUTLET" class="logo">
        <h1>GJ OUTLET</h1>
    </header>

    <!-- Detalhes visuais -->
    <div class="football-shirt-icon">⚽</div> <!-- Ícone de camisa de futebol -->
    <div class="football-stadium-icon">🏟️</div> <!-- Ícone de um etádio -->
    <div class="team-icon">🏆</div> <!-- Ícone de troféu -->

    <section class="product">
        <p>Bem-vindo ao GJ OUTLET! Compre as melhores camisas do mercado, e com direito a personalisação!</p>
        <div class="line-detail"></div> <!-- Linha reta decorativa -->
        <div class="wavy-line"></div> <!-- Linha ondulada decorativa -->
        <a href="https://wa.me/message/BAQ5OCR6QC7SG1" class="buy-button" target="_blank">Comprar pelo WhatsApp</a>
    </section>

    <footer>
        <p>&copy; 2024 GJ OUTLET&trade; Todos os direitos reservados.</p>
    </footer>
</body>
</html>
