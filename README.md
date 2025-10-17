# beaten-emotion
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Beaten Emotion - Batidos Nutricionales</title>
  <style>
    /* Colores principales */
    :root {
      --morado: #b28bff;
      --rosado: #ffb6c1;
      --verde: #b4f8c8;
      --blanco: #fff;
      --gris: #f7f7f7;
    }

    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background-color: var(--gris);
      color: #333;
    }

    header {
      background: linear-gradient(90deg, var(--morado), var(--rosado), var(--verde));
      padding: 20px;
      text-align: center;
      color: var(--blanco);
      font-size: 1.8em;
      font-weight: bold;
      letter-spacing: 2px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: var(--blanco);
      padding: 10px 0;
    }

    nav a {
      text-decoration: none;
      color: #555;
      margin: 0 20px;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: var(--morado);
    }

    section {
      padding: 50px 10%;
      text-align: center;
    }

    .historia, .mision-vision, .contacto {
      background-color: var(--blanco);
      border-radius: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      padding: 40px;
      animation: fadeIn 1.2s ease-in-out;
      margin-bottom: 50px;
    }

    .historia h2, .mision-vision h2, #productos h2, .contacto h2 {
      color: var(--morado);
      margin-bottom: 15px;
    }

    .productos {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      gap: 30px;
    }

    .batido {
      background-color: var(--blanco);
      border-radius: 20px;
      width: 280px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s;
      overflow: hidden;
    }

    .batido:hover {
      transform: scale(1.05);
    }

    .batido img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 20px 20px 0 0;
    }

    .batido h3 {
      color: var(--morado);
      margin-top: 15px;
    }

    .batido p {
      padding: 0 15px 20px;
    }

    .mision-vision {
      background: linear-gradient(90deg, var(--verde), var(--rosado));
      color: #333;
    }

    .mision-vision .contenedor {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      gap: 30px;
    }

    .mision, .vision {
      width: 300px;
      background-color: var(--blanco);
      border-radius: 20px;
      padding: 25px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }

    .mision h3, .vision h3 {
      color: var(--morado);
    }

    .contacto {
      background: linear-gradient(90deg, var(--verde), var(--rosado));
      color: #333;
    }

    form {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
      margin-top: 20px;
    }

    input, textarea {
      width: 70%;
      padding: 10px;
      border-radius: 10px;
      border: none;
      outline: none;
      font-size: 1em;
    }

    button {
      background-color: var(--morado);
      color: var(--blanco);
      padding: 10px 25px;
      border: none;
      border-radius: 15px;
      cursor: pointer;
      font-size: 1em;
      transition: 0.3s;
    }

    button:hover {
      background-color: var(--rosado);
    }

    footer {
      background-color: var(--morado);
      color: var(--blanco);
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <header>🥤 Beaten Emotion 🩷💜💚</header>

  <nav>
    <a href="#historia">Nuestra Historia</a>
    <a href="#mision-vision">Misión y Visión</a>
    <a href="#productos">Batidos</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="historia" class="historia">
    <h2>Nuestra historia</h2>
    <p>
      En <strong>Beaten Emotion</strong> creemos que cada emoción puede transformarse en energía positiva. 
      Nuestros batidos nacen de la unión entre <em>nutrición, color y bienestar emocional</em>.  
      Comenzamos como un pequeño proyecto familiar que buscaba dar alegría a cada sorbo, 
      y hoy somos una comunidad que se alimenta con propósito.
    </p>
  </section>

  <section id="mision-vision" class="mision-vision">
    <h2>Nuestra Misión y Visión</h2>
    <div class="contenedor">
      <div class="mision">
        <h3>🌟 Misión</h3>
        <p>
          Brindar bienestar físico y emocional a través de batidos naturales que combinan 
          ingredientes saludables con colores y sabores que inspiran emociones positivas.
        </p>
      </div>
      <div class="vision">
        <h3>🌈 Visión</h3>
        <p>
          Ser reconocidos como la marca líder en batidos emocionales en Latinoamérica, 
          promoviendo una cultura de alimentación consciente, alegre y equilibrada.
        </p>
      </div>
    </div>
  </section>

  <section id="productos">
    <h2>Nuestros batidos emocionales</h2>
    <div class="productos">

      <div class="batido">
        <img src="https://cdn.pixabay.com/photo/2016/08/03/21/03/smoothie-1563591_1280.jpg" alt="Batido Energía Alegre">
        <h3>🌞 Energía Alegre</h3>
        <p>Batido de mango, piña y avena que despierta tu cuerpo y tu mente. Perfecto para comenzar el día con optimismo.</p>
      </div>

      <div class="batido">
        <img src="https://cdn.pixabay.com/photo/2016/02/24/17/56/smoothie-1224829_1280.jpg" alt="Batido Calma Interior">
        <h3>💜 Calma Interior</h3>
        <p>Batido de frutos morados, lavanda y yogur griego. Ideal para equilibrar emociones y reducir el estrés.</p>
      </div>

      <div class="batido">
        <img src="https://cdn.pixabay.com/photo/2017/08/01/00/17/smoothie-2563824_1280.jpg" alt="Batido Amor Verde">
        <h3>💚 Amor Verde</h3>
        <p>Batido de espinaca, manzana verde y menta. Refresca tu cuerpo y llena tu corazón de vitalidad.</p>
      </div>
    </div>
  </section>

  <section id="contacto" class="contacto">
    <h2>Contáctanos</h2>
    <p>¿Tienes dudas o quieres pedir tu batido emocional? Escríbenos 💌</p>
    <form>
      <input type="text" placeholder="Tu nombre" required>
      <input type="email" placeholder="Tu correo electrónico" required>
      <textarea rows="4" placeholder="Tu mensaje..."></textarea>
      <button type="submit">Enviar mensaje</button>
    </form>
  </section>

  <footer>
    © 2025 Beaten Emotion - Nutre tu cuerpo, vibra con tus emociones 🌈
  </footer>

</body>
</html>
