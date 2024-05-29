<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenido al WiFi del Parque</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            max-width: 500px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .header {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .content {
            margin: 20px 0;
        }
        .footer {
            font-size: 12px;
            color: #777;
        }
        button {
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">Bienvenido al WiFi del Parque</div>
        <div class="content">
            <p>Disfruta de acceso gratuito a Internet por hasta 1 hora.</p>
            <p>Haz clic en el botón de abajo para conectarte.</p>
            <button onclick="authenticate()">Conectar</button>
        </div>
        <div class="footer">Proporcionado por [Tu Organización]</div>
    </div>
    <script>
        function authenticate() {
            // Redirige al usuario a una URL de autenticación o éxito
            window.location.href = 'https://extreme.com.co/'; // Cambia esta URL a la página de destino después de la autenticación
        }
    </script>
</body>
</html>
