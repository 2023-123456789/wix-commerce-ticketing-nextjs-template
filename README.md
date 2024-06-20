<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chiflon Norteño</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #ffd700;
            color: #333;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #4caf50;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
        }
        .about, .products, .contact {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
        .footer a {
            color: #ffd700;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Chiflon Norteño</h1>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#sobre-mi">Sobre Nosotros</a>
    <a href="#productos">Productos</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="inicio" class="about">
    <h2>Bienvenidos a Chiflon Norteño</h2>
    <p>Somos una empresa dedicada a la fabricación y distribución de snacks peruanos como chifles, papas y más. También distribuimos frutos secos de la región andina.</p>
</section>

<section id="sobre-mi" class="about">
    <h2>Sobre Nosotros</h2>
    <p>Chiflon Norteño es una empresa comprometida con ofrecer productos de alta calidad, respetando las tradiciones y sabores auténticos del Perú. Nos enorgullecemos de llevar los mejores snacks a tu mesa, hechos con ingredientes seleccionados y bajo estrictos estándares de calidad.</p>
</section>

<section id="productos" class="products">
    <h2>Nuestros Productos</h2>
    <ul>
        <li>Chifles</li>
        <li>Papas</li>
        <li>Snacks peruanos</li>
        <li>Frutos secos de la región andina</li>
    </ul>
</section>

<section id="contacto" class="contact">
    <h2>Contacto</h2>
    <p>Para más información, puedes seguirnos en nuestra página de Facebook:</p>
    <p><a href="https://www.facebook.com/chiflonnorteno/?locale=es_LA" target="_blank">Facebook de Chiflon Norteño</a></p>
</section>

<footer class="footer">
    <p>&copy; 2024 Chiflon Norteño. Todos los derechos reservados.</p>
</footer>

</body>
</html>
