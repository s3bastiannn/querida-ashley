# querida-ashley

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Querida Ashley</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      background-image: url('https://imgs.search.brave.com/zYpu97P7TqUqcg81fIcJeHJzYiPPscN2NP_ghIkjUps/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9jYXBy/aWNoby5hYnJpbC5j/b20uYnIvd3AtY29u/dGVudC91cGxvYWRz/LzIwMTkvMTIvcGFy/YS10b2Rvcy1vcy1n/YXJvdG9zLXF1ZS1q/YS1hbWVpLXBzLWFp/bmRhLWFtby12b2Nl/LXBldGVyLWZsb3Jl/cy5qcGc_cXVhbGl0/eT04NSZzdHJpcD1p/bmZv');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      overflow-x: hidden;
    }

    .contenedor {
      max-width: 900px;
      margin: 50px auto;
      padding: 20px;
      border-radius: 20px;
    }

    h1 {
      text-align: center;
      font-family: 'Pacifico', cursive;
      font-size: 3em;
      color: #ffe4e1;
      margin-bottom: 20px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }

    .mensaje {
      background: rgba(255, 255, 255, 0.6);
      padding: 25px;
      border-radius: 15px;
      font-size: 1.2em;
      line-height: 1.6;
      color: #333;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    .mensaje p {
      margin-bottom: 15px;
      text-align: justify;
    }

    .firma {
      margin-top: 30px;
      text-align: right;
      font-family: 'Pacifico', cursive;
      font-size: 1.5em;
      font-style: italic;
      color: #ffe4e1;
    }

    .gif-hello {
      margin: 20px auto 10px;
      text-align: center;
    }

    .gif-hello img {
      width: 150px;
      height: auto;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }

    .imagen-final {
      margin-top: 20px;
      text-align: center;
    }

    .imagen-final img {
      max-width: 100%;
      height: auto;
      border-radius: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    /* Estilo para los corazones */
    .heart {
      position: fixed;
      top: -10px;
      width: 20px;
      height: 20px;
      background-color: pink;
      transform: rotate(45deg);
      animation: fall 8s linear infinite;
      opacity: 0.8;
      z-index: 0;
    }

    .heart::before,
    .heart::after {
      content: '';
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: pink;
      border-radius: 50%;
    }

    .heart::before {
      top: -10px;
      left: 0;
    }

    .heart::after {
      left: -10px;
      top: 0;
    }

    @keyframes fall {
      0% {
        transform: translateY(-10px) rotate(45deg);
        opacity: 1;
      }
      100% {
        transform: translateY(100vh) rotate(45deg);
        opacity: 0;
      }
    }
  </style>
</head>
<body>

<!-- Corazones cayendo -->
<script>
  for (let i = 0; i < 25; i++) {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = 4 + Math.random() * 4 + "s";
    document.body.appendChild(heart);
  }
</script>

<div class="contenedor">
  <h1>Querida Ashley:</h1>
  <div class="mensaje">
    <p>Sé que aún no nos conocemos tanto como quisiera, pero por eso mismo estoy aquí, escribiéndote esto con sinceridad.</p>
    <p>Desde el primer momento en que te vi, algo en ti llamó mi atención. Tal vez fue tu sonrisa, tus ojos, tu forma de estar en el mundo... No lo sé con exactitud, pero lo sentí. Y desde entonces, no he podido dejar de pensar en ti.</p>
    <p>No te escribo esto para impresionarte, sino para que sepas que quiero conocerte de verdad. Me encantaría que me dieras una oportunidad, aunque sea pequeña, para ver si el destino tiene algo preparado para nosotros.</p>
    <p>Como dice Lara Jean en “A todos los chicos de los que me enamoré”:<br>
    "La gente entra en tu vida por una razón, por una temporada o para toda la vida."<br>
    Y yo... espero poder quedarme el tiempo que tú me permitas.</p>
    <p>No te prometo perfección, pero sí honestidad, detalles sinceros y ganas de hacerte sonreír.</p>
    <p>Tal vez esto sea un riesgo, como enviar una carta que tal vez nunca se lea, pero como también dijo Peter Kavinsky:<br>
    “No estoy tratando de ser alguien perfecto. Estoy tratando de ser alguien que vale la pena.”</p>
    <p>Y eso quiero ser para ti: alguien que valga la pena conocer.</p>
  </div>

  <div class="firma">
    <p>Con cariño,<br>Sebastian</p>
  </div>

  <div class="gif-hello">
    <img src="https://imgs.search.brave.com/8IcGpX-lhqB4ja-tvgDh4R1OLil_1lNIEhNgSItTLtI/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YTEuZ2lwaHkuY29t/L21lZGlhL3YxLlky/bGtQVGM1TUdJM05q/RXhiR05tWkhJek1E/UjZlV1Z5YmpBd2JH/SXpibXMzYTJKdk1Y/RTFiMjg0WVhrMWFY/SndaVE5tZUNabGNE/MTJNVjluYVdaelgz/TmxZWEpqYUNaamRE/MW4vVXZhN2gxd1RJ/ejlXS2liMHcxLzIw/MC5naWY.gif" />
  </div>

  <div class="imagen-final">
    <img src="https://imgs.search.brave.com/24GCazsBXCo4rgfKR5sdtqVkOaFpam153r9rzilNBE8/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9jb250/ZW50Mi5mbG93d293/LWltYWdlcy5jb20v/ZGF0YS9mbG93ZXJz/LzUyNHg1MjQvMzUv/MTcyNzE4NjI1NF8x/MzM1OTgzNS5qcGc" alt="Tulipanes románticos" />
  </div>
</div>

</body>
</html>
