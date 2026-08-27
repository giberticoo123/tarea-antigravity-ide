# tarea-antigravity-ide
primer code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>[span_52](start_span)[span_52](end_span).</title>
</head>
<body>
     
     <h1>hola</h1>
     <p>[span_53](start_span)[span_53](end_span)[span_54](start_span)[span_54](end_span).</p>
  
</body>
</html>

code2
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Ejercicio de Formato Semántico</title>
</head>
<body>

    <p>
        Es <strong>fundamental entender las buenas prácticas de desarrollo web</strong> para construir sitios accesibles. Al estructurar el contenido, debes aplicar cada etiqueta con <em>precisión</em>.
    </p>

    <blockquote cite="https://www.w3.org/WAI/fundamentals/accessibility-intro/es">
        La web está diseñada para trabajar con todas las personas, independientemente de su hardware, software, idioma, ubicación o capacidad.
    </blockquote>

</body>
</html>
code3
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio Modelo de Caja</title>
</head>
<body>

    <div style="box-sizing: border-box; width: 300px; height: 150px; padding: 20px; margin: 30px; border: 2px solid #333; background-color: #e2e8f0;">Contenido del contenedor con Modelo de Caja aplicado.</div>

</body>
</html>
code4
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio de Apariencia de Texto</title>
    <style>
       
        body {
            font-family: Arial, Helvetica, sans-serif;
            text-align: center; 
        }

      
        h1 {
            font-size: 36px;
        }
    </style>
</head>
<body>
    <h1>Título Principal</h1>
    <p>Este es el texto principal de la página con los estilos de tipografía y alineación aplicados.</p>
</body>
</html>
code5
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio de Imagen Semántica</title>
</head>
<body>

    <figure>
        <img src="https://picsum.photos/600/400" alt="Fotografía de un paisaje natural con montañas al atardecer">
        <figcaption>Paisaje natural con montañas al atardecer reflejadas en un lago.</figcaption>
    </figure>

</body>
</html>

code6
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Sección Estilizada</title>
    <!-- 1. El CSS DEBE ir obligatoriamente dentro de la etiqueta <style> -->
    <style>
        /* Agregamos un fondo gris al body para que el cuadro blanco y su sombra resalten */
        body {
            background-color: #e2e8f0;
            font-family: sans-serif;
            padding: 40px;
        }

        /* Tu CSS corregido */
        .mi-seccion {
            background-color: #ffffff; 
            border-radius: 16px; 
            box-shadow: 0px 10px 25px rgba(0, 0, 0, 0.15); 
            padding: 24px; /* Añadido para que el texto no toque los bordes */
            max-width: 500px;
        }
    </style>
</head>
<body>

    <!-- 2. Tu HTML DEBE ir dentro del <body> -->
    <section class="mi-seccion">
        <h2>Título de la sección</h2>
        <p>Contenido explicativo dentro del contenedor.</p>
    </section>

</body>
</html>
code7
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulario de Ingreso de Usuarios</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
    }
    form {
      background-color: #ffffff;
      padding: 20px 30px;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 300px;
    }
    div {
      margin-bottom: 15px;
    }
    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 8px;
      box-sizing: border-box;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button[type="submit"] {
      width: 100%;
      padding: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
    }
    button[type="submit"]:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <!-- Requerimiento: Contenedor <form> que agrupa los campos -->
  <form action="#" method="POST">
    
    <h2>Ingreso de Usuarios</h2>

    <!-- Campo de usuario -->
    <div>
      <!-- Requerimiento: Etiqueta <label> asociada con el atributo "for" -->
      <label for="usuario">Usuario:</label>
      <!-- Requerimiento: Elemento <input> con type="text" -->
      <input type="text" id="usuario" name="usuario">
    </div>

    <!-- Campo de contraseña -->
    <div>
      <!-- Requerimiento: Etiqueta <label> asociada con el atributo "for" -->
      <label for="contrasena">Contraseña:</label>
      <!-- Requerimiento: Elemento <input> con type="password" -->
      <input type="password" id="contrasena" name="contrasena">
    </div>

    <!-- Requerimiento: Elemento <button type="submit"> para enviar -->
    <button type="submit">Enviar</button>

  </form>

</body>
</html>
code8
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menú de Navegación Horizontal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f9;
    }

    /* Estilos base para la navegación */
    nav {
      background-color: #333;
      padding: 15px 30px;
      border-radius: 8px;
    }

    /* Requerimiento 2: Aplicar el modelo Flexbox al contenedor mediante display: flex
      Requerimiento 3: Distribuir el espacio entre los ítems mediante justify-content: space-between
    */
    nav ul {
      display: flex;
      justify-content: space-between;
      align-items: center;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    /* Estilos de los enlaces */
    nav li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 16px;
      transition: background-color 0.3s;
    }

    nav li a:hover {
      background-color: #555;
      border-radius: 4px;
    }
  </style>
