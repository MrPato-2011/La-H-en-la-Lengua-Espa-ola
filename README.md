<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>H en español — Aprende jugando</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<header class="topbar">
  <a class="brand" href="#inicio">H<span>+</span></a>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#reglas">Reglas</a>
    <a href="#flashcards">Flashcards</a>
    <a href="#practica">Práctica</a>
  </nav>
  <button id="themeBtn" class="icon-btn" aria-label="Cambiar tema">☾</button>
</header>

<main>
<section id="inicio" class="hero section">
  <div class="hero-copy">
    <p class="eyebrow">ORTOGRAFÍA · ESPAÑOL</p>
    <h1>La <span>H</span> no suena,<br>pero sí importa.</h1>
    <p class="lead">Aprende cuándo usar la H con reglas claras, ejemplos y tarjetas interactivas. Sin relleno. Sin memorizar a ciegas.</p>
    <div class="actions">
      <a class="btn primary" href="#flashcards">Empezar</a>
      <a class="btn ghost" href="#reglas">Ver reglas</a>
    </div>
  </div>
  <div class="h-orbit" aria-hidden="true">
    <div class="orbit-ring"></div>
    <div class="big-h">H</div>
    <span class="word w1">huevo</span><span class="word w2">hielo</span>
    <span class="word w3">haber</span><span class="word w4">humano</span>
  </div>
</section>

<section id="reglas" class="section">
  <div class="section-head">
    <div><p class="eyebrow">01 · CLAVES</p><h2>Reglas que sí sirven</h2></div>
    <p>La H es muda, pero aparece en posiciones concretas.</p>
  </div>
  <div class="rule-grid">
    <article class="card"><div class="num">01</div><h3>Inicio con hie- / hue-</h3><p>Muchas palabras que empiezan por <b>hie</b> o <b>hue</b> llevan H.</p><div class="examples">hielo · hierba · huevo · huella</div></article>
    <article class="card"><div class="num">02</div><h3>Formas de haber</h3><p>El verbo <b>haber</b> y sus formas conservan la H.</p><div class="examples">he · has · ha · había · habrá</div></article>
    <article class="card"><div class="num">03</div><h3>Formas de hacer</h3><p>Las formas del verbo <b>hacer</b> se escriben con H.</p><div class="examples">hago · hizo · hecho · haré</div></article>
    <article class="card"><div class="num">04</div><h3>Familias de palabras</h3><p>Una palabra puede conservar la H en palabras de la misma familia.</p><div class="examples">hora → horario · humo → humareda</div></article>
  </div>
</section>

<section id="flashcards" class="section dark-section">
  <div class="section-head">
    <div><p class="eyebrow">02 · FLASHCARDS</p><h2>Voltea y comprueba</h2></div>
    <p>Haz clic en una tarjeta para ver la respuesta.</p>
  </div>
  <div class="flash-wrap">
    <button class="arrow" id="prev">‹</button>
    <div class="flashcard" id="flashcard" tabindex="0">
      <div class="face front"><span class="tag">¿Lleva H?</span><strong id="question">__uevo</strong><small>Haz clic para revelar</small></div>
      <div class="face back"><span class="tag correct">CORRECTO</span><strong id="answer">huevo</strong><p id="why">La palabra comienza por <b>hue-</b>.</p></div>
    </div>
    <button class="arrow" id="next">›</button>
  </div>
  <div class="dots" id="dots"></div>
</section>

<section id="practica" class="section">
  <div class="section-head">
    <div><p class="eyebrow">03 · PRÁCTICA</p><h2>Completa la palabra</h2></div>
    <p>Escribe la palabra correcta y recibe feedback inmediato.</p>
  </div>
  <div class="practice-card">
    <div class="practice-icon">H?</div>
    <h3 id="practicePrompt">__ielo</h3>
    <div class="input-row">
      <input id="practiceInput" autocomplete="off" placeholder="Escribe la palabra">
      <button class="btn primary" id="checkBtn">Comprobar</button>
    </div>
    <p id="feedback" class="feedback"></p>
    <div class="score">Aciertos: <strong id="score">0</strong> / <span id="total">0</span></div>
  </div>
</section>
</main>

<footer><span>H+</span> · Aprende ortografía jugando · Español</footer>
<script src="script.js"></script>
</body>
</html>
