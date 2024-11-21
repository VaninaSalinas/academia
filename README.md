<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beauty Center Academy</title>
    <style>
        /* Menú de navegación */
nav {
    position: sticky;
    top: 0;
    background-color: #7a6cc9;
    padding: 10px 0;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}
nav ul li {
    margin: 0 15px;
}
nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.2rem;
    padding: 10px 15px;
    border-radius: 5px;
    transition: background-color 0.3s;
}
nav ul li a:hover {
    background-color: #5645a0;
}
        /* Resetear los estilos por defecto del navegador */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }
        /* Contenedor principal */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Encabezado de la página */
        header {
            text-align: center;
            padding: 30px 0;
            background-color: #786ac7;
            color: white;
            border-radius: 8px;
        }
        header h1 {
            font-size: 3rem;
        }
        header p {
            font-size: 1.2rem;
        }

        /* Sección de información */
        .info-emprendimiento {
            margin-top: 40px;
        }
        .info-emprendimiento h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .info-emprendimiento p {
            font-size: 1.1rem;
            margin-bottom: 20px;
        }

        .info-emprendimiento ul {
            list-style: none;
            padding-left: 20px;
        }
        .info-emprendimiento ul li {
            font-size: 1rem;
            margin-bottom: 10px;
        }

        .boton-enlace {
            text-align: center;
            margin-top: 40px;
        }

        .boton-enlace a {
            background-color: #6755b6;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2rem;
        }
        .boton-enlace a:hover {
            background-color: #472c72;
        }
        @media (max-width: 768px) {
    header h1 {
        font-size: 2.5rem; /* Reduce el tamaño para pantallas medianas */
    }

    header p {
        font-size: 1rem; /* Ajusta el tamaño del párrafo */
    }
}

@media (max-width: 480px) {
    header h1 {
        font-size: 2rem; /* Ajuste aún más pequeño para móviles */
    }

    header p {
        font-size: 0.9rem; /* Ajuste del tamaño del párrafo para móviles */
    }
}
@media (max-width: 768px) {
    .container {
        padding: 15px; /* Reducir el padding en pantallas más pequeñas */
    }
}
@media (max-width: 768px) {
    .formulario-comentarios input,
    .formulario-comentarios textarea {
        padding: 12px; /* Ajuste del padding para pantallas más pequeñas */
    }

    .formulario-comentarios button {
        padding: 12px; /* Ajuste en el botón */
    }
}
@media (max-width: 768px) {
    section {
        padding: 30px 0; /* Reducir el padding superior e inferior en pantallas pequeñas */
    }
}
@media (max-width: 480px) {
    .comentario {
        padding: 10px; /* Reducir el padding para mejor ajuste en dispositivos móviles */
    }
}
@media (max-width: 768px) {
    nav ul {
        flex-direction: column; /* Cambia la dirección de los elementos de horizontal a vertical */
        align-items: center; /* Centra los elementos verticalmente */
    }

    nav ul li {
        margin: 10px 0; /* Aumenta el margen entre los enlaces en vista móvil */
    }

    nav ul li a {
        font-size: 1rem; /* Ajusta el tamaño de fuente */
        padding: 12px; /* Ajusta el padding para mejor visualización */
    }
}
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#comentarios">Mi historia</a></li>
            <li><a href="#info">como trabajo</a></li>
        </ul>
    </nav>
    <section id="inicio">
<!-- Contenedor principal de la página -->
<div class="container">
    <header>
        <h1>Conoce Beauty Center Academy</h1>
        <p>¡Estamos aquí para ofrecerte lo mejor! Descubre lo que hacemos y toda la experiencia
            que brindamos.</p>
    </header>

        
        <h2>¿Qué hacemos aqui? Veras...</h2>
        <p>
            En mi academia ofrecemos una enseñanza profesional que fue adquirida
            durante años, te enseñare a hacer diseños de uñas hermosos y a que seas capaz de hacer
            lo que te impongas ya sea como meta personal o laboral. No sera sencillo, nada lo es, pero ofrecemos 
            las mejores estrategias y metodos para que puedas ser una grandiosa manicurista.
        </p>
        <h2>Y esto no es todo, pues...</h2>
        <p>Tambien ofrezco mi gran experiencia haciendo pestañas, y debo decir que, aunque luzca como una tarea sencilla, no lo es.
           De hecho, hay que tenerle mucha paciencia y motivacion al arte de la estetica. Dar una gota de experiencia por cada pestaña colocada, 
           una gota por la paciencia dedicada y una gota por los minutos y horas trabajando en ello.
        </p>
        <section id="comentarios">
            <!-- Información sobre el emprendimiento -->
            <div class="info-emprendimiento">
        
                <h2>¿Quieres saber quien soy?</h2>
                <p>
                    Mi nombre es Mayra y tengo más de 10 años de experiencia en el apasionante mundo de la estética. Desde que comencé mi carrera, descubrí mi amor por el arte de las uñas y las pestañas, lo que me condujo a explorar cada vez más en este campo. A lo largo de los años, he tenido la oportunidad de capacitarme con diversos profesionales y adquirir conocimientos valiosos que me han permitido perfeccionar mi técnica y desarrollar una visión única.
        
        Mi pasión por la estética no solo se limita a la práctica, sino que también me motiva a compartir lo que he aprendido. Es por eso que quiero dar clases y transmitir mis conocimientos a quienes, como yo, estén interesados en este hermoso arte...
         Estoy comprometida personalmente en brindar tips prácticos y estrategias de mejora, que he adquirido a través de mi experiencia personal y asistiendo a capacitaciones.
        
        Mi objetivo es inspirar y empoderar a otros en su camino en la estética, compartiendo mi conocimiento y amor por este trabajo, para que juntos podamos seguir creciendo y reinventándonos en un mundo tan creativo.
        </section>
        </p>
        <h2>Nuestros Valores</h2>
        <ul>
            <li><strong>Innovación:</strong> Siempre estamos buscando nuevas ideas y soluciones.</li>
            <li><strong>Compromiso:</strong> Nos comprometemos con la calidad y satisfacción de nuestros clientes.</li>
            <li><strong>Responsabilidad social:</strong> Trabajamos con ética y apoyamos causas locales.</li>
            <li><strong>Sostenibilidad:</strong> Nos esforzamos por tener un impacto positivo en el medio ambiente.</li>
        </ul>

        <h2>¿Cómo contactarnos?</h2>
        <p>
            Si tienes alguna pregunta o quieres saber más, no dudes en ponerte en contacto con nosotros:
        </p>
        <ul>
            <li><strong>Teléfono:</strong> +598 94 651 659</li>
            <li><strong>Redes Sociales:</strong> ...</li>
        </ul>
    </div>

    <!-- Botón para volver a la página de comentarios -->
    <div class="boton-enlace">
        <a href="C:\Users\mimit\Desktop\programar\ejemplo.html">Ver los Comentarios</a>
    </div>
</div>

</body>
</html>