</head>
<body>

  <!-- Requerimiento 1: Estructurar los enlaces utilizando las etiquetas <nav>, <ul> y <li> -->
  <nav>
    <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#">Servicios</a></li>
      <li><a href="#">Proyectos</a></li>
      <li><a href="#">Nosotros</a></li>
      <li><a href="#">Contacto</a></li>
    </ul>
  </nav>

</body>
</html>
code9
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Reproductor Multimedia Interactivo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      color: #333;
      margin: 0;
      padding: 30px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .container {
      background-color: #ffffff;
      padding: 25px 30px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      max-width: 680px;
      width: 100%;
      box-sizing: border-box;
    }

    h1 {
      text-align: center;
      color: #2c3e50;
      margin-top: 0;
      margin-bottom: 25px;
    }

    .section {
      margin-bottom: 25px;
      padding-bottom: 20px;
      border-bottom: 1px solid #eee;
    }

    .section:last-child {
      border-bottom: none;
      margin-bottom: 0;
      padding-bottom: 0;
    }

    h2 {
      font-size: 1.2rem;
      color: #4a5568;
      margin-bottom: 12px;
    }

    /* Estilos para responsividad y ajuste visual */
    audio {
      width: 100%;
      outline: none;
    }

    video {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      background-color: #000;
      display: block;
      margin: 0 auto;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Integración de Archivos Multimedia</h1>

    <!-- Sección de Audio -->
    <!-- STREAMING_CHUNK:Insertando el reproductor de sonido con <audio> y <source>... -->
    <div class="section">
      <h2>Reproductor de Audio</h2>
      <!-- Requerimiento 1: Insertar reproductor con <audio> y atributo controls -->
      <audio controls>
        <!-- Requerimiento 3: Especificar la ruta mediante la etiqueta <source> -->
        <source src="https://www.w3schools.com/html/horse.mp3" type="audio/mpeg">
        <source src="https://www.w3schools.com/html/horse.ogg" type="audio/ogg">
        Tu navegador no soporta el elemento de audio.
      </audio>
    </div>

    <!-- Sección de Video -->
    <!-- STREAMING_CHUNK:Insertando el reproductor de video con <video>, dimensiones y <source>... -->
    <div class="section">
      <h2>Reproductor de Video</h2>
      <!-- Requerimiento 2: Insertar video mediante <video> definiendo dimensiones con width y height -->
      <video width="640" height="360" controls>
        <!-- Requerimiento 3: Especificar la ruta mediante la etiqueta <source> -->
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        <source src="https://www.w3schools.com/html/mov_bbb.ogg" type="video/ogg">
        Tu navegador no soporta el elemento de video.
      </video>
    </div>

  </div>

</body>
</html>
code10
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Instrucciones Secuenciales y Selección de Opciones</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      color: #333;
      margin: 0;
      padding: 30px;
      display: flex;
      justify-content: center;
    }

    .container {
      background-color: #ffffff;
      padding: 25px 30px;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      max-width: 500px;
      width: 100%;
    }

    h1 {
      font-size: 1.5rem;
      color: #2c3e50;
      margin-top: 0;
      margin-bottom: 20px;
      text-align: center;
    }

    h2 {
      font-size: 1.1rem;
      color: #4a5568;
      margin-bottom: 10px;
    }

    .section {
      margin-bottom: 25px;
    }

    /* Estilos para la lista ordenada */
    ol {
      padding-left: 20px;
      line-height: 1.6;
    }

    li {
      margin-bottom: 8px;
    }

    /* Estilos para el formulario y desplegable */
    label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
    }

    select {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
      background-color: #fff;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Instrucciones y Configuración</h1>

    <!-- Sección de Lista Secuencial -->
    <!-- STREAMING_CHUNK:Creando la lista secuencial con <ol> y <li>... -->
    <div class="section">
      <h2>Pasos de Configuración</h2>
      <!-- Requerimiento 1: Lista secuencial empleando <ol> e ítems <li> -->
      <ol>
        <li>Selecciona una opción del menú desplegable.</li>
        <li>Revisa las instrucciones de confirmación.</li>
        <li>Haz clic en guardar para aplicar los cambios.</li>
      </ol>
    </div>

    <!-- Sección de Selección de Opciones -->
    <!-- STREAMING_CHUNK:Creando el formulario con la lista desplegable <select> y sus <option>... -->
    <div class="section">
      <form action="#" method="POST">
        <label for="opciones">Elige un plan de suscripción:</label>
        
        <!-- Requerimiento 2: Lista desplegable utilizando la etiqueta <select> -->
        <select id="opciones" name="opciones">
          <!-- Requerimiento 3: Alternativas mediante etiquetas <option> -->
          <option value="">-- Selecciona una opción --</option>
          <option value="basico">Plan Básico</option>
          <option value="estandar">Plan Estándar</option>
          <option value="premium">Plan Premium</option>
        </select>
      </form>
    </div>
  </div>

</body>
</html>



