<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YoChef - Cursos de Cocina</title>
    <style>
        body {
            margin: 0;
            font-family: Lato;
            background-color: #b6cbe7;
            color: #769dd2;
        }

        header {
            background-color: #034cad;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #4682b4;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #87cefa;
        }

        .hero h1 {
            font-size: 2.5em;
        }

        .hero p {
            font-size: 1.2em;
        }

        .courses {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }

        .course {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 300px;
            padding: 20px;
            text-align: center;
        }

        .course img {
            max-width: 100%;
            border-radius: 5px;
        }

        .course h3 {
            color: #1e90ff;
            margin: 15px 0;
        }

        .course p {
            font-size: 0.9em;
            margin-bottom: 15px;
        }

        .course a {
            display: inline-block;
            text-decoration: none;
            color: #fff;
            background-color: #1e90ff;
            padding: 10px 20px;
            border-radius: 5px;
        }

        .course a:hover {
            background-color: #4682b4;
        }

        footer {
            background-color: #1e90ff;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>YoChef - Aprende a Cocinar con Nosotros</h1>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#cursos">Cursos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section class="hero">
        <h1>Descubre el Chef que Llevas Dentro</h1>
        <p>Aprende con nuestros cursos de cocina diseñados para todos los niveles.</p>
    </section>

    <section class="courses" id="cursos">
        <div class="course">
            <h3>Curso Básico de Cocina</h3>
            <p>Ideal para principiantes que quieren aprender las bases de la cocina.</p>
            <a href="#">Más Información</a>
        </div>

        <div class="course">
            <h3>Cocina Premium</h3>
            <p>Explora sabores del mundo y sorprende a tus amigos y familiares.</p>
            <a href="#">Más Información</a>
        </div>

        <div class="course">
            <h3>Repostería Avanzada</h3>
            <p>Para aquellos que quieren perfeccionar el arte de la repostería.</p>
            <a href="#">Más Información</a>
        </div>
    </section>

    <footer id="contacto">
        <p>Contacto: info@yochef.com | Teléfono: +34 123 456 789</p>
        <p>&copy; 2025 YoChef. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
