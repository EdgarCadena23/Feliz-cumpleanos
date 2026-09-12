<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Cumpleaños ❤️</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            min-height: 100vh;
            font-family: Georgia, 'Times New Roman', serif;
            background: linear-gradient(135deg, #180b1c, #35152f, #541f45);
            color: #fff;
            overflow-x: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 25px;
        }

        .container {
            width: 100%;
            max-width: 750px;
            position: relative;
            z-index: 2;
        }

        .card {
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 25px;
            padding: 45px 35px;
            text-align: center;
            box-shadow: 0 20px 60px rgba(0,0,0,0.45);
            backdrop-filter: blur(10px);
            animation: aparecer 1.5s ease;
        }

        .heart {
            font-size: 55px;
            animation: latido 1.5s infinite;
            margin-bottom: 15px;
        }

        h1 {
            font-size: 48px;
            margin-bottom: 10px;
            font-weight: normal;
        }

        .subtitle {
            font-size: 23px;
            color: #ffd6ed;
            margin-bottom: 30px;
            font-style: italic;
        }

        .line {
            width: 100px;
            height: 2px;
            background: #ffd6ed;
            margin: 0 auto 30px;
            opacity: 0.7;
        }

        .message {
            text-align: left;
            font-size: 18px;
            line-height: 1.8;
            color: #fff5fa;
        }

        .message p {
            margin-bottom: 20px;
        }

        .signature {
            text-align: right;
            margin-top: 30px;
            font-size: 20px;
            color: #ffd6ed;
            font-style: italic;
        }

        .final {
            margin-top: 35px;
            font-size: 25px;
            color: #fff;
            font-weight: bold;
        }

        .music-button {
            display: inline-block;
            margin-top: 30px;
            padding: 13px 25px;
            border-radius: 30px;
            background: rgba(255,255,255,0.15);
            color: white;
            text-decoration: none;
            border: 1px solid rgba(255,255,255,0.3);
            transition: 0.3s;
            font-family: Arial, sans-serif;
        }

        .music-button:hover {
            background: rgba(255,255,255,0.25);
            transform: scale(1.05);
        }

        .balloon {
            position: fixed;
            bottom: -120px;
            font-size: 55px;
            animation: subir linear infinite;
            opacity: 0.75;
            z-index: 1;
        }

        .b1 {
            left: 8%;
            animation-duration: 11s;
        }

        .b2 {
            left: 25%;
            animation-duration: 14s;
            animation-delay: 3s;
        }

        .b3 {
            right: 20%;
            animation-duration: 12s;
            animation-delay: 1s;
        }

        .b4 {
            right: 7%;
            animation-duration: 15s;
            animation-delay: 5s;
        }

        .confetti {
            position: fixed;
            top: -20px;
            font-size: 20px;
            animation: caer linear infinite;
            z-index: 1;
        }

        .c1 {
            left: 15%;
            animation-duration: 7s;
        }

        .c2 {
            left: 40%;
            animation-duration: 9s;
            animation-delay: 2s;
        }

        .c3 {
            left: 65%;
            animation-duration: 8s;
            animation-delay: 1s;
        }

        .c4 {
            left: 85%;
            animation-duration: 10s;
            animation-delay: 4s;
        }

        @keyframes aparecer {
            from {
                opacity: 0;
                transform: translateY(30px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes latido {
            0%, 100% {
                transform: scale(1);
            }

            50% {
                transform: scale(1.15);
            }
        }

        @keyframes subir {
            0% {
                transform: translateY(0) rotate(0deg);
            }

            100% {
                transform: translateY(-120vh) rotate(15deg);
            }
        }

        @keyframes caer {
            0% {
                transform: translateY(-30px) rotate(0deg);
            }

            100% {
                transform: translateY(110vh) rotate(360deg);
            }
        }

        @media (max-width: 600px) {
            body {
                padding: 15px;
            }

            .card {
                padding: 35px 22px;
            }

            h1 {
                font-size: 38px;
            }

            .subtitle {
                font-size: 20px;
            }

            .message {
                font-size: 16px;
                line-height: 1.7;
            }

            .final {
                font-size: 21px;
            }
        }
    </style>
</head>

<body>

    <!-- Globos -->
    <div class="balloon b1">🎈</div>
    <div class="balloon b2">🎈</div>
    <div class="balloon b3">🎈</div>
    <div class="balloon b4">🎈</div>

    <!-- Confeti -->
    <div class="confetti c1">✨</div>
    <div class="confetti c2">💖</div>
    <div class="confetti c3">🎉</div>
    <div class="confetti c4">✨</div>

    <div class="container">
        <div class="card">

            <div class="heart">❤️</div>

            <h1>Feliz cumpleaños</h1>

            <div class="subtitle">
                Para alguien muy especial ❤️
            </div>

            <div class="line"></div>

            <div class="message">

                <p>
                    Hoy quiero aprovechar este día para recordarte lo muchísimo
                    que te quiero y lo importante que eres para mí.
                </p>

                <p>
                    Hemos pasado por diferentes etapas, hemos compartido
                    momentos, risas, pláticas y también cosas que solamente
                    nosotros entendemos. Y aunque en algún momento las cosas
                    pudieron haber sido diferentes, me alegra muchísimo saber
                    que hoy podemos llevarnos tan bien y tener la confianza
                    que tenemos.
                </p>

                <p>
                    Quiero que sepas que eres una persona que ocupa un lugar
                    muy especial en mi vida. De esas personas que uno no quiere
                    perder y que, pase lo que pase, siempre quiere tener cerca.
                </p>

                <p>
                    Siempre voy a estar para ti. Para escucharte cuando
                    necesites hablar, para apoyarte cuando las cosas no estén
                    tan bien, para celebrar contigo cuando tengas algo bonito
                    que celebrar y, por supuesto, para hacerte reír cuando
                    lo necesites.
                </p>

                <p>
                    Aunque probablemente no siempre te lo diga, quiero que
                    nunca dudes de lo mucho que significas para mí.
                </p>

                <p>
                    Espero que este nuevo año de tu vida venga lleno de
                    momentos increíbles, sueños cumplidos, personas que te
                    quieran bonito y muchísimas razones para sonreír.
                </p>

                <p>
                    Nunca dejes de ser esa persona tan especial que eres.
                    Sigue siendo tú, sigue riéndote así, sigue haciendo
                    locuras y sigue persiguiendo todo aquello que quieres,
                    porque sé que eres capaz de conseguir muchísimo.
                </p>

                <p>
                    Y si algún día se te olvida lo increíble que eres,
                    aquí voy a estar para recordártelo.
                </p>

                <p>
                    Te quiero muchísimo y espero que tengas un cumpleaños
                    tan bonito como tú. ❤️
                </p>

            </div>

            <div class="signature">
                Con mucho cariño ❤️
            </div>

            <div class="final">
                Feliz cumpleaños, hermosa. 🎂❤️✨
            s

</body>
</html>w
