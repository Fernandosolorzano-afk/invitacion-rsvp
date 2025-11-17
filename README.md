<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Graduación 2025 — Fernando Solórzano | Confirmación</title>

  <!-- Fuentes -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Montserrat:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    /* ---------------- reset ---------------- */
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family:'Montserrat',sans-serif;
      background:linear-gradient(180deg,#081024 0%, #11213a 60%, #0d2238 100%);
      color:#fff;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      overflow-x:hidden;
    }

    /* ---------------- estrellas (fondo) ---------------- */
    .stars{position:fixed;inset:0;z-index:0;pointer-events:none;overflow:hidden}
    .star{position:absolute;border-radius:50%;box-shadow:0 0 8px rgba(255,215,0,0.6);opacity:0.9;transform:translateY(120vh);animation:starRise linear infinite}
    @keyframes starRise{from{transform:translateY(120vh) scale(.6);opacity:0}10%{opacity:1}100%{transform:translateY(-20vh) scale(.9);opacity:0}}

    /* ---------------- intro a pantalla completa ---------------- */
    #intro{position:fixed;inset:0;display:flex;align-items:center;justify-content:center;z-index:20;background:#000;flex-direction:column;gap:6px;padding:20px}
    .intro-box{position:absolute;inset:0;z-index:18;background:radial-gradient(circle at center, rgba(0,0,0,0.95) 0%, rgba(3,7,12,0.98) 40%, rgba(3,7,12,1) 100%)}

    /* textos del intro - mismas dimensiones visuales */
    .intro-text{z-index:22;text-align:center;font-family:'Playfair Display',serif;font-weight:700;line-height:1;pointer-events:none}
    .intro-line{display:block}
    .intro-title{font-size:calc(28px + 3.2vw);letter-spacing:1px;margin:0}
    .intro-sub{font-size:calc(20px + 1.8vw);margin:6px 0 0}

    /* efecto brillo dorado (shimmer) */
    .gold-shimmer{background:linear-gradient(90deg,#ffd700,#fff6d1,#ffd700);-webkit-background-clip:text;background-clip:text;color:transparent;background-size:200% auto;animation:goldMove 3.8s linear infinite;filter:drop-shadow(0 8px 32px rgba(255,200,40,0.12))}
    @keyframes goldMove{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}

    /* estilo letras animadas (span por letra) */
    .animated-letters{display:inline-block;overflow:visible}
    .animated-letters span{display:inline-block;color:transparent;opacity:0;transform:translateY(26px) rotateX(12deg) scale(.98);transition:transform .58s cubic-bezier(.2,.9,.2,1),opacity .45s}

    /* ---------------- contenedor principal ---------------- */
    .page{position:relative;min-height:100vh;z-index:1;display:flex;align-items:center;justify-content:center;padding:48px 20px}

    .card{width:100%;max-width:640px;background:linear-gradient(180deg,rgba(8,24,43,0.94),rgba(7,18,35,0.82));border-radius:18px;padding:28px 30px 34px;box-shadow:0 26px 60px rgba(2,6,20,0.6);border:1px solid rgba(255,255,255,0.06);position:relative;z-index:3;transform:translateY(30px);opacity:0;transition:all .9s cubic-bezier(.2,.9,.2,1)}
    .card.visible{transform:translateY(0);opacity:1}

    .card-header{text-align:center;margin-bottom:10px}
    .card-header img{width:84px;display:block;margin:0 auto 12px}
    .card-header h3{font-family:'Playfair Display',serif;font-size:1.8rem;color:#ffd87a;margin-bottom:6px;text-shadow:0 8px 28px rgba(255,200,40,0.08)}
    .card-header p{color:#dbe8ff;font-size:.98rem;margin:0;opacity:.95}

    /* ---------------- formulario ---------------- */
    form{margin-top:8px}
    form .row{display:flex;gap:12px}
    form .col{flex:1}
    label{display:block;font-weight:700;color:#e8f3ff;margin-bottom:8px;font-size:.95rem}

    /* Inputs generales estilo azul elegante */
    input[type="text"],input[type="number"],textarea{width:100%;padding:12px 14px;border-radius:12px;border:1px solid rgba(255,255,255,0.04);background:linear-gradient(180deg, rgba(12,30,55,0.55), rgba(10,26,48,0.45));color:#eaf6ff;font-size:0.98rem;outline:none;transition:box-shadow .18s ease,transform .12s ease}
    input:focus,textarea:focus{box-shadow:0 10px 30px rgba(0,50,120,0.16);transform:translateY(-3px)}
    textarea{min-height:104px;resize:vertical}

    /* Select estilo AZUL con opciones blancas */
    select{width:100%;padding:12px;border-radius:12px;border:1px solid rgba(255,255,255,0.04);background:linear-gradient(180deg, rgba(12,30,55,0.55), rgba(10,26,48,0.45));color:#fff;font-size:0.98rem}
    select option{background:#0b1b2b;color:#fff}

    /* boton dorado */
    .btn{display:inline-block;width:100%;padding:14px;border-radius:12px;border:none;background:linear-gradient(90deg,#ffd700,#fff1b8);color:#041627;font-weight:800;font-size:1.05rem;cursor:pointer;box-shadow:0 12px 36px rgba(255,200,20,0.12);transition:transform .14s ease,box-shadow .14s ease}
    .btn:hover{transform:translateY(-4px);box-shadow:0 22px 48px rgba(255,200,20,0.16)}

    .note{font-size:.85rem;color:#cfe1ff;opacity:.95;margin-top:12px;text-align:center}

    /* ---------------- audio: oculto (sin botón) ---------------- */
    audio{display:none}

    /* responsive */
    @media (max-width:720px){.card{padding:20px}.intro-title{font-size:calc(22px + 5vw)}.intro-sub{font-size:calc(16px + 3.6vw)}}

  </style>
</head>

<body>

  <!-- estrellas de fondo -->
  <div class="stars" id="stars"></div>

  <!-- INTRO de pantalla completa -->
  <div id="intro" aria-hidden="false">
    <div class="intro-box"></div>
    <div class="intro-text">
      <span class="intro-line intro-title animated-letters" id="line1"></span>
      <span class="intro-line intro-title animated-letters" id="line2"></span>
    </div>
  </div>

  <!-- contenido: formulario -->
  <main class="page" role="main">
    <section class="card" id="card">
      <div class="card-header">
        <img src="https://cdn-icons-png.flaticon.com/512/2985/2985150.png" alt="Gorro de graduación">
        <h3 id="main-title">Graduación 2025 — Confirmación</h3>
        <p>Fernando Solórzano • Aula de Graduación</p>
      </div>

      <form id="rsvpForm" action="https://formsubmit.co/fernandoeliseosolorzano14@gmail.com" method="POST" autocomplete="on">
        <input type="hidden" name="_captcha" value="false">
        <input type="hidden" name="_template" value="table">

        <label for="nombre">Nombre completo</label>
        <input id="nombre" name="nombre" type="text" placeholder="Ej: María Pérez" required>

        <div class="row" style="margin-top:8px">
          <div class="col">
            <label for="asistira">¿Asistirá?</label>
            <select id="asistira" name="asistira" required>
              <option value="" disabled selected>Seleccione...</option>
              <option value="Sí">Sí</option>
              <option value="No">No</option>
            </select>
          </div>

          <div class="col">
            <label for="cantidad">Cantidad de personas</label>
            <input id="cantidad" name="cantidad" type="number" min="0" max="10" value="0" required>
          </div>
        </div>

        <label for="mensaje" style="margin-top:12px">Comentario / Mensaje</label>
        <textarea id="mensaje" name="mensaje" placeholder="Por ejemplo: Llegare puntual"></textarea>

        <div style="margin-top:14px">
          <button type="submit" class="btn">Confirmar asistencia</button>
        </div>

        <div class="note">Se enviará una confirmación a mi correo. Gracias por confirmar.</div>
      </form>
    </section>
  </main>

<!-- Música en segundo plano (autoplay suave) -->
<audio id="bgMusic" preload="auto" loop>
    <source src="never-give-up-276533.mp3" type="audio/mpeg">
    Tu navegador no soporta audio.
  </audio>
  
  <script>
    document.addEventListener("DOMContentLoaded", () => {
      const music = document.getElementById("bgMusic");
  
      // volumen suave
      music.volume = 0.25;
  
      // intentar reproducir automáticamente
      const attemptPlay = () => {
        music.play().catch(() => {
          // si el navegador lo bloquea, vuelve a intentar cuando el usuario haga clic en cualquier parte
          document.body.addEventListener("click", () => {
            music.play();
          }, { once:true });
        });
      };
  
      attemptPlay();
    });
  </script>  

  <!-- scripts -->
  <script>
    /* ---------- generar estrellas ---------- */
    (function(){
      const container = document.getElementById('stars');
      const n = 60;
      for(let i=0;i<n;i++){
        const d = document.createElement('div');
        d.className = 'star';
        const size = 1 + Math.random()*3;
        d.style.width = size + 'px'; d.style.height = size + 'px';
        d.style.left = (Math.random()*100) + 'vw';
        d.style.top = (Math.random()*100) + 'vh';
        d.style.animationDelay = (Math.random()*6) + 's';
        d.style.animationDuration = (6 + Math.random()*9) + 's';
        d.style.background = 'rgba(255,215,0,' + (0.5 + Math.random()*0.6) + ')';
        container.appendChild(d);
      }
    })();

    /* ---------- animación letra por letra (intro) ---------- */
    const textA = 'Graduación 2025';
    const textB = 'Fernando Solórzano';
    const out1 = document.getElementById('line1');
    const out2 = document.getElementById('line2');

    function putLetters(container, text){
      container.innerHTML = '';
      for(let i=0;i<text.length;i++){
        const ch = text[i];
        const span = document.createElement('span');
        span.textContent = ch === ' ' ? ' ' : ch;
        span.className = 'letter';
        container.appendChild(span);
      }
    }

    putLetters(out1, textA);
    putLetters(out2, textB);

    function playIntro(){
      const s1 = out1.querySelectorAll('span');
      const s2 = out2.querySelectorAll('span');
      // animar primera linea
      s1.forEach((sp,i)=>{
        setTimeout(()=>{
          sp.style.opacity = '1';
          sp.style.transform = 'translateY(0) rotateX(0) scale(1)';
          sp.classList.add('gold-shimmer');
        }, 180 + i*55);
      });
      // animar segunda linea justo despues
      setTimeout(()=>{
        s2.forEach((sp,i)=>{
          setTimeout(()=>{
            sp.style.opacity = '1';
            sp.style.transform = 'translateY(0) rotateX(0) scale(1)';
            sp.classList.add('gold-shimmer');
          }, i*45);
        });
      }, 180 + s1.length*55 + 160);
    }

    // iniciar anim intro
    setTimeout(()=>{ playIntro(); }, 220);

    /* ---------- mostrar formulario tras intro ---------- */
    const intro = document.getElementById('intro');
    const card = document.getElementById('card');
    // tiempo visible del intro (ajustable)
    const visibleMs = 3800;
    setTimeout(()=>{
      intro.style.transition = 'opacity 750ms ease, visibility 750ms';
      intro.style.opacity = '0';
      intro.style.visibility = 'hidden';
      setTimeout(()=>{ card.classList.add('visible'); }, 820);
    }, visibleMs + 600);

    /* ---------- audio autoplay suave (sin botones) ---------- */
    (function audioAuto(){
      const music = document.getElementById('bgMusic');
      music.volume = 0.22;
      // intenta reproducir; si el navegador lo bloquea, la reproducción comenzará cuando el usuario interactúe
      window.addEventListener('load', ()=>{
        music.play().catch(()=>{
          // silencio: si falla autoplay, añadimos listener para reintentar en la primera interacción
          const resume = ()=>{ music.play().catch(()=>{}); window.removeEventListener('pointerdown', resume); window.removeEventListener('keydown', resume); };
          window.addEventListener('pointerdown', resume);
          window.addEventListener('keydown', resume);
        });
      });
    })();

    /* ---------- validación simple del formulario ---------- */
    const form = document.getElementById('rsvpForm');
    form.addEventListener('submit', (e)=>{
      const nombre = document.getElementById('nombre').value.trim();
      const asistira = document.getElementById('asistira').value;
      const cantidad = parseInt(document.getElementById('cantidad').value);
      if(!nombre || !asistira || isNaN(cantidad)){
        e.preventDefault();
        alert('Por favor completa los campos obligatorios (nombre, asistencia y cantidad).');
        return;
      }
      if(asistira === 'No') document.getElementById('cantidad').value = 0;
      // FormSubmit procesa el envío
    });

    /* ---------- permitir saltar intro tocando (mobile) ---------- */
    intro.addEventListener('click', ()=>{
      intro.style.transition = 'opacity 420ms ease, visibility 420ms';
      intro.style.opacity = '0'; intro.style.visibility = 'hidden'; card.classList.add('visible');
    });
  </script>
</body>
</html>



