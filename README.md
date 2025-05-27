<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>¿Cómo estás?</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
    }
    #respuesta {
      display: none;
      margin-top: 30px;
    }
    img {
      max-width: 300px;
      margin-top: 20px;
    }
    button {
      padding: 10px 20px;
      margin: 10px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <h1>¿Cómo estás?</h1>

  <button onclick="mostrarRespuesta()">FELIZ</button>
  <button onclick="mostrarRespuesta()">TRISTE</button>

  <div id="respuesta">
    <h2>Escucha esto</h2>
    <img src="https://media.giphy.com/media/3oriO0OEd9QIDdllqo/giphy.gif" alt="Escucha esto">
  </div>

  <script>
    function mostrarRespuesta() {
      document.getElementById('respuesta').style.display = 'block';
    }
  </script>

</body>
</html>
