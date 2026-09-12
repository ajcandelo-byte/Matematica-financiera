<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matemática Financiera | Finanzasconmate</title>
  
  <style>
    
    html { scroll-behavior: smooth; }
    body { font-family: Arial, sans-serif; line-height: 1.6; color: #333; max-width: 850px; margin: 0 auto; padding: 25px; padding-top: 70px; }
    
    
    /* Navegación superior */
    
    
    nav.nav-bar { position: fixed; top: 0; left: 0; right: 0; background-color: #0d6efd; padding: 12px 20px; box-shadow: 0 2px 8px rgba(0,0,0,0.15); z-index: 1000; text-align: center; }
    nav.nav-bar a { color: white; text-decoration: none; font-weight: bold; margin: 0 12px; font-size: 14px; }
    nav.nav-bar a:hover { text-decoration: underline; }

    h1 { color: #0d6efd; text-align: center; margin-bottom: 5px; }
    .subtitle-header { text-align: center; color: #6c757d; font-size: 1.1em; margin-bottom: 30px; }
    h2 { color: #1a252c; border-bottom: 2px solid #0d6efd; padding-bottom: 6px; margin-top: 35px; }
    h3 { color: #495057; }
    hr { border: 0; height: 1px; background: #e9ecef; margin: 30px 0; }
    .disclaimer { background: #fff3cd; color: #856404; padding: 15px; border-left: 5px solid #ffeeba; border-radius: 4px; font-size: 0.9em; margin: 20px 0; }
    .formula { background: #e9ecef; padding: 10px 15px; border-radius: 6px; font-weight: bold; font-family: monospace; }
    ul { margin-bottom: 20px; }
    
    .simulador-box { max-width: 500px; margin: 30px auto; padding: 25px; border-radius: 12px; background-color: #f8f9fa; border: 1px solid #e9ecef; box-shadow: 0 4px 10px rgba(0,0,0,0.08); }
    .form-group { margin-bottom: 15px; }
    .form-group label { display: block; font-weight: bold; margin-bottom: 5px; color: #495057; }
    .form-group input, .form-group select { width: 100%; padding: 10px; border-radius: 6px; border: 1px solid #ced4da; box-sizing: border-box; font-size: 14px; }
    .btn-calcular { width: 100%; padding: 12px; background-color: #0d6efd; color: white; border: none; border-radius: 6px; font-weight: bold; font-size: 15px; cursor: pointer; }
    .btn-calcular:hover { background-color: #0b5ed7; }
    .resultado-box { margin-top: 20px; padding: 16px; border-radius: 8px; background-color: #ffffff; border: 1px solid #dee2e6; display: none; }
    
    .referencias { background-color: #f8f9fa; padding: 20px; border-radius: 8px; border: 1px solid #e9ecef; font-size: 0.95em; }
    .referencias p { text-indent: -2em; padding-left: 2em; margin-bottom: 12px; }

    .btn-back-top { position: fixed; bottom: 20px; right: 20px; background-color: #0d6efd; color: white; border: none; padding: 10px 16px; border-radius: 20px; font-weight: bold; cursor: pointer; box-shadow: 0 4px 10px rgba(0,0,0,0.2); text-decoration: none; display: inline-block; }
    .btn-back-top:hover { background-color: #0b5ed7; }
    
  </style>
  
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
