<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="refresh" content="60; url=https://www.gob.mx">
    <title>ERROR 404 - HACKED</title>
    <style>
        /* Estilos generales */
        body {
            background-color: black;
            color: #00FFFF;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            text-align: center;
            overflow: hidden;
        }
        h1, h2 {
            font-size: 50px;
            text-shadow: 0 0 20px #00FFFF, 0 0 30px #00FFFF, 0 0 40px #00FFFF, 0 0 50px #00FFFF;
        }
        h1 {
            margin-top: 50px;
        }
        h2 {
            font-size: 35px;
            margin-top: 20px;
            color: #FF0000;
        }
        .error-message {
            font-size: 40px;
            font-weight: bold;
            text-shadow: 0 0 10px red, 0 0 20px red, 0 0 30px red;
        }
        .cyber-text {
            font-size: 25px;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 0 0 5px #00FFFF, 0 0 10px #00FFFF, 0 0 15px #00FFFF;
        }
        .footer {
            position: fixed;
            bottom: 10px;
            width: 100%;
            color: #FF0000;
            font-size: 20px;
            text-align: center;
            animation: blink 1s infinite step-start;
        }
        .footer p {
            margin: 0;
        }
        .blink {
            animation: blink-animation 1s steps(5, start) infinite;
        }
        @keyframes blink-animation {
            50% {
                visibility: hidden;
            }
        }
        /* Animaciones */
        @keyframes glitch {
            0% { text-shadow: 0 0 2px #FF0000, 0 0 10px #00FFFF, 0 0 20px #00FFFF; }
            50% { text-shadow: 0 0 10px #FF0000, 0 0 30px #00FFFF, 0 0 40px #00FFFF; }
            100% { text-shadow: 0 0 20px #FF0000, 0 0 50px #00FFFF, 0 0 60px #00FFFF; }
        }
        .glitch-text {
            display: inline-block;
            font-size: 45px;
            font-weight: bold;
            animation: glitch 1s infinite alternate-reverse;
        }
        .hidden-message {
            display: none;
        }
        /* Música */
        .music {
            font-size: 30px;
            font-weight: bold;
            color: #FF0000;
            margin-top: 50px;
            text-shadow: 0 0 15px #FF0000, 0 0 30px #FF0000;
        }
    </style>
</head>
<body>
    <!-- Título principal -->
    <h1 class="glitch-text">HACKED BY <span class="blink">@4dmin_079</span></h1>
    <h2>GOBIERNO DE MÉXICO - PÁGINA INFECTADA</h2>

    <!-- Mensaje de error -->
    <div class="error-message">
        <p>Error 404: Página no encontrada</p>
        <p class="cyber-text">Vulnerabilidad detectada en el sistema</p>
    </div>

    <!-- Mensaje cibernético -->
    <div class="cyber-text">
        <p>Acceso no autorizado. Sistema comprometido.</p>
        <p class="hidden-message">Conexión establecida a red interna.</p>
    </div>

    <!-- Música de fondo -->
    <div class="music">
        <p>MÚSICA: ESTILO - HACKER - HOSTIL</p>
    </div>

    <!-- Footer con mensaje cibernético -->
    <div class="footer">
        <p>Iniciando reconfiguración... (Página controlada por @4dmin_079)</p>
    </div>

    <!-- Efecto de parpadeo y redireccionamiento -->
    <script>
        let errorMessage = document.querySelector('.error-message');
        setInterval(() => {
            errorMessage.classList.toggle('hidden-message');
        }, 500);

        // Redireccionamiento a una URL externa después de 60 segundos
        setTimeout(() => {
            window.location.href = "https://www.gob.mx";
        }, 60000);
    </script>
</body>
</html>