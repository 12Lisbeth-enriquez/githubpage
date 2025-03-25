<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida CV - Lisbeth Dayanara Enríquez Chuga</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #f5f5f5;
            color: #333;
        }
        .container {
            display: flex;
            width: 95%; /* Aumenté el ancho */
            max-width: 1400px; /* Mayor tamaño máximo */
            height: 95vh; /* Aumenté la altura */
            background: #ffffff;
            color: #222;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
        }

        .contact-info, .links {
            margin-top: 20px;
            text-align: left;
        }
        .contact-info a, .links a {
            color: #777;
            text-decoration: none;
            display: block;
            margin-top: 5px;
        }
        .contact-info a:hover, .links a:hover {
            text-decoration: underline;
        }
        .bio h2, .interests h2, .portfolio h2 {
            border-bottom: 2px solid #777;
            padding-bottom: 5px;
            margin-bottom: 10px;
            color: #555;
        }
        .bio p, .interests ul {
            font-size: 14px;
            color: #444;
        }
        .interests ul {
            list-style: none;
            padding-left: 0;
        }

        .sidebar {
            width: 30%;
            background: #e0e0e0;
            color: #333;
            text-align: center;
            padding: 30px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .sidebar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #555;
            margin-bottom: 15px;
        }
        .sidebar h2 {
            font-size: 22px;
        }

        .main-content {
            width: 70%;
            padding: 30px;
            overflow-y: auto;
        }
        .title {
            font-size: 26px;
            font-weight: bold;
            text-align: center;
            margin-bottom: 20px;
            color: #555;
        }

        .portfolio .tabs {
            display: flex;
            justify-content: space-around;
            background: #e0e0e0;
            color: #333;
            padding: 10px;
            border-radius: 5px;
        }
        .portfolio .tabs div {
            flex: 1;
            text-align: center;
            padding: 10px;
            cursor: pointer;
            transition: background 0.3s, color 0.3s;
        }
        .portfolio .tabs div:hover {
            background: #bdbdbd;
        }
        .portfolio .tabs div.active {
            background: #9e9e9e;
            font-weight: bold;
        }
        .tab-content {
            display: none;
            padding: 15px;
            background: #f5f5f5;
            border-radius: 5px;
            margin-top: 10px;
            color: #222;
        }
        .tab-content.active {
            display: block;
        }

        .year {
            background: #bdbdbd;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            text-align: center;
            transition: background 0.3s;
        }
        .year:hover {
            background: #9e9e9e;
        }
        .year-content {
            display: none;
            padding: 5px 15px;
            background: white;
            border-left: 4px solid #777;
            margin-top: 5px;
        }

        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                height: auto;
            }
            .sidebar {
                width: 100%;
                padding: 20px;
            }
            .main-content {
                width: 100%;
                padding: 20px;
            }
            .portfolio .tabs {
                flex-direction: column;
            }
        }
        .bio {
            padding: 20px;
        }

        .bio p {
            text-align: justify;
            line-height: 1.6;
            font-size: 16px;
            color: #444;
        }
    </style>
