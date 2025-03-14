<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ibiza Tattoo - Temporada 2025</title>
    <style>
        body {
            font-family: Helvetica, sans-serif;
            font-size: 11px;
            letter-spacing: 2px;
            text-transform: uppercase;
            background: #FFFFFF;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background: #FFFFFF;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 350px;
            border: 3px solid #0000FF;
            text-align: center;
            margin: auto;
        }
        h1 {
            font-family: Helvetica, sans-serif;
            font-size: 48px;
            text-align: center;
            margin-bottom: 10px;
            letter-spacing: 4px;
            color: #0000FF;
            text-transform: uppercase;
            transition: color 0.8s ease-in-out;
            -webkit-text-stroke: 2px #0000FF;
            text-stroke: 2px #0000FF;
        }
        h1:hover {
            color: transparent;
        }
        .subtitle {
            text-align: center;
            font-size: 11px;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-top: 10px;
            text-align: left;
        }
        input, textarea, select {
            width: 100%;
            padding: 6px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 11px;
            letter-spacing: 0px;
            text-transform: lowercase;
            color: #0000FF;
        }
        button {
            background-color: white;
            color: #0000FF;
            padding: 8px;
            border: 2px solid #0000FF;
            border-radius: 5px;
            width: 100%;
            cursor: pointer;
            margin-top: 15px;
            font-size: 11px;
            letter-spacing: 2px;
            text-transform: uppercase;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        button:hover {
            background-color: #0000FF;
            color: white;
        }
        .thank-you {
            display: none;
            font-size: 16px;
            color: #0000FF;
            text-align: center;
            line-height: 1.5;
        }
        .heart {
            display: block;
            font-size: 14px;
            margin-top: 5px;
        }
    </style>
    <script>
        function mostrarMensaje(event) {
            event.preventDefault();
            document.querySelector('.container').style.display = 'none';
            document.querySelector('.thank-you').style.display = 'block';
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>IBIZA TATTOO</h1>
        <p class="subtitle">_ Temporada 2025 _</p>
        <form onsubmit="mostrarMensaje(event)" action="mailto:criaturacreadoraa@gmail.com" method="post" enctype="multipart/form-data">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            
            <label for="instagram">Instagram Profesional:</label>
            <input type="text" id="instagram" name="instagram" required>
            
            <label for="fotos">Adjunta 3 fotos de tatuajes curados:</label>
            <input type="file" id="fotos" name="fotos" accept="image/*" multiple required>
            
            <label for="primera-temporada">¿Es tu primera temporada en Ibiza?</label>
            <select id="primera-temporada" name="primera-temporada">
                <option value="sí">Sí</option>
                <option value="no">No</option>
            </select>
            
            <label for="idiomas">Idiomas que dominas:</label>
            <input type="text" id="idiomas" name="idiomas" required>
            
            <label for="presentacion">Cuéntanos más sobre ti:</label>
            <textarea id="presentacion" name="presentacion" rows="4" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </div>
    <div class="thank-you">Gracias por tu tiempo <br><span class="heart">&lt;3</span></div>
</body>
</html>
