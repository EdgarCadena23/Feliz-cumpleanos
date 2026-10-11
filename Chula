<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para ti, chula ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    min-height: 100vh;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: Georgia, 'Times New Roman', serif;
    background: linear-gradient(135deg, #4a001f, #b31352, #ff709d, #ffd1df);
    position: relative;
}

/* Corazones visibles por TODA la pantalla */
.fondo-corazones {
    position: fixed;
    inset: 0;
    overflow: hidden;
    pointer-events: none;
    z-index: 0;
}

.corazon {
    position: absolute;
    color: #fff0f6;
    text-shadow: 0 0 12px #ffb3d0, 0 0 25px #ff4d88;
    animation: flotar linear infinite;
    opacity: 0.9;
    user-select: none;
}

@keyframes flotar {
    0% {
        transform: translateY(110vh) rotate(0deg) scale(0.7);
        opacity: 0;
    }
    15% {
        opacity: 0.9;
    }
    85% {
        opacity: 0.8;
    }
    100% {
        transform: translateY(-20vh) rotate(360deg) scale(1.3);
        opacity: 0;
    }
}

/* Brillos románticos */
.brillo {
    position: fixed;
    color: #fff;
    font-size: 25px;
    animation: brillar 2s ease-in-out infinite alternate;
    z-index: 1;
    pointer-events: none;
}

.b1 { top: 10%; left: 12%; }
.b2 { top: 20%; right: 12%; animation-delay: .5s; }
.b3 { bottom: 12%; left: 15%; animation-delay: 1s; }
.b4 { bottom: 15%; right: 13%; animation-delay: .7s; }

@keyframes brillar {
    from { opacity: .3; transform: scale(.8); }
    to { opacity: 1; transform: scale(1.3); }
}

/* Tarjeta central */
.mensaje {
    position: relative;
    z-index: 2;
    width: 90%;
    max-width: 850px;
    padding: 50px 30px;
    text-align: center;
    background: rgba(255, 238, 246, 0.18);
    border: 2px solid rgba(255, 255, 255, 0.7);
    border-radius: 35px;
    box-shadow: 0 0 35px rgba(255, 20, 100, 0.45),
                inset 0 0 30px rgba(255, 255, 255, 0.12);
    backdrop-filter: blur(3px);
    animation: aparecer 1.5s ease-out;
}

.corazon-central {
    font-size: clamp(55px, 10vw, 85px);
    margin-bottom: 20px;
    display: inline-block;
    filter: drop-shadow(0 0 15px #ffb6d0);
    animation: latido 1.2s infinite;
}

h1 {
    color: #fff;
    font-size: clamp(35px, 7vw, 65px);
    line-height: 1.2;
    margin-bottom: 30px;
    text-shadow: 0 3px 12px #9b174a;
    font-weight: normal;
}

.separador {
    color: #fff;
    font-size: 30px;
    margin-bottom: 25px;
    letter-spacing: 8px;
}

p {
    color: #fff;
    font-size: clamp(25px, 5vw, 39px);
    line-height: 1.6;
    font-weight: bold;
    text-shadow: 0 2px 12px rgba(100, 0, 40, .6);
}

.abrazos {
    font-size: clamp(35px, 7vw, 55px);
    margin-top: 25px;
    letter-spacing: 10px;
}

.dedicatoria {
    margin-top: 25px;
    color: #ffe4ef;
    font-size: clamp(17px, 3.5vw, 24px);
    font-style: italic;
}

@keyframes latido {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.15); }
}

@keyframes aparecer {
    from {
        opacity: 0;
        transform: translateY(25px) scale(.95);
    }
    to {
        opacity: 1;
        transform: translateY(0) scale(1);
    }
}

@media (max-width: 480px) {
    .mensaje {
        padding: 38px 20px;
    }

    h1 {
        margin-bottom: 22px;
    }

    p {
        line-height: 1.5;
    }
}
</style>
</head>

<body>

<div class="fondo-corazones" id="fondo"></div>

<div class="brillo b1">✨</div>
<div class="brillo b2">💕</div>
<div class="brillo b3">✨</div>
<div class="brillo b4">💗</div>

<div class="mensaje">
    <div class="corazon-central">❤️</div>

    <h1>Para ti, chula</h1>

    <div class="separador">♡ ♡ ♡</div>

    <p>
        Besos y abrazos<br>
        en tu corazón<br>
        para que te sientas<br>
        mejor, chula. 💗
    </p>

    <div class="abrazos">💋 🫂 💋</div>

    <div class="dedicatoria">
        Te mando todo mi cariño. ❤️
    </div>
</div>

<script>
const fondo = document.getElementById("fondo");
const simbolos = ["❤️", "💗", "💕", "💖", "💘", "♥"];

function crearCorazon() {
    const corazon = document.createElement("span");
    corazon.className = "corazon";
    corazon.textContent =
        simbolos[Math.floor(Math.random() * simbolos.length)];

    corazon.style.left = Math.random() * 100 + "%";
    corazon.style.fontSize = (20 + Math.random() * 35) + "px";
    corazon.style.animationDuration = (6 + Math.random() * 8) + "s";
    corazon.style.animationDelay = (Math.random() * 2) + "s";

    fondo.appendChild(corazon);

    setTimeout(() => {
        corazon.remove();
    }, 16000);
}

/* Muchos corazones flotando continuamente */
for (let i = 0; i < 35; i++) {
    setTimeout(crearCorazon, i * 180);
}

setInterval(crearCorazon, 300);
</script>

</body>
</html>