</head>
<body>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida CV - Lisbeth Dayanara Enríquez Chuga</title>
</head>
<body>

    <div class="container">
        <!-- Barra lateral -->
        <div class="sidebar">
            <img src="https://avatars.githubusercontent.com/u/202364198?s=400&u=ee9582aeef5a4b33335becb3a5a44cecf54ccd26&v=4" alt="Foto de perfil">
            <h2>Lisbeth Dayanara Enríquez Chuga</h2>
            <div class="contact-info">
                <p><strong>Correo:</strong> <a href="lisbethenriquezchuga@gmail.com"><i class="fas fa-envelope"></i> lisbethenriquezchuga@gmail.com</a></p>
                <p><strong>Teléfono:</strong> <a href="tel:+593 958787150"><i class="fas fa-phone"></i> +593 958787150</a></p>
            </div>
            <br>
            <div class="links">
                <h3>Links Externos</h3>
                <a href="https://upecedu-my.sharepoint.com/:b:/g/personal/lisbeth_enriquez_upec_edu_ec/EdMBGGd2Q5pCq2USg2lm6rkB64N1y3R1HvAwCH3z9oJItQ?e=3u7IA2"><i class="fas fa-file-pdf"></i> Hoja de vida PDF</a>
                <a href="https://www.linkedin.com/in/lisbeth-enriquez-a530452a8/"><i class="fab fa-linkedin"></i> LinkedIn</a>
            </div>
        </div>


        <!-- Sección Principal -->
        <div class="main-content">
            <div class="title">Hoja de Vida CV</div>

            <div class="bio">
                <h2>Biografía</h2>
                <p>
                    Ingeniera en Logística y Transporte por la Universidad Politécnica Estatal del Carchi, con formación en el diseño y optimización de los procesos relacionados con el aprovisionamiento, almacenamiento, distribución y transporte de bienes y servicios. Con el fin de mejorar la eficiencia en las cadenas de suministro, reducir costos y garantizar la satisfacción del cliente mediante estrategias operativas efectivas y el uso de tecnologías innovadoras.
                    <br>Especializada en la evaluación de la competitividad y la implementación de estrategias de expansión en el sector florícola, con experiencia en la optimización de la cadena de suministro y el análisis de gestión logística. Con conocimientos en BPMN y Bizagi para el modelado de procesos, así como en la teoría de las restricciones y el análisis competitivo basado en las cinco fuerzas de Porter. Apasionada por la investigación y aplicación de metodologías que permitan mejorar la eficiencia de las operaciones logísticas.
                    <br>Proactiva y orientada a resultados, con gran capacidad de adaptación y aprendizaje continuo. Poseo habilidades para el trabajo en equipo, la toma de decisiones bajo presión y la resolución de problemas de manera efectiva. Comprometida con la mejora continua y el uso de tecnologías emergentes para la optimización de los procesos empresariales. 
                </p> 
            </div>
            <div class="interests">
                <h2>Intereses Profesionales</h2>
                <ul>
                    <li><i class="fa-solid fa-bus"></i> Transporte y movilidad de pasajeros</li>
                    <li><i class="fa-solid fa-truck"></i> Logística y gestión de transporte</li>
                    <li><i class="fa-solid fa-cogs"></i> Optimización de procesos logísticos</li>
                    <li><i class="fa-solid fa-vr-cardboard"></i> Realidad virtual aplicada a procesos</li>
                </ul>
            </div>

            <style>
                .tab-content { display: none; background-color: #D3D3D3; padding: 15px; border-radius: 5px; }
                .tab-content.active { display: block; }
                .year { cursor: pointer; font-weight: bold; margin-top: 10px; }
                .year-content { display: none; padding-left: 20px; }
                .tabs { display: flex; gap: 10px; margin-bottom: 20px; }
                .tab-btn { cursor: pointer; padding: 10px; background: #D3D3D3; color: black; border-radius: 5px; }
            </style>
            
            <script>
                function toggleYear(yearId) {
                    var content = document.getElementById(yearId);
                    if (content.style.display === "none" || content.style.display === "") {
                        content.style.display = "block";
                    } else {
                        content.style.display = "none";
                    }
                }
                
                function showTab(tabId, element) {
                    var tabs = document.querySelectorAll('.tab-content');
                    tabs.forEach(tab => tab.classList.remove('active'));
                    document.getElementById(tabId).classList.add('active');
                    
                    var buttons = document.querySelectorAll('.tab-btn');
                    buttons.forEach(btn => btn.style.background = '#007BFF');
                    element.style.background = '#0056b3';
                }
            </script>
            
            <div class="portfolio">
                <h2>Portafolio de Proyectos</h2>
                <div class="tabs">
                    <div class="tab-btn" onclick="showTab('consultoria', this)">Proyectos Consultoría</div>
                    <div class="tab-btn" onclick="showTab('investigacion', this)">Proyectos Investigación</div>
                    <div class="tab-btn" onclick="showTab('cursos', this)">Cursos</div>
                    <div class="tab-btn" onclick="showTab('colaboraciones', this)">Colaboraciones</div>
                </div>
            
                <div id="consultoria" class="tab-content active">
                    <div class="year" onclick="toggleYear('pc2025')">2025</div>
                    <div id="pc2025" class="year-content">
                        <ul>
                            <li>Título del proyecto: Modelo de Evaluación de gestión Logística . Rol: Desarrollador.  Duración: 4 meses. Cliente o empresa: florícola León Roses. <a href="https://upecedu-my.sharepoint.com/:b:/g/personal/lisbeth_enriquez_upec_edu_ec/Eam102dMy_dBu3uqX65uMW8BzWjdjhYCEHWXnjIJxGj-eA?e=oatASQ">Link proyecto</a></li>
                        </ul>
                    </div>
                  
                </div>
            
                <div id="investigacion" class="tab-content">
                    <div class="year" onclick="toggleYear('pi2025')">2025</div>
                    <div id="pi2025" class="year-content">
                        <ul>
                            <li>Título del proyecto: Gestión Logística y competitividad del sector florícola de Pedro Moncayo y Mira [Trabajo de Integración Curricular]. Universidad Politécnica Estatal del Carchi. Año: 2025</li>

                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('pi2024')">2024</div>
                    <div id="pi2024" class="year-content">4
                        <ul>
                            <li>Título del proyecto: Diseño de rutas para el mejoramiento del servicio de transporte comercial, modalidad escolar e institucional, con las operadoras domiciliadas en la ciudad de Tulcán. Duración: 114 horas. Proyecto de vinculación con la sociedad.</li>
                           
                        </ul>
                    </div>
                </div>
            
                <div id="cursos" class="tab-content">
                    <div class="year" onclick="toggleYear('c2025')">2025</div>
                    <div id="c2025" class="year-content">
                        <ul>
                            <li>Formación de líderes en Programación y Tecnología: 40 horas. Universidad Politécnica Estatal del Carchi. 05 - 31 de marzo, 2025.</li>
                            
                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('c2024')">2024</div>
                    <div id="c2024" class="year-content">
                        <ul>
                            <li>Práctica de llenado de declaraciones aduaneras. Duración: 10 horas. My Intelecto, Ecuador. Noviembre.</li>
                           
                        </ul>
                    </div>
                </div>
            
                <div id="colaboraciones" class="tab-content">
                    <div class="year" onclick="toggleYear('col2025')">2025</div>
                    <div id="col2025" class="year-content">
                        <ul>
                            <li>Participación en proyecto de la Universidad Politécnica Estatal del Carchi para el diseño de un recorrido virtual, mediante captura de imágenes con cámara 360° por el campus universitario. Duración: 40 horas. Enlace: (Link vinculado con la publicación del recorrido virtual de la Universidad).</li>

                        </ul>
                    </div>
                    <div class="year" onclick="toggleYear('col2024')">2024</div>
                    <div id="col2024" class="year-content">
                        <ul>
                            <li>Asisten de Investigación sobre eficiencia en transporte de mercancías</li>
                        </ul>
                    </div>
                </div>
            </div>
        <!-- Archivos CSS -->
        <link rel="stylesheet" href="../hv/css/main.css" />
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
        
    <!-- Scripts -->
    <script src="../hv/js/main.js"></script>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
