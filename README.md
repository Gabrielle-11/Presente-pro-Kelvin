<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Aniversário, Meu Amor!</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 20px;
            background-color: #ffffff; /* Fundo branco */
            color: #333;
            text-align: center;
            overflow-x: hidden; /* Para evitar barra de rolagem horizontal */
        }
        img {
            max-width: 100%;
            height: auto;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        audio {
            width: 100%;
            margin-bottom: 20px;
        }
        .message {
            font-size: 1.1em;
            line-height: 1.6;
            margin-bottom: 30px;
        }
        .love {
            color: #e44d26;
            font-weight: bold;
        }

        /* Animação dos corações */
        .heart {
            color: #e44d26;
            font-size: 2em;
            position: fixed;
            animation: float 5s linear infinite, drift 3s ease-in-out infinite alternate;
            opacity: 0.7;
            z-index: -1; /* Para ficarem atrás do conteúdo principal */
        }

        @keyframes float {
            0% { transform: translateY(100vh) scale(1); opacity: 0.7; }
            100% { transform: translateY(-10vh) scale(0.5); opacity: 0; }
        }

        @keyframes drift {
            from { transform: translateX(-5vw); }
            to { transform: translateX(5vw); }
        }

        /* Posicionamento aleatório dos corações */
        .heart:nth-child(1) { left: 10vw; animation-delay: 0s; font-size: 1.5em; }
        .heart:nth-child(2) { left: 30vw; animation-delay: 1s; font-size: 2em; }
        .heart:nth-child(3) { left: 50vw; animation-delay: 2s; font-size: 1.8em; }
        .heart:nth-child(4) { left: 70vw; animation-delay: 0.5s; font-size: 2.2em; }
        .heart:nth-child(5) { left: 90vw; animation-delay: 1.5s; font-size: 1.6em; }
        .heart:nth-child(6) { left: 5vw; animation-delay: 2.5s; font-size: 2.5em; }
        .heart:nth-child(7) { left: 25vw; animation-delay: 0.8s; font-size: 1.9em; }
        .heart:nth-child(8) { left: 60vw; animation-delay: 1.8s; font-size: 2.1em; }
        .heart:nth-child(9) { left: 80vw; animation-delay: 0.2s; font-size: 1.7em; }
        .heart:nth-child(10) { left: 40vw; animation-delay: 2.8s; font-size: 2.3em; }
    </style>
</head>
<body>
    <div class="message">
        <p>"Essa música fala muito sobre o que ainda mora aqui dentro. Espero que, ao ouvir, você sinta um pouco da verdade que existe no meu coração."</p>
    </div>

    <img src="URL_DA_SUA_FOTO_AQUI" alt="Foto de vocês dois">

    <audio controls autoplay loop>
        <source src="https://youtu.be/eflklgCwNvw?si=Cc9GrjIIxHdHKvFo" type="audio/mpeg">
        Seu navegador não suporta o elemento de áudio.
    </audio>

    <div class="message love">
        <p>Ainda Te Amo Coroa ♥</p>
    </div>

    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
    <div class="heart">♥</div>
</body>
</html>
