<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Portafolio Profesional</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Estilos personalizados */
        body {
            font-family: 'Arial', sans-serif;
        }

        h1, h2 {
            font-weight: bold;
        }

        header {
            background-color: #343a40;
            color: white;
            padding: 50px 0;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
        }

        #about {
            margin-top: 50px;
        }

        #tecnologias i {
            font-size: 4rem;
            color: #007bff;
            margin-bottom: 15px;
        }

        .card img {
            height: 200px;
            object-fit: cover;
        }

        .card {
            margin-bottom: 30px;
        }

        #contacto ul {
            padding: 0;
        }

        #contacto ul li {
            margin: 0 15px;
        }

        #contacto ul li a {
            font-size: 18px;
            text-decoration: none;
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header>
        <h1>Portafolio Profesional</h1>
        <p>Desarrollado con HTML, CSS y Bootstrap</p>
    </header>

    <!-- Sobre mí -->
    <section id="about" class="container">
        <h2>Sobre mí</h2>
        <p>Soy una persona responsable, puntual y con una actitud sumamente positiva y proactiva hacia cualquier tarea
            que se me asigne. Mi disposición para aprender nuevas cosas es una de mis principales fortalezas, y tengo
            un fuerte deseo de desarrollarme tanto en el ámbito profesional como personal. Mi objetivo principal es
            cultivar habilidades diversas que me permitan enfrentar desafíos de manera eficiente y creativa. Aunque mi
            experiencia en JavaScript, HTML y CSS es limitada, estoy profundamente comprometido con el proceso de
            aprendizaje en estos campos tecnológicos tan dinámicos y emocionantes.</p>
    </section>

    <!-- Tecnologías Utilizadas -->
    <section id="tecnologias" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center">Tecnologías Utilizadas</h2>
            <div class="row text-center mt-4">
                <div class="col-md-4">
                    <i class="bi bi-filetype-html5 display-1"></i>
                    <h4>HTML5</h4>
                    <p>Maquetación semántica y estructurada para páginas web.</p>
                </div>
                <div class="col-md-4">
                    <i class="bi bi-filetype-css3 display-1"></i>
                    <h4>CSS3</h4>
                    <p>Estilos avanzados para interfaces atractivas y modernas.</p>
                </div>
                <div class="col-md-4">
                    <i class="bi bi-bootstrap display-1"></i>
                    <h4>Bootstrap 5</h4>
                    <p>Diseños responsivos y componentes preconfigurados.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Proyectos -->
    <section id="proyectos" class="container mt-5">
        <h2 class="text-center">Proyectos</h2>
        <div class="row mt-4">
            <div class="col-md-6">
                <div class="card">
                    <img src="https://via.placeholder.com/600x400" class="card-img-top" alt="Proyecto 1">
                    <div class="card-body">
                        <h5 class="card-title">Proyecto 1</h5>
                        <p class="card-text">Descripción del proyecto 1, utilizando HTML y CSS para crear una landing page moderna.</p>
                        <a href="#" class="btn btn-primary">Ver Proyecto</a>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card">
                    <img src="https://via.placeholder.com/600x400" class="card-img-top" alt="Proyecto 2">
                    <div class="card-body">
                        <h5 class="card-title">Proyecto 2</h5>
                        <p class="card-text">Descripción del proyecto 2, utilizando Bootstrap para crear un sitio web responsivo.</p>
                        <a href="#" class="btn btn-primary">Ver Proyecto</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="row mt-4">
            <div class="col-md-6">
                <div class="card">
                    <img src="https://via.placeholder.com/600x400" class="card-img-top" alt="Proyecto 3">
                    <div class="card-body">
                        <h5 class="card-title">Proyecto 3</h5>
                        <p class="card-text">Descripción del proyecto 3, una página web interactiva utilizando JavaScript.</p>
                        <a href="#" class="btn btn-primary">Ver Proyecto</a>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card">
                    <img src="https://via.placeholder.com/600x400" class="card-img-top" alt="Proyecto 4">
                    <div class="card-body">
                        <h5 class="card-title">Proyecto 4</h5>
                        <p class="card-text">Descripción del proyecto 4, integración de API REST utilizando JavaScript.</p>
                        <a href="#" class="btn btn-primary">Ver Proyecto</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="bg-dark text-white py-5">
        <div class="container text-center">
            <h2>Contacto</h2>
            <p>Puedes contactarme a través de los siguientes medios:</p>
            <ul class="list-inline">
                <li class="list-inline-item"><a href="mailto:tu_email@example.com" class="text-white">Email</a></li>
                <li class="list-inline-item"><a href="https://github.com/tu_usuario" class="text-white">GitHub</a></li>
                <li class="list-inline-item"><a href="https://www.linkedin.com/in/tu_perfil" class="text-white">LinkedIn</a></li>
            </ul>
        </div>
    </section>

    <!-- Bootstrap JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
