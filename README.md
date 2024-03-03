<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página con Botones</title>
    <style>
        .boton {
            display: block;
            margin-bottom: 10px;
            padding: 10px;
            background-color: #007bff;
            color: #fff;
            text-align: left;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .boton:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div>
        <button class="boton" onclick="abrirPagina('pagina1.html')">Botón 1</button>
        <button class="boton" onclick="abrirPagina('pagina2.html')">Botón 2</button>
        <button class="boton" onclick="abrirPagina('pagina3.html')">Botón 3</button>
    </div>

    <script>
        function abrirPagina(url) {
            window.location.href = url;
        }
    </script>
</body>
</html>

