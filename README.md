<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Para ti 💖</title>
    <style>
      :root {
        --rosa: #ff4f87;
        --rosa-claro: #ffd5e3;
        --vino: #7a1631;
        --fondo: #fff6fa;
        --texto: #2d1a22;
      }

      * {
        box-sizing: border-box;
      }

      body {
        margin: 0;
        min-height: 100vh;
        display: grid;
        place-items: center;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        background: radial-gradient(circle at top, #ffe8f0, var(--fondo) 55%);
        color: var(--texto);
        padding: 24px;
      }

      .carta {
        width: min(760px, 100%);
        background: #ffffffd9;
        backdrop-filter: blur(3px);
        border: 1px solid #ffd3e2;
        border-radius: 22px;
        box-shadow: 0 20px 60px #8a3b5626;
        overflow: hidden;
      }

      .encabezado {
        text-align: center;
        padding: 28px 24px 16px;
      }

      h1 {
        margin: 0;
        color: var(--vino);
        font-size: clamp(1.8rem, 4vw, 2.7rem);
      }

      .sub {
        margin-top: 8px;
        font-size: 1.02rem;
        color: #6d4755;
      }

      .foto-wrap {
        padding: 0 18px;
      }

      .foto {
        width: 100%;
        border-radius: 18px;
        border: 3px solid var(--rosa-claro);
        display: block;
      }

      .mensaje {
        padding: 20px 24px 30px;
        text-align: center;
      }

      .mensaje p {
        margin: 0 auto 20px;
        line-height: 1.7;
        max-width: 60ch;
      }

      .boton {
        display: inline-block;
        text-decoration: none;
        color: white;
        background: linear-gradient(90deg, var(--rosa), #ff7ca8);
        padding: 13px 24px;
        border-radius: 999px;
        font-weight: 700;
        transition: transform 0.2s ease, box-shadow 0.2s ease;
        box-shadow: 0 10px 25px #ff4f8740;
      }

      .boton:hover {
        transform: translateY(-2px);
        box-shadow: 0 15px 30px #ff4f8754;
      }

      .firma {
        margin-top: 16px;
        font-style: italic;
        color: #8a5a6a;
      }
    </style>
  </head>
  <body>
    <main class="carta">
      <header class="encabezado">
        <h1>Para una chica increíble 💐</h1>
        <p class="sub">Hay canciones que suenan bonito... y otras que se sienten.</p>
      </header>

      <section class="foto-wrap">
        <img
          class="foto"
          src="./viernes13.png"
          alt="Ilustración de la canción Viernes 13"
        />
      </section>

      <section class="mensaje">
        <p>
          Quería dedicarte esta canción porque cada vez que la escucho, me hace pensar
          en ti. Ojalá te saque una sonrisa tan linda como las que me provocas tú.
        </p>

        <a
          class="boton"
          href="https://music.apple.com/pe/album/viernes-13/1194314770?i=1194315078"
          target="_blank"
          rel="noopener noreferrer"
        >
          Escuchar “Viernes 13” 🎵
        </a>

        <p class="firma">Con cariño, para ti ✨</p>
      </section>
    </main>
  </body>
</html>
