 
</head>

<body id="inicio">

  <nav class="nav-bar">
    <a href="#inicio">🏠 Perfil</a>
    <a href="#teoria">📖 Teoría VDT</a>
    <a href="#simulador">🧮 Simulador</a>
    <a href="#proximo">📅 Próximo Tema</a>
    <a href="#contacto">✉️ Contacto</a>
  </nav>

  <h1>Matemática Financiera</h1>
  <div class="subtitle-header"><strong>Finanzasconmate</strong></div>

  <h2>Perfil Profesional</h2>
  <p>Estudiante de Licenciatura en Matemáticas y Banca y Finanzas, apasionada por la aplicación práctica de los modelos financieros, análisis cuantitativo y la asesoría comercial en el sector financiero.</p>

  <h2>Áreas de Interés</h2>
  <ul>
    <li>Matemática Financiera y Modelos Cuantitativos</li>
    <li>Asesoría Financiera y Comercial</li>
    <li>Análisis y Gestión de Datos</li>
    <li>Proyectos sociales</li>
    <li>Coaching Social y Desarrollo Personal</li>
    <li>Power BI</li>
    <li>Emprendimiento</li>
  </ul>

  <h2>Publicaciones y Proyectos</h2>
  <p><strong>1. Introducción al Interés Simple y Compuesto: El Valor del Dinero en el Tiempo</strong></p>

  <div id="proximo" style="background-color: #e7f1ff; border-left: 5px solid #0d6efd; padding: 20px; border-radius: 8px; margin: 35px 0;">
    <span style="background-color: #0d6efd; color: white; padding: 3px 10px; border-radius: 12px; font-size: 0.85em; font-weight: bold; text-transform: uppercase;">Próxima publicación</span>
    <h3 style="color: #0d6efd; margin-top: 10px; margin-bottom: 8px;">2. El club de los números: ¿Quién es quién en ℝ, ℤ, ℚ, 𝕀 y ℝ?</h3>
    <p style="margin-bottom: 10px;">¡Prepárate para la próxima entrega! Descubriremos de forma interactiva cómo se clasifican los conjuntos numéricos y pondremos a prueba tus conocimientos con un clasificador dinámico de números reales.</p>
    <p style="margin: 0; font-weight: bold; color: #495057;">📅 Disponible el próximo viernes, 18 de septiembre de 2026</p>
  </div>

  <h2 id="contacto">Contacto & Red Profesional</h2>
  <p>Si deseas ponerte en contacto conmigo para colaboraciones académicas, consultas sobre asesoría financiera o proyectos:</p>
  <ul>
    <li><strong>Correo electrónico:</strong> ashlyjulieth@hotmail.com</li>
    <li><strong>Ubicación:</strong> Cali, Colombia</li>
    <li><strong>LinkedIn:</strong> <a href="https://linkedin.com" target="_blank" style="color: #0d6efd; font-weight: bold; text-decoration: none;">Connect on LinkedIn ↗</a></li>
  </ul>

  <a href="#inicio" class="btn-back-top">⬆️ Regresar al Perfil</a>

  <script>
    function cambiarModo() {
      const modo = document.getElementById('tipoCalculo').value;
      const lblMonto = document.getElementById('lblMonto');
      if (modo === 'VF') {
        lblMonto.innerText = 'Valor Presente (VP / Capital Inicial):';
      } else {
        lblMonto.innerText = 'Valor Futuro deseado (VF / Meta Futura):';
      }
      document.getElementById('resultado').style.display = 'none';
    }

    
    

</body>
</html>
