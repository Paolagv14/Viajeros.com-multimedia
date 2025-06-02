<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viajero.com</title>
    <style>
        /* Estilos básicos para la página */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 0.5em 0;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5em 1em;
            display: inline-block;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: 2em auto;
            background-color: white;
            padding: 2em;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h2 {
            color: #007BFF;
        }
        .section-content {
            margin-bottom: 2em;
        }
    </style>
</head>
<body>
    <header>
	<h1>VIAJEROS.COM</h1>
        <h2>Explora el Mundo con nosotros: ¡Elige tu destino ideal!</h2>
    </header>
    <nav>
        <a href="#seccion1">Brasil</a>
        <a href="#seccion2">Japon</a>
        <a href="#seccion3">España</a>
    </nav>

    <div class="container">
        <section id="seccion1" class="section-content">
            <h2>Brasil</h2>
            <p>Visita Brasil y siente el ritmo de la Samba</p>
            <a href="https://maps.app.goo.gl/gcWEHBKKUz71iDNS6" target="_blank" style="background-color: #007BFF; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px;">Ver en Street View</a>
        </section>

        <section id="seccion2" class="section-content">
            <h2>Japon</h2>
            <p>Descubre lo impresionante de Japon</p>
            <a href="https://maps.app.goo.gl/ttrnbMNCBdPRpvP87" target="_blank" style="background-color: #007BFF; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px;">Ver en Street View</a>
        </section>

        <section id="seccion3" class="section-content">
            <h2>España</h2>
            <p>Conoce uno de los monumentos más emblematicos de España</p>
            <a href="https://maps.app.goo.gl/QQFfhLLPa73g56SM8" target="_blank" style="background-color: #007BFF; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px;">Ver en Street View</a>
        </section>
    </div>

    <footer>
        <p>© 2025 Mi Página de Street View. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
