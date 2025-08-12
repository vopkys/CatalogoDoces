<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo H&H Doces</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Playfair Display', serif;
            background-color: #f8f8e8;
            margin: 0;
            padding: 0;
            color: #6b3e2e;
        }

        body {
    font-family: 'Open Sans', sans-serif;
}

h1, h2 {
    font-family: 'Prata', serif;
}


        header {
            text-align: center;
            padding: 15px;
        }
        header h1 {
            font-size: 2em;
            margin: 0;
        }
        header p {
            font-size: 1em;
            margin-top: -5px;
        }
        .produto {
            background-color: #ffd6d6;
            border-radius: 15px;
            padding: 10px;
            margin: 10px auto;
            display: flex;
            align-items: center;
            justify-content: space-between;
            max-width: 95%;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            flex-wrap: wrap;
        }
        .produto img {
            border-radius: 50%;
            width: 70px;
            height: 70px;
            object-fit: cover;
        }
        .produto-info {
            flex: 1 1 100%;
            margin-top: 10px;
        }
        .produto-info h2 {
            margin: 0;
            font-size: 1.2em;
        }
        .produto-info p {
            margin: 5px 0;
            font-size: 0.9em;
        }
        .preco {
            font-size: 1.1em;
            font-weight: bold;
            color: #b45f3a;
            margin-top: 5px;
        }
        @media (min-width: 600px) {
            .produto {
                flex-wrap: nowrap;
            }
            .produto-info {
                flex: 1;
                margin-left: 15px;
            }
            .preco {
                margin-top: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Catálogo</h1>
        <p>H&H DOCES</p>
        <p>🍰</p>
    </header>

    <div class="produto">
        <img src="morango.jpg" alt="Morango do Amor">
        <div class="produto-info">
            <h2>Morango do Amor</h2>
            <p>Morango envolvido em brigadeiro branco e caramelo caseiro. (10g)</p>
            <div class="preco">R$15</div>
        </div>
    </div>

    <div class="produto">
        <img src="pudim.jpg" alt="Pudim de leite condensado">
        <div class="produto-info">
            <h2>Pudim de leite condensado</h2>
            <p>Pudim feito com leite condensado e calda de caramelo. (..G)</p>
            <div class="preco">R$..</div>
        </div>
    </div>

    <div class="produto">
        <img src="torta-limao.jpg" alt="Torta de limão">
        <div class="produto-info">
            <h2>Torta de limão</h2>
            <p>Torta de limão com chantilly e raspinhas de limão. (..G)</p>
            <div class="preco">R$..</div>
        </div>
    </div>

    <div class="produto">
        <img src="torta-maracuja.jpg" alt="Torta de maracujá">
        <div class="produto-info">
            <h2>Torta de maracujá</h2>
            <p>Torta de maracujá com cobertura de maracujá. (..G)</p>
            <div class="preco">R$..</div>
        </div>
    </div>


</body>
</html>
