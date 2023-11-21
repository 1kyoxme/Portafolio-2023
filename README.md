<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Portfolio</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <!-- MENU ENCABEZADO -->
    <div class="contenedor-header">
        <header>
            <div class="logo">
                <a href="#">Carlos</a>
            </div>
            <nav id="nav">
                <ul>
                    <li><a href="#inicio" onclick="seleccionar()">INICIO</a></li>
                    <li><a href="#sobremi" onclick="seleccionar()">SOBRE MI</a></li>
                    <li><a href="#curriculum" onclick="seleccionar()">CURRICULUM</a></li>
                    <li><a href="#contacto" onclick="seleccionar()">CONTACTO</a></li>
                </ul>
            </nav>
            <div class="nav-responsive" onclick="mostrarOcultarMenu()">
                <i class="fa-solid fa-bars"></i>
            </div>
        </header>
    </div>

    <!-- SECCION INICIO -->
    <section id="inicio" class="inicio">
        <div class="contenido-banner">
            <div class="contenedor-img">
                <img src="https://pbs.twimg.com/profile_images/1718555544934404096/jRzuABAw_400x400.jpg" alt="">
            </div>
            <h1>Carlos Canal</h1>
            <h2>Tecnico Informatico - Especializado en Programacion</h2>
            <div class="redes">
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
            </div>
        </div>
    </section>

    <!-- SECCION SOBRE MI -->
    <section id="sobremi" class="sobremi">
    <section id="sobremi" class="sobremi">
        <div class="contenido-seccion">
            <h2>Sobre Mí</h2>
            <p><span>Hola, soy Carlos Canal.</span> Tengo 19 años, me especializo generalmente en Programacion (HTML, CSS y JS), Informatica basica y Atencion al cliente. Mis conocimientos antes dichos fueron desarrollados y mejorados en la 'Escuela de Educación Secundaria Técnica N°1 Gral. JOSÉ DE SAN MARTÍN' ubicada en Buenos Aires, Argentina.</p>

            <div class="fila">
                <!-- datos personales -->
                <div class="col">
                    <h3>Datos Personales</h3>
                    <ul>
                        <li>
                            <strong>Cumpleaños</strong>
                            25-06-2004
                        </li>
                        <li>
                            <strong>Teléfono</strong>
                            11-3367-88766
                        </li>
                        <li>
                            <strong>Email</strong>
                            ikyoxme43@gmail.com
                        </li>
                        <li>
                            <strong>Dirección</strong>
                            Buenos Aires, Argentina
                        </li>
                        <li>
                            <strong>Cargo</strong>
                            <span>FREELANCE</span>
                        </li>
                    </ul>
                </div>

                <!-- intereses -->
                <div class="col">
                    <h3>Intereses</h3>
                    <div class="contenedor-intereses">
                        <div class="interes">
                            <i class="fa-solid fa-gamepad"></i>
                            <span>JUEGOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-headphones"></i>
                            <span>MUSICA</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-plane"></i>
                            <span>VIAJAR</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-person-hiking"></i>
                            <span>DEPORTE</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-book"></i>
                            <span>LIBROS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-car"></i>
                            <span>AUTOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-camera"></i>
                            <span>FOTOS</span>
                        </div>
                        
                    </div>
                </div>
            </div>
            <button>
                Descargar CV <i class="fa-solid fa-download"></i>
                <span class="overlay"></span>
            </button>
        </div>
    </section>

    <!-- SECCION CURRICULUM -->
    <section id="curriculum" class="curriculum">
        <div class="contenido-seccion">
            <h2>Curriculum</h2>
            <div class="fila">
                <div class="col izquierda">
                    <h3>Educación</h3>
                    <div class="item izq">
                        <h4>Tecnicatura</h4>
                        <span class="casa">Escuela de Educación Secundaria Técnica N°1</span>
                        <span class="fecha">2019 - 2024</span>
                        <p>Especializacion en Informatica (Armado y desarmado de una PC), Conocimiento de Software como Visual Studio, Notepad++, Photoshop y FL Studio; Conocimientos basicos de Sistemas DIgitales (Compuertas, Byts, Tabla de la verdad y Componentes). </p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <div class="item izq">
                        <h4>Primario</h4>
                        <span class="casa">Colegio Santa Soledad Torres Acosta</span>
                        <span class="fecha">2009 - 2015</span>
                        <p>Conocimientos basicos en Materias como Informatica, Matematicas, Literatura, Ingles, Arte, Educacion fisica, etc.</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                </div>

                <div class="col derecha">
                    <h3>Experiencia de trabajo</h3>
                    <div class="item der">
                        <h4>Tecnico Informatico</h4>
                        <span class="casa">Actualmente sin Trabajo</span>
                        <p>Estoy abierto a cualquier propuesta de trabajo la cual cumpla con mis conocimientos anteriormente mencionados en la columna 'Educacion'.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Atencion al Cliente</h4>
                        <span class="casa">Casa de Familia</span>
                        <span class="fecha">2015- Actualmente</span>
                        <p>Ayudo a mi familia en dos negocios de perfumeria, tintureria y pañalera, de los cuales he adquirido conocimientos para la atencion al cliente.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION CONTACTO -->
    <section id="contacto" class="contacto">
        <div class="contenido-seccion">
            <h2>CONTACTO</h2>
            <div class="fila">
                <!-- Formulario -->
                <div class="col">
                    <input type="text" placeholder="Tú Nombre">
                    <input type="text" placeholder="Número telefónico">
                    <input type="text" placeholder="Dirección de correo">
                    <input type="text" placeholder="Tema">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Mensaje"></textarea>
                    <button>
                        Enviar Mensaje<i class="fa-solid fa-paper-plane"></i>
                        <span class="overlay"></span>
                    </button>
                </div>
                <!-- Mapa -->
                <div class="col">
                    <img src="img/ubicacion.png" alt="">
                    <div class="info">
                        <ul>
                            <li>
                                <i class="fa-solid fa-location-dot"></i>
                                Malvinas Argenitinas, Grand Bourg
                            </li>
                            <li>
                                <i class="fa-solid fa-mobile-screen"></i>
                                Contactame: 11-3367-88766 
                            </li>
                            <li>
                                <i class="fa-solid fa-envelope"></i>
                                Email: ikyoxme43@gmail.com
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- footer -->
    <footer>
        <a href="#inicio" class="arriba">
            <i class="fa-solid fa-angles-up"></i>
        </a>
        <div class="redes">
            <a href="#"><i class="fa-brands fa-instagram"></i></a>
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
