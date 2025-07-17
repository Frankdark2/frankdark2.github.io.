# frankdark2.github.io.
PAGINA WEB - PROYECTO FINAL
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Unidad Educativa José Domingo de Santistevan</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f6f8;
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      background-color: #ff6100;
      color: white;
      padding: 30px;
      text-align: center;
      position: relative;
    }

    .logo {
      position: absolute;
      top: 15px;
      left: 20px;
      width: 170px;
      height: auto;
    }

    nav {
      background-color: #0033cc;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 14px 0;
    }

    nav a {
      color: white;
      margin: 10px 20px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
      font-size: 1rem;
    }

    nav a:hover {
      color: #ffcc00;
      text-decoration: underline;
    }

    section {
      display: none;
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    section.active {
      display: block;
      animation: fadeIn 0.6s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    .flex-contenido {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 30px;
      margin-bottom: 40px;
    }

    .flex-contenido img {
      flex: 1 1 400px;
      max-width: 500px;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    .flex-texto {
      flex: 1 1 400px;
    }
    
    .imagen-colegio, #imagen {
      width: 100%;
      max-width: 800px;
      margin: 20px auto;
      display: block;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    .mision-vision {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .mision, .vision {
      flex: 1 1 400px;
      padding: 25px;
      background: #f9f9f9;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
    }

    .mision img, .vision img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    input, textarea, select {
      padding: 12px;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    button {
      padding: 12px;
      background-color: #0033cc;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1rem;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #001a80;
    }

    footer {
      background-color: #0d47a1;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <img src="09_Logo Blanco Azul Vertical.png" alt="Logo" class="logo">
    <h1>Unidad Educativa José Domingo de Santistevan</h1>
    <h3>Formando líderes con valores y excelencia académica</h3>
  </header>

  <nav>
    <a href="#" onclick="mostrar('inicio')">Inicio</a>
    <a href="#" onclick="mostrar('historia')">Historia</a>
    <a href="#" onclick="mostrar('misionvision')">Misión y Visión</a>
    <a href="#" onclick="mostrar('metodologiaacademica')">Metodología Académica</a>
    <a href="#" onclick="mostrar('nivelesdeestudio')">Niveles De Estudio</a>
    <a href="#" onclick="mostrar('contactenos')">Contáctenos</a>
  </nav>

   <!-- INICIO -->
  <section id="inicio" class="active">
    <img id="imagen" src="https://santistevan.edu.ec/images/santistevan/slide/inicio.png" alt="Carrusel de imágenes">
    <h1>¿Quiénes Somos?</h1>
    <p>La Unidad Educativa "José Domingo de Santistevan" es una institución privada perteneciente a la Red de Colegios de Formación Profesional de la Junta de Beneficencia de Guayaquil, con la misión de formar estudiantes libres, responsables y solidarios, brindando una educación de calidad basada en valores e impulsando la innovación y la formación profesional.</p>
    <p>Ofrecemos educación desde Inicial 2 hasta Tercero de Bachillerato, con modernas instalaciones que incluyen canchas deportivas y laboratorios especializados, garantizando una formación integral.</p>
    <p>Nuestra historia inicia con la administración municipal, para luego ser gestionada por la Junta de Beneficencia. Inaugurada el 5 de enero de 1905, la institución fue fundada con fondos donados por José Domingo de Santistevan. Hasta el 2001, fue administrada por los Padres Salesianos.</p>
    <p>Enfocamos nuestra enseñanza en la participación cívica y comunitaria y destacamos por la excelencia académica, reflejada en los logros de nuestros aprendices. Con 1.200 estudiantes, hemos formado a generaciones que han dejado su huella en la sociedad, como el Dr. Eduardo Peña Triviño, ex Ministro de Educación y Vicepresidente de la República.</p>
    <p>Reconocida por su alto rendimiento académico y deportivo, la Unidad Educativa José Domingo de Santistevan se posiciona como una institución de referencia en Guayaquil.</p>
    <iframe width="900" height="550"
        src="https://www.youtube.com/embed/YI2PZ2fzWoM"
        title="Video Institucional" frameborder="0" allowfullscreen>
    </iframe>
    <h2>Contacto</h2>
    <p><strong>Dirección:</strong> Calle Principal y Av. Central, Guayas, Ecuador</p>
    <p><strong>Teléfono:</strong> +593 4 123 4567</p>
    <p><strong>Email:</strong> info@santistevan.edu.ec</p>
    <h2>Ubicación</h2>
    <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3986.9329662304135!2d-79.8774466!3d-2.1791484!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x902d6dcd80961205%3A0x383f8b7e79b0b445!2sUnidad%20Educativa%20Jos%C3%A9%20Domingo%20de%20Santistevan%20de%20la%20Junta%20de%20Beneficencia%20de%20Guayaquil!5e0!3m2!1ses-419!2sec!4v1752764054595!5m2!1ses-419!2sec" 
    width="600" 
    height="450" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
    </iframe>
  </section>

  <!-- HISTORIA -->
  <section id="historia">
    <h1>Historia</h1>
    <img src="https://santistevan.edu.ec/images/santistevan/web/banda_santistevan.jpg" class="imagen-colegio" alt="banda_santistevan">
    <p>El Directorio de la Junta de Beneficencia de Guayaquil, en Sesión General del 12 de julio de 1903, resolvió construir el Asilo de niños Huérfanos, José Domingo de Santistevan, en un lote situado en las faldas del Cerro Santa Ana. El 5 de enero de 1905, se marcó la fecha de fundación del asilo, el que dio inicio en ese año a sus labores educativas y de asistencia social.</p>
    <p>La administración de esta obra de enorme trascendencia para la comunidad guayaquileña fue encargada a la Comunidad Salesiana del Ecuador, cuyo primer Director fue Monseñor Obispo Domingo Comín. La finalidad de esta institución era la de recibir niños huérfanos y de escasos recursos económicos y brindarles educación primaria, alimentación y formación espiritual.</p>
    <p>En 1905 se inició esta obra con 24 niños varones. Se les recibía desde los 6 años de edad y solamente se les impartía enseñanza primaria. El horario de la escuela en la mañana era de 08h00 a 11h30 y en la tarde de 13h30 a 15h45.</p>
    <p>El asilo mantenía dos modalidades de estudio con estudiantes internos y externos, quienes formaban parte de un selecto coro, la orquesta, la sociedad de deportes, etc. En 1908, durante la crisis de la fiebre bubónica, la Junta de Beneficencia dispuso que este local sirviera de refugio para los enfermos.</p>
    <p>El edificio original del Instituto, adosado a las faldas del Cerro Santa Ana y con estructura de madera, fue reconstruido en cemento en 1937. En aquel entonces, la escuela contaba con 6 salones de clase con capacidad de 60 alumnos por aula.</p>
  <button onclick="mostrar('inicio')">Regresar a Inicio</button>
  </section>

  <!-- MISION Y VISION JUNTAS -->
  <section id="misionvision">
    <h2>Misión y Visión</h2>
    <div class="mision-vision">
      <div class="mision">
        <h3>Misión</h3>
        <p>La Unidad Educativa  José Domingo de Santistevan tiene como misión "Formar integralmente a niños y jóvenes con mentalidad creadora, solidaria, productiva y crítica, fortalecida en el desarrollo del pensamiento y educación en valores y proveer a la sociedad de seres humanos competentes, optimizando los procesos e impulsando el desarrollo eficaz de nuestro talento humano, sastifaciendo las necesidades de los estudiantes, de el desarrollo del país, y de sus representantes".</p>
         <img src="https://santistevan.edu.ec/images/santistevanimagenes/Foto_Mision_y_Vision_JDS_2024.jpg" alt="Misión" width="400" height="300">  
    </div>
      <div class="vision">
        <h3>Visión</h3>
        <p>Ser una institución facilitadora de los aprendizajes significativos, detectar y desarrollar las inteligencias múltiples cimentadas en fundamentos pedagógicos holísticos, pensamientos renovadores, tecnologías modernas, afianzados también en los postulados de la religión católica y vigorizar con un segundo idioma que permita una formación sustentable, productiva y energizante para nuestros educandos.</p>
        <p>Concebimos la educación como un proceso activo, dinámico y con sentido de liderazgo, búsqueda de la excelencia y promueve la participación esencial de un grupo humano consciente  comprometido con el papel fundamental que desempeña en nuestra</p>
        <img src="https://santistevan.edu.ec/images/santistevan/noticias/2023/educacion_web.png" alt="Visión" width="400" height="300">
    </div>
    </div>
    <button onclick="mostrar('inicio')">Regresar a Inicio</button>
  </section>
  
  <!-- METODOLOGIA ACADEMICA -->
  <section id="metodologiaacademica">
    <h1>Metodología Académica</h1>
    <p>Nuestra misión es formar jóvenes con las competencias necesarias para desarrollar proyectos alineados con sus intereses y con un impacto social positivo. Para alcanzar estos objetivos, nos enfocamos en los siguientes resultados:</p>
    <div class="flex-contenido">
    <img src="https://santistevan.edu.ec/images/santistevanimagenes/metodologia_academica.jpg" alt="metodologia_academica" width="500" height="400">
    <div class="flex-texto">
     <h4>Altos Logros de Aprendizaje</h4>
     <p>- Certificación en inglés: Nivel B1.</p>
     <p>- Plan lector: 40 libros al año / 15 minutos de lectura diaria.</p>
     <p>- Convenio con SANTILLANA para evaluar habilidades en lectura y matemáticas.</p>
     <h4>Formación Humana y Acompañamiento Tutorial</h4>
     <p>- Enfoque en el humanismo cristiano.</p>
     <p>- Acompañamiento tutorial para la elaboración de proyectos de vida.</p>
     <p>- Fomento del liderazgo social.</p>
     <h4>Formación Profesional y Empleabilidad</h4>
     <p>- Desarrollo de competencias profesionales.</p>
     <p>- Formación Dual certificada por la Cámara Ecuatoriano-Alemana (AHK).</p>
     </div>
     </div>
     <p>.   </p>
      <h2>¿Cómo lo hacemos?</h2>
      <h4>Nuestros Sellos Educativos</h4>
       <p>Nuestro modelo educativo requiere tiempo. Acompañar y formar requiere tiempo y formación del formador.En este modelo, los recursos educativos, la infraestructura y el equipamiento están al servicio del aprendizaje.</p>
      <div class="flex-contenido">
      <img src="https://santistevan.edu.ec/images/santistevanimagenes/metodologia.jpg" alt="metodologia" width="500" height="400">
      <div class="flex-texto">
       <p>- Jornada Escolar Extendida: Garantizamos el tiempo necesario para un aprendizaje integral.</p>
       <p>- Recursos Educativos: Proveemos materiales y herramientas que enriquecen el proceso educativo.</p>
       <p>- Maestros en Constante Formación: Nuestros maestros son el corazón de todo, los capacitamos continuamente para ofrecer una formación de calidad.</p>
       <p>- Cultura de Evaluación: Implementamos evaluaciones constantes para mejorar y adaptar nuestra formación.</p>
       <p>- Infraestructura con Criterios Pedagógicos: Nuestras instalaciones están diseñadas para apoyar el aprendizaje efectivo.</p>
       </div>
       </div>
       <button onclick="mostrar('inicio')">Regresar a Inicio</button>
  </section>
  
  <!-- NIVELES DE ESTUDIO -->
  <section id="nivelesdeestudio">
    <h1>Inicial 2</h1>
    <p>En este nivel buscamos que los niños y las niñas aprendan y no solamente estudien por medio del concepto aprender-jugando lo que les permitirá explorar, experimentar y descubrir por sí mismos su entorno. Por ello, nuestros aprendices, desde edad temprana los incluimos en un sistema formativo que:</p>
    <div class="flex-contenido">
    <img src="https://santistevan.edu.ec/images/santistevanimagenes/Inicial_2.jpg" alt="Inicial_2" width="500" height="400">
    <div class="flex-texto">
      <p>- Desarrollo habilidades motrices a través del arte y el movimiento.</p>
      <p>- Aprendizaje divertido del Inglés.</p>
      <p>- Experimentación con el entorno natural.</p>
      <p>- Desarrollo del lenguaje</p>
      <p>- Creatividad y la imaginación.</p>
      <p>- Pensamiento lógico de forma lúdica.</p>
      <p>- Formación humana.</p>
      </div>
      </div>

      <h1>Educación General Básica</h1>
      <p>En este nivel fomentamos que los niños y niñas construyan aprendizaje de forma integral, promoviendo el "aprender- haciendo". Esto les permite indagar, aplicar y descubrir estrategias que les permite adquirir los siguientes logros de aprendizaje:</p>
      <div class="flex-contenido">
      <img src="https://santistevan.edu.ec/images/santistevanimagenes/Educacion_General_Basica.jpg" alt="Educacion_General_Basica" width="500" height="400">
      <div class="flex-texto">
      <p>- Exploran y reflexionan sobre el entorno físico.</p>
      <p>- Toman decisiones con razonamiento lógico y matemático.</p>
      <p>- Desarrollan procesos autónomos de aprendizaje.</p>
      <p>- Manejan responsablemente la tecnología (Tics).</p>
      <p>- Gestionan y lideran proyectos de emprendimiento económicos y sociales.</p>
      <p>- Reafirman su identidad.</p>
      <p>- Muestran respeto y tolerancia hacia diversas creencias.</p>
      <p>- Se comunican en su lengua materna y en inglés.</p>
      <p>- Valoran expresiones artísticas y crean las suyas.</p>
      <p>- Participan activamente en actividades físicas y de bienestar.</p>
      </div>
      </div>

      <h1>Bachillerato General Unificado</h1>
      <div class="flex-contenido">
      <img src="https://santistevan.edu.ec/images/santistevanimagenes/Bachillerato_General.jpg" alt="Bachillerato_General" width="500" height="400">
      <div class="flex-texto">
      <p>El Bachillerato es una etapa crucial en la preparación interdisciplinaria de los aprendices, facilitando tanto su integración al mundo laboral como la continuación de estudios en universidades o escuelas politécnicas. Con el apoyo del Departamento de Consejería Estudiantil, los jóvenes pueden elegir su perfil de manera acertada.</p>
      Contamos con el Bachillerato Dual, una metodología de enseñanza alemana que permite a los aprendices combinar su formación en el colegio y en la empresa durante los dos últimos años de bachillerato. Esta modalidad les brinda la oportunidad de adquirir experiencia laboral y obtener una certificación internacional alemana.</p>
      </div>
      </div> 
      <h4>Bachillerato en Ciencias</h4>
      <p>Este programa está diseñado para desarrollar habilidades y competencias en cualquier área, garantizando la excelencia académica. Ofrece herramientas para que los jóvenes puedan emprender en diversas áreas, continuar con estudios post-secundarios y prepararse para ser ciudadanos críticos y democráticos.</p>
    <button onclick="mostrar('inicio')">Regresar a Inicio</button>
    </section>

  <!-- NUEVA SECCION DE FORMULARIO DE RECLAMOS Y SUGERENCIAS -->
  <section id="contactenos">
    <h2>Formulario de Reclamos y Sugerencias</h2>
    <p>Tu opinión es muy importante para nosotros. Por favor, llena el siguiente formulario con tus inquietudes o sugerencias.</p>
    <form action="#" method="post">
      <label for="nombre">Nombre completo:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="correo">Correo electrónico:</label>
      <input type="email" id="correo" name="correo" required>

      <label for="tipo">Tipo de mensaje:</label>
      <select id="tipo" name="tipo">
        <option value="reclamo">Reclamo</option>
        <option value="sugerencia">Sugerencia</option>
        <option value="consulta">Consulta</option>
      </select>

      <label for="mensaje">Mensaje:</label>
      <textarea id="mensaje" name="mensaje" rows="6" required></textarea>

      <button type="submit">Enviar Mensaje</button>
    </form>

    <button onclick="mostrar('inicio')">Regresar a Inicio</button>
  </section>

  <footer>
    <p>&copy; 2025 Unidad Educativa José Domingo de Santistevan. Todos los derechos reservados.</p>
  </footer>

  <script>
    function mostrar(id) {
      const secciones = document.querySelectorAll("section");
      secciones.forEach(sec => sec.classList.remove("active"));
      document.getElementById(id).classList.add("active");
    }

    const imagenes = [
      "https://santistevan.edu.ec/images/santistevan/slide/2.png",
      "https://santistevan.edu.ec/images/santistevan/slide/slides%20de%20pgina%20web%202.png",
      "https://santistevan.edu.ec/images/santistevan/slide/4.png",
      "https://santistevan.edu.ec/images/santistevan/slide/5.png"
    ];

    let indice = 0;
    function iniciarCarrusel() {
      setInterval(() => {
        indice = (indice + 1) % imagenes.length;
        document.getElementById("imagen").src = imagenes[indice];
      }, 3000);
    }

    window.onload = iniciarCarrusel;
  </script>

</body>
</html>
