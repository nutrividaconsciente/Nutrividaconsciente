
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>NutriVida — Mejora (Recetas detalladas y Planes)</title>
  <meta name="description" content="NutriVida - herramientas nutricionales, recetas detalladas, planes y contacto." />
  <style>
}/* Fondo cálido con siluetas suaves de hojas */
body {
  background-color: #f6f7f3;
  background-image: url('https://cdn.pixabay.com/photo/2017/08/30/12/45/leaf-2692382_1280.png');
  background-repeat: repeat;
  background-size: 450px;
  background-attachment: fixed;
  background-position: center;
}
    :root{
      --bg:#f3f7f6; --card:#ffffff; --accent:#059669; --muted:#6b7280;
      --maxw:1100px; --radius:14px; font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#f3f7f6 0%,var(--bg) 100%);color:#0f172a;-webkit-font-smoothing:antialiased;}
    .container{max-width:var(--maxw);margin:24px auto;padding:24px;}
    header{background:linear-gradient(135deg,#2e7d32,#66bb6a);color:white;border-radius:12px;padding:18px;display:flex;align-items:center;justify-content:space-between;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-weight:700;color:white;background:rgba(255,255,255,0.08);font-size:20px}
    nav a{margin-left:16px;color:rgba(255,255,255,0.9);text-decoration:none;font-weight:600}
    nav a:hover{opacity:0.9}
    .cta{background:white;color:var(--accent);padding:8px 12px;border-radius:10px;text-decoration:none;font-weight:700}
    main{margin-top:18px}
    .hero-section{display:grid;grid-template-columns:1fr 420px;gap:20px;align-items:center;margin-bottom:20px}
    .hero-content h1{font-size:28px;margin:0;color:#06391f}
    .hero-content p{color:var(--muted);margin-top:8px}
    img.hero-img{width:100%;border-radius:12px;box-shadow:0 8px 20px rgba(2,6,23,0.06)}
    .calc-section{margin-top:8px}
    .calc-section h2{color:var(--accent);margin-bottom:6px}
    .intro-text{color:var(--muted);margin-bottom:12px}
    .grid-3{display:grid;grid-template-columns:1fr;gap:16px}
    .card{background:var(--card);border-radius:12px;padding:18px;box-shadow:0 8px 20px rgba(2,6,23,0.04)}
    .card h3{margin-top:0;color:#064e3b}
    .desc{color:var(--muted);margin-bottom:12px}
    .imc-input{width:100%;padding:10px;margin-bottom:10px;border-radius:8px;border:1px solid #e6e9ee}
    .btn{background:transparent;border:1px solid var(--accent);color:var(--accent);padding:10px 14px;border-radius:8px;cursor:pointer;font-weight:700}
    .btn.btn-solid{background:var(--accent);color:#fff;border-color:transparent}
    .imc-result{margin-top:10px;font-weight:700;color:var(--accent)}
    .nota{font-size:13px;color:var(--muted);margin-top:-6px;margin-bottom:10px}
    .recipe-img.small{width:100%;height:110px;object-fit:cover;border-radius:10px;margin-bottom:10px}
    .plans-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:12px}
    .reviews{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:12px}
    .stars{color:#fbbf24;font-weight:700}
    details{background:var(--card);padding:14px;border-radius:10px;border:1px solid #eef2f3}
    summary{font-weight:700;color:var(--accent);cursor:pointer;outline:none;padding:6px 0}
    .recipe-steps{font-size:14px;color:#14332f;line-height:1.5}
    .recipe-steps ol{padding-left:18px;margin:8px 0}
    .recipe-tip{font-size:13px;color:var(--muted);margin-top:8px}
    form.contact{max-width:700px;background:var(--card);padding:18px;border-radius:12px;box-shadow:0 8px 20px rgba(2,6,23,0.04)}
    .form-row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
    .form-row .full{grid-column:1/-1}
    .small-note{font-size:13px;color:var(--muted);margin-top:8px}
    @media(max-width:900px){
      .hero-section{grid-template-columns:1fr;gap:14px}
      .grid-3{grid-template-columns:1fr}
      .form-row{grid-template-columns:1fr

   }

  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">N</div>
        <div>
          <div style="font-weight:700;font-size:18px">NutriVida</div>
          <div style="font-size:13px;color:rgba(255,255,255,0.9)">Nutrición práctica y basada en evidencia</div>
        </div>
      </div>
      <nav>
        <a href="#herramientas">Herramientas</a>
        <a href="#planes">Planes</a>
        <a href="#recetas">Recetas</a>
        <a href="#reseñas">Reseñas</a>
        <a class="cta" href="#contacto">Reserva</a>
      </nav>
    </header>

    <main>
      <section id="hero" class="hero-section">
        <div class="hero-content">
          <h1>Mejora tu alimentación, mejora tu vida</h1>
          <p>
  Planes personalizados, recetas nutritivas y herramientas prácticas para alcanzar tus objetivos de bienestar.
  <br><br>
  <strong>En NutriVida contamos con un equipo de nutricionistas colegiados y expertos en salud y alimentación, comprometidos en acompañarte en cada paso hacia tu mejor versión.</strong>
</p>        </div>
        <div><img class="hero-img" src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?w=1200&q=80" alt="Comida saludable"></div>
      </section>

      <!-- Herramientas: acordeones independientes -->
      <section id="herramientas" class="calc-section">
        <h2>Herramientas Nutricionales</h2>
        <p class="intro-text">Calculadoras útiles para estimar tu IMC y tus necesidades calóricas.</p>

        <div class="grid-3">
          <div class="card">
            <details>
              <summary>Calculadora de IMC</summary>
              <div style="margin-top:12px">
                <p class="desc">Introduce tus datos para conocer tu Índice de Masa Corporal.</p>
                <input id="pesoIMC" class="imc-input" type="number" placeholder="Peso (kg)">
                <input id="alturaIMC" class="imc-input" type="number" placeholder="Altura (cm)">
                <button class="btn btn-solid" onclick="calcularIMC()">Calcular IMC</button>
                <div id="resultadoIMC" class="imc-result"></div>
              </div>
            </details>
          </div>

          <div class="card">
            <details>
              <summary>Calculadora — Fórmula de Mifflin-St Jeor</summary>
              <div style="margin-top:12px">
                <p class="desc">Calcula tu metabolismo basal (TMB) y gasto calórico diario estimado.</p>
                <input id="mifflinPeso" class="imc-input" type="number" placeholder="Peso (kg)">
                <input id="mifflinAltura" class="imc-input" type="number" placeholder="Altura (cm)">
                <input id="mifflinEdad" class="imc-input" type="number" placeholder="Edad (años)">
                <select id="mifflinGenero" class="imc-input">
                  <option value="hombre">Hombre</option>
                  <option value="mujer">Mujer</option>
                </select>
                <select id="actividad" class="imc-input">
                  <option value="1.2">Sedentario - poco o ningún ejercicio</option>
                  <option value="1.375">Ligera actividad - ejercicio ligero 1-3 días/semana</option>
                  <option value="1.55">Actividad moderada - ejercicio moderado 3-5 días/semana</option>
                  <option value="1.725">Alta actividad - ejercicio intenso 6-7 días/semana</option>
                  <option value="1.9">Actividad extrema - entrenamiento diario muy exigente</option>
                </select>
                <p class="nota">Selecciona tu nivel de actividad para estimar con mayor precisión tu gasto calórico diario.</p>
                <button class="btn btn-solid" onclick="calcularMifflin()">Calcular Gasto Diario</button>
                <div id="resultadoMifflin" class="imc-result"></div>
              </div>
            </details>
          </div>
        </div>
      </section>

      <!-- Plans -->
      <section id="plans" class="plans-section">
        <h2 id="planes">Planes Nutricionales</h2>
        <div class="plans-grid">
          <div class="card">
            <h3>Plan Pérdida de Peso</h3>
            <p>Reducción gradual y sostenible con menús equilibrados y flexibles.</p>
            <p class="desc">Incluye: videocon­sultas quincenales vía Zoom (45 min), seguimiento semanal vía WhatsApp para resolver dudas y ajustes de menú.</p>
            <p style="font-weight:700; margin-top:8px">Precio: 40 € / mensual</p>
          </div>
          <div class="card">
            <h3>Plan Ganancia Muscular</h3>
            <p>Aumenta masa magra optimizando proteínas y calorías.</p>
            <p class="desc">Incluye: videocon­sultas quincenales vía Zoom (45 min), plan nutricional enfocado en macronutrientes y soporte vía WhatsApp para seguimiento de progresos.</p>
            <p style="font-weight:700; margin-top:8px">Precio: 40 € / mensual</p>
          </div>
          <div class="card">
            <h3>Plan Salud Integral</h3>
            <p>Mejora tu bienestar general con un plan personalizado de nutrición equilibrada.</p>
            <p class="desc">Incluye: videocon­sultas quincenales vía Zoom (45 min), revisión de hábitos, recomendaciones de estilo de vida y soporte vía WhatsApp.</p>
            <p style="font-weight:700; margin-top:8px">Precio: 40 € / mensual</p>
          </div>
        </div>
      </section>

      <!-- Recipes with detailed accordion steps -->
      <section id="recetas" class="recipes-section">
        <h2 id="recetas">Recetas Populares</h2>
        <div class="grid-3">
          <div class="card">
            <img src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?w=600&q=80" alt="Bowl de quinoa" class="recipe-img small">
            <h4>Bowl de quinoa y vegetales</h4>
            <details>
              <summary>Ver preparación paso a paso</summary>
              <div class="recipe-steps">
                <ol>
                  <li><strong>Preparación previa (5 min):</strong> Lava 100 g de quinoa bajo agua fría hasta que el agua salga clara. Pica 1/2 pimiento, 1 zanahoria y 50 g de espinacas.</li>
                  <li><strong>Cocción (15 min):</strong> Hierve 200 ml de agua, añade la quinoa y una pizca de sal. Cocina a fuego medio-bajo 12–15 minutos hasta que esté tierna y el agua se absorba. Deja reposar 5 minutos con la tapa puesta.</li>
                  <li><strong>Salteado (6–8 min):</strong> En una sartén antiadherente, calienta 1 cucharada de aceite de oliva. Saltea el pimiento y la zanahoria 3–4 minutos, añade las espinacas y cocina 1–2 minutos más hasta que se ablanden.</li>
                  <li><strong>Montaje y aliño (3 min):</strong> Mezcla la quinoa con las verduras salteadas. Añade 30 g de garbanzos cocidos para proteína, 1 cucharada de semillas de sésamo y aliña con zumo de limón, 1 cucharadita de aceite de oliva y sal al gusto.</li>
                  <li><strong>Consejo nutricional:</strong> Esta receta aporta hidratos complejos, proteína vegetal y fibra; adecuada como almuerzo equilibrado. Para aumentar proteína, añade 50–100 g de pechuga de pollo a la plancha.</li>
                </ol>
              </div>
            </details>
          </div>

          <div class="card">
            <img src="https://images.unsplash.com/photo-1543353071-087092ec393a?w=600&q=80" alt="Salmón" class="recipe-img small">
            <h4>Salmón al horno con limón</h4>
            <details>
              <summary>Ver preparación paso a paso</summary>
              <div class="recipe-steps">
                <ol>
                  <li><strong>Preparación previa (5 min):</strong> Precalienta el horno a 200°C. Seca 150–180 g de filete de salmón con papel absorbente y sazona con sal y pimienta.</li>
                  <li><strong>Aliño y horneado (15–18 min):</strong> Coloca el salmón en una bandeja con papel de horno, añade unas rodajas de limón y 1 cucharadita de aceite de oliva. Hornea 12–15 minutos según grosor hasta que esté opaco y se desmenuce con facilidad.</li>
                  <li><strong>Guarnición rápida (5 min):</strong> Acompaña con una ensalada de hojas verdes y 80 g de patata asada o quinoa para un aporte de carbohidratos de calidad.</li>
                  <li><strong>Consejo nutricional:</strong> El salmón aporta ácidos grasos omega‑3 y proteína de alto valor biológico; ideal para incluir 2–3 veces por semana.</li>
                </ol>
              </div>
            </details>
          </div>

          <div class="card">
            <img src="https://images.unsplash.com/photo-1504754524776-8f4f37790ca0?w=600&q=80" alt="Smoothie verde" class="recipe-img small">
            <h4>Smoothie verde detox</h4>
            <details>
              <summary>Ver preparación paso a paso</summary>
              <div class="recipe-steps">
                <ol>
                  <li><strong>Ingredientes y preparación (3 min):</strong> En la licuadora añade 1 plátano maduro, 1 puñado de espinacas (40 g), 150 ml de agua o bebida vegetal y 1 cucharada de semillas de chía.</li>
                  <li><strong>Licuado (1–2 min):</strong> Licúa a potencia alta hasta obtener una textura homogénea. Si queda espeso, ajusta con agua hasta la consistencia deseada.</li>
                  <li><strong>Consejo práctico:</strong> Consumir inmediatamente para preservar vitaminas; ideal como desayuno ligero o snack. Añade 1 cucharada de proteína en polvo si buscas mayor aporte proteico.</li>
                  <li><strong>Nota nutricional:</strong> Alto en fibra y micronutrientes; controla la cantidad de fruta si buscas reducir azúcar.</li>
                </ol>
              </div>
            </details>
          </div>
        </div>
      </section>

      <!-- Reviews visual with stars -->
      <section id="reseñas" class="reviews-section">
        <h2 id="reseñas">Reseñas de Nuestros Clientes</h2>
        <div class="reviews">
          <div class="card">
            <p>“Gracias a NutriVida logré perder 8 kg en 3 meses sin sentirme privada de nada.”</p>
            <p class="stars">★★★★★</p>
            <p><strong>— Laura G.</strong></p>
          </div>
          <div class="card">
            <p>“El plan personalizado me ayudó a ganar masa muscular de manera saludable.”</p>
            <p class="stars">★★★★★</p>
            <p><strong>— Carlos R.</strong></p>
          </div>
          <div class="card">
            <p>“Excelente atención, recetas deliciosas y resultados reales.”</p>
            <p class="stars">★★★★★</p>
            <p><strong>— Marta P.</strong></p>
          </div>
        </div>
      </section>

      <!-- Contact with Formspree integration -->
      <section id="contacto" style="margin-top:20px">
        <h2>Contacto</h2>
        <form id="contactForm" class="contact" autocomplete="on">
          <div class="form-row">
            <input id="cf-name" name="name" required placeholder="Nombre" class="imc-input">
            <input id="cf-email" name="_replyto" type="email" required placeholder="Email" class="imc-input">
            <select name="plan" id="cf-plan" class="imc-input full">
              <option value="">Selecciona tipo de plan (opcional)</option>
              <option value="perdida_peso">Pérdida de Peso</option>
              <option value="ganancia_muscular">Ganancia Muscular</option>
              <option value="salud_integral">Salud Integral</option>
            </select>
            <textarea id="cf-message" name="message" rows="5" required placeholder="Mensaje" class="imc-input full"></textarea>
          </div>
          <input type="hidden" name="_subject" value="Nuevo mensaje desde web NutriVida">
          <input type="hidden" name="_template" value="table">
          <button type="submit" class="btn btn-solid">Enviar mensaje</button>
          <div id="cf-status" class="small-note" style="display:none;margin-top:12px"></div>
          <p class="small-note">Al enviar aceptas que usemos tus datos para responderte. No compartiremos tu información.</p>
        </form>
      </section>
    </main>

    <div style="text-align:center;margin-top:18px;color:var(--muted)">© 2025 NutriVida — Diseñado con ♥</div>
  </div>

  <script>
    // Calculators
    function calcularIMC(){
      const peso=parseFloat(document.getElementById('pesoIMC')?.value || 0);
      const altura=parseFloat(document.getElementById('alturaIMC')?.value || 0)/100;
      const res=document.getElementById('resultadoIMC');
      if(!peso||!altura){ if(res) res.textContent='Introduce peso y altura válidos.'; return;}
      const imc=(peso/(altura*altura)).toFixed(1);
      let msg='';
      if(imc<18.5)msg='Bajo peso'; else if(imc<25)msg='Peso saludable'; else if(imc<30)msg='Sobrepeso'; else msg='Obesidad';
      if(res) res.textContent=`Tu IMC es ${imc} (${msg}).`;
    }
    function calcularMifflin(){
      const peso=parseFloat(document.getElementById('mifflinPeso')?.value || 0);
      const altura=parseFloat(document.getElementById('mifflinAltura')?.value || 0);
      const edad=parseFloat(document.getElementById('mifflinEdad')?.value || 0);
      const genero=document.getElementById('mifflinGenero')?.value || 'hombre';
      const actividad=parseFloat(document.getElementById('actividad')?.value || 1.2);
      const res=document.getElementById('resultadoMifflin');
      if(!peso||!altura||!edad){ if(res) res.textContent='Introduce todos los datos.'; return;}
      let tmb=0;
      if(genero==='hombre') tmb=10*peso+6.25*altura-5*edad+5;
      else tmb=10*peso+6.25*altura-5*edad-161;
      const gastoTotal=tmb*actividad;
      if(res) res.textContent=`Tu TMB es ${tmb.toFixed(0)} kcal/día. Gasto diario estimado: ${gastoTotal.toFixed(0)} kcal.`;
    }

    // Formspree AJAX (endpoint: https://formspree.io/f/xovpezze)
    const form = document.getElementById('contactForm');
    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const status = document.getElementById('cf-status');
      status.style.display = 'block';
      status.textContent = 'Enviando mensaje...';
      const formData = new FormData(form);
      try {
        const res = await fetch('https://formspree.io/f/xovpezze', {
          method: 'POST',
          body: formData,
          headers: { 'Accept': 'application/json' }
        });
        const data = await res.json().catch(()=> ({}));
        if (res.ok) {
          status.textContent = '✅ Gracias por contactarnos. Te responderemos pronto.';
          form.reset();
        } else {
          status.textContent = 'Hubo un error al enviar. Intenta de nuevo más tarde.';
        }
      } catch (err) {
        status.textContent = 'No se pudo enviar el mensaje. Comprueba tu conexión.';
      }
    });
  </script>
</body>
</html>
