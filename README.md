<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desarrollo Web y Análisis de Requisitos</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body { font-family: 'Segoe UI', Arial, sans-serif; background-color: #f8f9fa; color: #212529; }
        .bg-dark-custom { background-color: #343a40; }
        .text-light-custom { color: #f8f9fa; }
        .card-custom { border: none; transition: transform 0.3s ease, box-shadow 0.3s ease; }
        .card-custom:hover { transform: translateY(-5px); box-shadow: 0 8px 16px rgba(0,0,0,0.1); }
        .section-icon { font-size: 3rem; color: #007bff; margin-bottom: 1rem; }
        .footer-text { font-size: 0.9rem; }
        .btn-custom {
            background-color: #007bff;
            color: white;
            border-radius: 50px;
            padding: 10px 25px;
            text-transform: uppercase;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn-custom:hover { background-color: #0056b3; }
    </style>
</head>
<body>

    <header class="bg-dark-custom text-light-custom py-5 text-center">
        <div class="container">
            <h1 class="display-4 fw-bold">Desarrollo Web: Conceptos Clave</h1>
            <p class="lead">Un enfoque en la arquitectura, el diseño y la investigación para la creación de aplicaciones web.</p>
        </div>
    </header>

    <main class="container my-5">
        
        <section id="arquitectura" class="mb-5 py-5">
            <div class="row justify-content-center">
                <div class="col-lg-10 text-center">
                    <i class="fas fa-server section-icon"></i>
                    <h2 class="fw-bold mb-4">Arquitectura Cliente/Servidor</h2>
                    <p class="fs-5">
                        La arquitectura Cliente/Servidor es la estructura fundamental de la mayoría de las aplicaciones web dinámicas. En este modelo, el **cliente** (generalmente un navegador web) solicita información a un **servidor** remoto, que procesa la petición y envía una respuesta. Esta interacción constante permite que la web no sea una simple colección de documentos estáticos, sino un sistema interactivo y personalizado. Gracias a esta arquitectura, un usuario puede iniciar sesión, realizar compras en línea o acceder a información actualizada, ya que el servidor actúa como el cerebro que gestiona los datos y la lógica del negocio.
                    </p>
                </div>
            </div>
        </section>

        <hr class="my-5">

        <section id="diseno-centrado-usuario" class="mb-5 py-5">
            <div class="row justify-content-center">
                <div class="col-lg-10 text-center">
                    <i class="fas fa-user-check section-icon"></i>
                    <h2 class="fw-bold mb-4">Diseño Centrado en el Usuario (DCU)</h2>
                    <p class="fs-5">
                        El Diseño Centrado en el Usuario (DCU) es una filosofía que coloca al usuario en el centro de cada etapa del proceso de desarrollo de software. En lugar de enfocarse solo en la funcionalidad, el DCU prioriza la usabilidad y la experiencia del usuario final. El objetivo es crear interfaces intuitivas y eficientes que resuelvan los problemas reales de las personas de una manera sencilla y agradable. Este enfoque requiere investigación continua, pruebas con usuarios reales y un ciclo de retroalimentación constante para asegurar que el producto final sea valioso, útil y accesible para su audiencia.
                    </p>
                </div>
            </div>
        </section>

        <hr class="my-5">

        <section id="investigacion" class="mb-5 py-5">
            <div class="row justify-content-center">
                <div class="col-lg-10 text-center">
                    <i class="fas fa-search section-icon"></i>
                    <h2 class="fw-bold mb-4">Importancia de la Investigación en el Entorno</h2>
                    <p class="fs-5">
                        Para el análisis de requisitos en el desarrollo web, la investigación en el entorno es un paso crítico. Esta práctica va más allá de un simple cuestionario y busca entender el contexto real en el que se utilizará la aplicación. A través de entrevistas, observación directa y análisis del comportamiento de los usuarios, se pueden identificar necesidades no expresadas y problemas ocultos. Esta información es invaluable para definir los requerimientos y las especificaciones técnicas, garantizando que la aplicación no solo sea funcional, sino que también se adapte perfectamente al ambiente de sus usuarios, resultando en un producto final exitoso y de gran impacto.
                    </p>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-dark-custom text-light-custom text-center py-4 mt-5">
        <div class="container footer-text">
            <p class="mb-1">&copy; 2024 Proyecto de Desarrollo Web. Todos los derechos reservados.</p>
            <p class="mt-3">**Referencias bibliográficas (Normas APA 7.0):**</p>
            <p class="mb-0">*(Añade aquí las referencias que consultaste para el trabajo)*</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
