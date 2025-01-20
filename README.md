<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Recursos - Melilla</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <!-- Cabecera -->
    <header>
        <div class="navbar">
            <div class="logo">
                <h1>Catálogo de Recursos</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#recursos">Recursos</a></li>
                    <li><a href="#imagenes-lugares">Lugares</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Sección de Introducción -->
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Bienvenido al Catálogo de Recursos de Melilla</h2>
            <p>Descubre programas y servicios para la orientación, formación e inserción sociolaboral en Melilla.</p>
        </div>
    </section>

    <!-- Barra de búsqueda -->
    <section class="search-bar">
        <input type="text" id="search" placeholder="Buscar recursos por nombre o tipo..." onkeyup="searchResources()">
    </section>

    <!-- Filtros por tipo de recurso -->
    <section class="filters">
        <h2>Filtrar por tipo de recurso</h2>
        <div class="filter-buttons">
            <button onclick="filterResources('Empleo y Formación')">Empleo y Formación</button>
            <button onclick="filterResources('Orientación e inserción sociolaboral')">Orientación e Inserción Sociolaboral</button>
            <button onclick="filterResources('Programas de inserción sociolaboral')">Programas de Inserción Sociolaboral</button>
            <button onclick="filterResources('Inserción sociolaboral y formación')">Inserción Sociolaboral y Formación</button>
            <button onclick="filterResources('')">Mostrar Todos</button>
        </div>
    </section>

    <!-- Listado de Recursos -->
    <section id="recursos" class="resources">
        <h2>Recursos Disponibles</h2>
        <div class="resources-container">
            <!-- Recurso 1 -->
            <div class="resource" data-type="Empleo y Formación">
                <h3>Melilla Orienta</h3>
                <p><strong>Colectivos:</strong> Desempleados, jóvenes, personas en riesgo de exclusión social</p>
                <p><strong>Contacto:</strong> C/ La Dalia, 36, 52006 Melilla</p>
                <p><a href=" https://melillaorienta.com" target="_blank">Página web</a></p>
            </div>

            <!-- Recurso 2 -->
            <div class="resource" data-type="Orientación e inserción sociolaboral">
                <h3>Centro de Melilla de la Red COE</h3>
                <p><strong>Colectivos:</strong> Desempleados, jóvenes y emprendedores</p>
                <p><strong>Contacto:</strong> Calle Pablo Vallescá, 12, 52001 Melilla</p>
                <p><a href=" RedCOE@sepe.es">Página web</a></p>
            </div>

            <!-- Recurso 3 -->
            <div class="resource" data-type="Programas de inserción sociolaboral">
                <h3>Fundación Diagrama – Programa TALEM</h3>
                <p><strong>Colectivos:</strong> Jóvenes en riesgo de exclusión social</p>
                <p><strong>Contacto:</strong> Avda. Juan Carlos I Rey, nº 11 – 2ºB, 52001 Melilla</p>
                <p><a href="https://fundaciondiagrama.org" target="_blank">Página web</a></p>
            </div>

            <!-- Recurso 4 -->
            <div class="resource" data-type="Inserción sociolaboral y formación">
                <h3>Proyecto Melilla (PROMESA)</h3>
                <p><strong>Colectivos:</strong> Desempleados, jóvenes y adultos sin cualificación laboral</p>
                <p><a href="https://promesa.com" target="_blank">Página web</a></p>
            </div>

            <!-- Recurso 5 -->
            <div class="resource" data-type="Inserción sociolaboral y formación">
                <h3>Cruz Roja Melilla – Programa de Empleo</h3>
                <p><strong>Colectivos:</strong> Personas en riesgo de exclusión, inmigrantes, mujeres víctimas de violencia de género y jóvenes</p>
                <p><strong>Contacto:</strong> C/ Mar Chica, 12, 52006 Melilla</p>
                <p><strong>Teléfono:</strong> 952 68 88 88</p>
            </div>
        </div>
        <!-- Nuevos Recursos Añadidos -->

<!-- Recurso 6 -->
<div class="resource" data-type="Empleo y Formación">
<h3>Centro de Formación Profesional para el Empleo</h3>
<p><strong>Colectivos:</strong> Personas desempleadas, jóvenes y personas en riesgo de exclusión</p>
<p><strong>Contacto:</strong> C/ Gabriel de Morales, 8, 52001 Melilla</p>
<p><a href=" https://sepe.es" target="_blank">Página web</a></p>
</div>

<!-- Recurso 7 -->
<div class="resource" data-type="Apoyo al autoempleo y asesoramiento empresarial">
<h3>Asociación de Empresarios de Melilla (AEM)</h3>
<p><strong>Colectivos:</strong> Emprendedores, pequeñas y medianas empresas</p>
<p><strong>Contacto:</strong> Avda. Juan Carlos I Rey, nº 4, 52001 Melilla</p>
<p><a href="info@aemmelilla.org">Página web</a></p>
</div>

<!-- Recurso 8 -->
<div class="resource" data-type="Planes de empleo">
<h3>Plan de Empleo de Melilla - SEPE</h3>
<p><strong>Colectivos:</strong> Desempleados de larga duración, jóvenes y mayores de 45 años</p>
<p><strong>Contacto:</strong> C/ Alfonso XIII, 14, 52001 Melilla</p>
<p><a href="https://sepe.es" target="_blank">Página web</a></p>
</div>

<!-- Recurso 9 -->
<div class="resource" data-type="Empleo y Formación">
<h3>Asociación AMPA Down Melilla – Servicio Prelaboral</h3>
<p><strong>Colectivos:</strong> Personas con discapacidad intelectual</p>
<p><strong>Contacto:</strong> C/ Querol, 5, 52006 Melilla</p>
<p><a href=" ampadownmelilla@gmail.com">Página web</a></p>
</div>

<!-- Recurso 10 -->
<div class="resource" data-type="Empleo protegido">
<h3>Enclave laboral de la Asociación de Personas con Discapacidad (ADIMEL)</h3>
<p><strong>Colectivos:</strong> Personas con discapacidad física y sensorial</p>
<p><strong>Contacto:</strong> C/ Pablo Vallescá, 12, 52001 Melilla</p>
<p><a href="adimel@outlook.es">Página web</a></p>
</div>

<!-- Recurso 11 --><div class="resource" data-type="Programas de inserción sociolaboral">
<h3>Escuela Taller “Melilla Joven”</h3>
<p><strong>Colectivos:</strong> Jóvenes desempleados menores de 25 años</p>
<p><strong>Contacto:</strong> C/ Mar Chica, 8, 52001 Melilla</p>
<p><a href="https://empleo.es" target="_blank">Página web</a></p>
</div>

<!-- Recurso 12 -->
<div class="resource" data-type="Orientación e inserción sociolaboral">
<h3>Agencia de Colocación Melilla Activa</h3>
<p><strong>Colectivos:</strong> Personas desempleadas, empresas locales</p>
<p><strong>Contacto:</strong> Plaza de España, s/n, 52001 Melilla</p>
<p><a href="info@melillaactiva.com">Página web</a></p>
</div>

<!-- Recurso 13 -->
<div class="resource" data-type="Centro ocupacional">
<h3>Centro Ocupacional Reina Sofía</h3>
<p><strong>Colectivos:</strong> Personas con discapacidad intelectual</p>
<p><strong>Contacto:</strong> C/ Querol, 10, 52006 Melilla</p>
<p><a href="reinasofia@melilla.gob">Página web</a></p>
</div>
<!-- Recurso 14 -->
<div class="resource" data-type="Orientación e inserción sociolaboral">
<h3>Fundación Cepaim – Servicio de Orientación Laboral para inmigrantes</h3>
<p><strong>Colectivos:</strong> Personas inmigrantes y refugiadas</p>
<p><strong>Contacto:</strong> C/ General Polavieja, 3, 52001 Melilla</p>
<p>Ofrecen orientación laboral y apoyo para la integración sociolaboral de personas inmigrantes. Los servicios incluyen talleres de empleabilidad, asesoramiento personalizado y acompañamiento en la búsqueda de empleo.</p>
</div>

<!-- Recurso 15 -->
<div class="resource" data-type="Programas de inserción sociolaboral">
<h3>Cámara de Comercio de Melilla – Plan de Apoyo al Comercio Local</h3>
<p><strong>Colectivos:</strong> Emprendedores y pequeñas empresas</p>
<p><strong>Contacto:</strong> Plaza de España, 1, 52001 Melilla</p>
<p>Ofrecen asesoramiento y formación para emprendedores, ayudando a desarrollar ideas de negocio y facilitando la creación de nuevas empresas en Melilla. Incluye formación en gestión empresarial y acceso a financiación.</p>
</div>

<!-- Recurso 16 -->
<div class="resource" data-type="Programas de inserción sociolaboral">
<h3>Servicio Público de Empleo Estatal (SEPE) Melilla</h3>
<p><strong>Colectivos:</strong> Personas desempleadas</p>
<p><strong>Contacto:</strong> C/ Alfonso XIII, 14, 52001 Melilla. Teléfono: 952 68 56 00</p>
<p>Oficina de empleo que ofrece servicios de orientación, intermediación laboral y acceso a prestaciones por desempleo. También facilita cursos de formación profesional para mejorar la empleabilidad.</p>
</div>

<!-- Recurso 17 -->
<div class="resource" data-type="Empleo y Formación">
<h3>Centro de Educación de Personas Adultas (CEPA) Enrique Soler</h3>
<p><strong>Colectivos:</strong> Adultos, personas sin titulación</p>
<p><strong>Contacto:</strong> C/ Valencia, 3, 52005 Melilla</p>
<p>Ofrecen cursos de alfabetización, educación secundaria y formación profesional básica para adultos. Además, imparten formación específica para mejorar la empleabilidad.</p>
</div>

<!-- Recurso 18 -->
<div class="resource" data-type="Inserción sociolaboral y formación">
<h3>Oficina de Atención al Inmigrante (OPEI)</h3>
<p><strong>Colectivos:</strong> Inmigrantes, solicitantes de asilo</p>
<p><strong>Contacto:</strong> Plaza de España, s/n, 52001 Melilla</p>
<p>Servicio que ofrece asesoramiento legal y orientación laboral para inmigrantes en Melilla. Ayuda a los usuarios a regularizar su situación y encontrar empleo mediante programas de apoyo y formación.</p>
</div>

<!-- Recurso 19 -->
<div class="resource" data-type="Programas de inserción sociolaboral">
<h3>Talleres de Empleo Melilla</h3>
<p><strong>Colectivos:</strong> Desempleados de larga duración, jóvenes</p>
<p><strong>Contacto:</strong> Avda. Duquesa de la Victoria, 52006 Melilla</p>
<p>Programas de formación dual que combinan teoría y trabajo práctico. Suelen centrarse en áreas como jardinería, construcción y atención a la comunidad.</p>
</div>

<!-- Recurso 20 -->
<div class="resource" data-type="Empleo y Formación">
<h3>Centro Especial de Empleo (CEE) Melilla Integra</h3>
<p><strong>Colectivos:</strong> Personas con discapacidad física e intelectual</p>
<p><strong>Contacto:</strong> C/ Luis de Sotomayor, 52006 Melilla. Teléfono: 952 69 48 33</p>
<p>Empresa social que proporciona empleo a personas con discapacidad. Ofrecen un entorno adaptado y oportunidades laborales estables, ayudando a los empleados a desarrollar habilidades en áreas como limpieza y mantenimiento.</p>
</div>

<!-- Recurso 21 -->
<div class="resource" data-type="Inserción sociolaboral y formación">
<h3>Programa de Garantía Juvenil</h3>
<p><strong>Colectivos:</strong> Jóvenes desempleados menores de 30 años</p>
<p><strong>Contacto:</strong> C/ Pablo Vallescá, 12, 52001 Melilla</p>
<p>Iniciativa europea destinada a reducir el desempleo juvenil. Ofrecen formación, prácticas laborales y ayudas para el autoempleo a jóvenes menores de 30 años que no estudian ni trabajan.</p>
</div>

<!-- Recurso 22 -->
<div class="resource" data-type="Inserción sociolaboral y formación">
<h3>Asociación Mujeres Progresistas de Melilla – Programa de Inserción Laboral</h3>
<p><strong>Colectivos:</strong> Mujeres en riesgo de exclusión social</p>
<p><strong>Contacto:</strong> C/ La Legión, 3, 52006 Melilla</p>
<p>Programa de formación y orientación laboral dirigido a mujeres en situación de vulnerabilidad. Ofrecen cursos de capacitación, talleres de habilidades laborales y asesoría para la búsqueda de empleo.</p>
</div>

<!-- Recurso 23 -->
<div class="resource" data-type="Inserción sociolaboral y formación">
<h3>Programa de Inclusión Social “Melilla Integra”</h3>
<p><strong>Colectivos:</strong> Personas en riesgo de exclusión social</p>
<p><strong>Contacto:</strong> C/ Polígono Industrial Sepes, 52006 Melilla</p>
<p>Proyecto destinado a apoyar a personas en situación de vulnerabilidad social para que puedan acceder al empleo. Ofrecen itinerarios personalizados que incluyen formación, asesoramiento laboral y apoyo psicológico.</p>
</div>
<!-- Recurso 24 -->
<div class="resource" data-type="Formación profesional para el empleo">
<h3>Centro de Formación para el Empleo (CFE)</h3>
<p><strong>Colectivos:</strong> Desempleados, jóvenes, adultos en búsqueda de mejora profesional</p>
<p><strong>Contacto:</strong> Avda. Juan Carlos I Rey, s/n, 52001 Melilla</p>
<p>Ofrecen cursos de formación profesional en diversas áreas, como hostelería, administración y nuevas tecnologías. El objetivo es mejorar la empleabilidad de los participantes mediante la adquisición de competencias específicas.</p>
</div>

<!-- Recurso 25 -->
<div class="resource" data-type="Inserción sociolaboral y formación">
<h3>Fundación Secretariado Gitano – Programa Acceder</h3>
<p><strong>Colectivos:</strong> Comunidad gitana</p>
<p><strong>Contacto:</strong> C/ García Cabrelles, 12, 52001 Melilla</p>
<p>El programa “Acceder” se enfoca en mejorar la empleabilidad de la comunidad gitana a través de la formación y el acceso a oportunidades laborales. Ofrecen talleres de capacitación, asesoramiento individualizado y seguimiento durante el proceso de búsqueda de empleo.</p>
</div>

<!-- Recurso 26 -->
<div class="resource" data-type="Asesoramiento para el autoempleo">
<h3>Centro de Innovación y Desarrollo Empresarial (CIDE Melilla)</h3>
<p><strong>Colectivos:</strong> Emprendedores y pequeñas empresas</p>
<p><strong>Contacto:</strong> C/ Marqués de Montemar, 3, 52002 Melilla</p>
<p>Proporcionan apoyo a emprendedores y empresarios locales para el desarrollo de sus negocios. Ofrecen servicios de consultoría, asesoramiento en innovación y ayuda en la búsqueda de financiación.</p>
</div>

<!-- Recurso 27 -->
<div class="resource" data-type="Empleo y Formación">
<h3>Escuela de Hostelería Melilla</h3>
<p><strong>Colectivos:</strong> Jóvenes y adultos interesados en el sector de la hostelería</p>
<p><strong>Contacto:</strong> C/ Ejército Español, 10, 52001 Melilla</p>
<p>Ofrecen programas formativos en hostelería y turismo, incluyendo cursos de cocina, servicio de sala y gestión hotelera. Los alumnos reciben una formación práctica en colaboración con establecimientos locales.</p>
</div>

<!-- Recurso 28 -->
<div class="resource" data-type="Orientación e inserción sociolaboral">
<h3>Centro de Iniciativas Empresariales (CIE)</h3>
<p><strong>Colectivos:</strong> Emprendedores y pequeñas empresas locales</p>
<p><strong>Contacto:</strong> C/ General Astilleros, 1, 52002 Melilla</p>
<p>Ayudan a los nuevos emprendedores a poner en marcha sus proyectos, ofreciendo orientación personalizada, formación específica y acceso a recursos para la creación y gestión empresarial.</p>
</div>
<!-- Recurso 29 -->
<div class="resource" data-type="Inserción sociolaboral y formación">
<h3>Asociación Síndrome de Down Melilla – Programa de Formación e Inserción</h3>
<p><strong>Colectivos:</strong> Personas con síndrome de Down</p>
<p><strong>Contacto:</strong> C/ San Roque, 12, 52001 Melilla</p>
<p>Descripción: Ofrecen programas de formación y empleo adaptados para personas con síndrome de Down, facilitando su inclusión en el mercado laboral. Incluyen formación en habilidades laborales y prácticas en empresas colaboradoras.</p>
</div>

<!-- Recurso 30 -->
<div class="resource" data-type="Programas de inserción sociolaboral">
<h3>Centro de Atención al Recluso – Programa de Reinserción Sociolaboral</h3>
<p><strong>Colectivos:</strong> Personas que han cumplido condenas en prisión</p>
<p><strong>Contacto:</strong> C/ Real, 5, 52002 Melilla</p>
<p>Descripción: Proporcionan apoyo a personas que han estado privadas de libertad para facilitar su reinserción en la sociedad. Incluyen formación profesional, orientación laboral y asesoramiento psicológico para ayudar a los participantes a encontrar empleo.</p>
</div>


    </section>
     <!-- Sección de Imágenes -->
     <section id="imagenes-lugares" class="imagenes-lugares">
     <h2>ubicación</h2>
     <div class="images-container">
         <div class="image-item">
 
        <p>Melilla Orienta  <p><a href=" https://www.google.es/maps/@35.2709577,-2.944436,3a,75y,68.98h,93.32t/data=!3m7!1e1!3m5!1sn1PRc6Y_j5Zi_UG1muALNA!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-3.323441995136861%26panoid%3Dn1PRc6Y_j5Zi_UG1muALNA%26yaw%3D68.98481060960296!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p </p>
    </div>
    <div class="image-item">
        <p>Centro de Melilla de la Red COE</p><p><a href="https://www.google.es/maps/@35.2936774,-2.9383034,3a,75y,32.88h,90.46t/data=!3m7!1e1!3m5!1s5AoP5nRZosaOIN8SyAXPaw!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-0.4600441524897718%26panoid%3D5AoP5nRZosaOIN8SyAXPaw%26yaw%3D32.880881624396295!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Fundación Diagrama – Programa TALEM</p><p><a href="https://www.google.es/maps/@35.2935178,-2.9399717,3a,75y,103.7h,75.83t/data=!3m7!1e1!3m5!1swS2gtUYduW_uG8iSxbNNwQ!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D14.169586576032188%26panoid%3DwS2gtUYduW_uG8iSxbNNwQ%26yaw%3D103.70168082131997!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Proyecto Melilla (PROMESA)</p><p><a href="https://www.google.es/maps/place/Proyecto+Melilla+S+A/@35.2710393,-2.9444855,3a,75y,85.76h,90t/data=!3m7!1e1!3m5!1st5WvmplLLfd6484zA4UpGg!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3Dt5WvmplLLfd6484zA4UpGg%26yaw%3D85.755248989601!7i16384!8i8192!4m14!1m7!3m6!1s0xd7705ef11302803:0x3be376030f66f28e!2sProyecto+Melilla+S+A!8m2!3d35.2711118!4d-2.9443444!16s%2Fg%2F1q5bmqqhg!3m5!1s0xd7705ef11302803:0x3be376030f66f28e!8m2!3d35.2711118!4d-2.9443444!16s%2Fg%2F1q5bmqqhg?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Cruz Roja Melilla – Programa de Empleo</p><p><a href="https://www.google.es/maps/@35.2895491,-2.9441062,3a,75y,276.56h,117.66t/data=!3m7!1e1!3m5!1sWSHrp9rla10bUZhEl5ikeg!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-27.656823001400085%26panoid%3DWSHrp9rla10bUZhEl5ikeg%26yaw%3D276.5636497883423!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro de Formación Profesional para el Empleo</p><p><a href="https://www.google.es/maps/@35.2940531,-2.9434372,3a,75y,298.24h,90t/data=!3m7!1e1!3m5!1sw6N1nXmrM0tZvdsPB-lBOA!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3Dw6N1nXmrM0tZvdsPB-lBOA%26yaw%3D298.24265!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentrao</a></p>
    </div>
    <div class="image-item">
        <p>Asociación de Empresarios de Melilla (AEM)</p><p><a href="https://www.google.es/maps/@35.2928069,-2.9388623,3a,75y,28.84h,90t/data=!3m7!1e1!3m5!1sC3s2BnnUykdo52kjN0J4Og!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3DC3s2BnnUykdo52kjN0J4Og%26yaw%3D28.836979!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Plan de Empleo de Melilla - SEPE</p><p><a href="https://www.google.es/maps/place/S.E.P.E.+Servicio+P%C3%BAblico+de+Empleo+Estatal/@35.2738344,-2.9476248,3a,75y,247.57h,75.86t/data=!3m7!1e1!3m5!1sqRDVb3ahZ5QBcqXFhASVzw!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D14.139700678023388%26panoid%3DqRDVb3ahZ5QBcqXFhASVzw%26yaw%3D247.56784469629386!7i16384!8i8192!4m9!3m8!1s0xd7705e4ca803c3f:0xfd16532e9802f0e6!8m2!3d35.2738151!4d-2.9477166!10e5!14m1!1BCgIgARICCAI!16s%2Fg%2F119v0dcy2?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentrao</a></p>
    </div>
    <div class="image-item">
        <p>Asociación AMPA Down Melilla – Servicio Prelaboral</p><p><a href="https://www.google.es/maps/@35.2903818,-2.9407044,3a,75y,327.64h,81.52t/data=!3m7!1e1!3m5!1s1YOuJJdFceHx2XqtY79Iyw!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D8.483489985580121%26panoid%3D1YOuJJdFceHx2XqtY79Iyw%26yaw%3D327.63695040364576!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Enclave laboral de la Asociación de Personas con Discapacidad (ADIMEL)</p><p><a href="https://www.google.es/maps/place/C.+Pablo+Vallesc%C3%A1,+12,+52001+Melilla,+NULL/@35.293722,-2.9408037,17z/data=!3m1!4b1!4m6!3m5!1s0xd77058a11e01391:0x832029e5f7241eb0!8m2!3d35.2937176!4d-2.9382288!16s%2Fg%2F11cscv98f2?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">CDonde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Escuela Taller “Melilla Joven”</p><p><a href="https://www.google.es/maps/place/Escuela+Taller/@35.2997741,-2.9446769,3a,75y,90t/data=!3m8!1e2!3m6!1sAF1QipOrwmoVJIMICnYol7sOx2b6rsxtu2mIUv4UvwGt!2e10!3e12!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipOrwmoVJIMICnYol7sOx2b6rsxtu2mIUv4UvwGt%3Dw114-h86-k-no!7i3264!8i2448!4m7!3m6!1s0xd77058f6e404021:0x955daa9e946cd64e!8m2!3d35.2997741!4d-2.9446769!10e5!16s%2Fg%2F12qg1438j?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Agencia de Colocación Melilla Activa</p><p><a href="https://www.google.es/maps/@35.2937359,-2.9383939,3a,75y,117.53h,68.68t/data=!3m7!1e1!3m5!1sNUpY-fcC18cWrTB_RDos0w!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D21.32190321713425%26panoid%3DNUpY-fcC18cWrTB_RDos0w%26yaw%3D117.53387449808943!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro Ocupacional Reina Sofía</p><p><a href="https://www.google.es/maps/@39.4668861,-3.6260281,3a,75y,220.54h,90t/data=!3m7!1e1!3m5!1sT7DYmAUDcGibGy9yn4yOLA!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3DT7DYmAUDcGibGy9yn4yOLA%26yaw%3D220.54286!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Fundación Cepaim – Servicio de Orientación Laboral para inmigrantes</p><p><a href="https://www.google.es/maps/@35.2861966,-2.9421387,3a,75y,122.7h,90t/data=!3m7!1e1!3m5!1sORb83Tn9q-z4dO_w7HQ5rg!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3DORb83Tn9q-z4dO_w7HQ5rg%26yaw%3D122.697495!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Cámara de Comercio de Melilla – Plan de Apoyo al Comercio Local</p><p><a href="https://www.google.es/maps/@35.2922081,-2.9372587,3a,75y,83.75h,90t/data=!3m7!1e1!3m5!1so5vKCBWVsQmiChvksJvh7A!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3Do5vKCBWVsQmiChvksJvh7A%26yaw%3D83.74608!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Servicio Público de Empleo Estatal (SEPE) Melilla</p><p><a href="https://www.google.es/maps/place/S.E.P.E.+Servicio+P%C3%BAblico+de+Empleo+Estatal/@35.2738344,-2.9476248,3a,75y,90t/data=!3m7!1e1!3m5!1sqRDVb3ahZ5QBcqXFhASVzw!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3DqRDVb3ahZ5QBcqXFhASVzw%26yaw%3D0!7i16384!8i8192!4m9!3m8!1s0xd7705e4ca803c3f:0xfd16532e9802f0e6!8m2!3d35.2738151!4d-2.9477166!10e5!14m1!1BCgIgARICCAI!16s%2Fg%2F119v0dcy2?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro de Educación de Personas Adultas (CEPA) Enrique Soler</p><p><a href="https://www.google.es/maps/place/COMAMEL/@35.2783975,-2.9481628,3a,75y,331.09h,90t/data=!3m7!1e1!3m5!1smHY2vU4gkNA-AJqR3OEkkw!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3DmHY2vU4gkNA-AJqR3OEkkw%26yaw%3D331.0858!7i16384!8i8192!4m11!1m2!2m1!1senrique+soler+melilla+cepa!3m7!1s0xd7705bdf3bd7c23:0x5298f57f9e5f4d0b!8m2!3d35.2787242!4d-2.948386!10e5!15sChplbnJpcXVlIHNvbGVyIG1lbGlsbGEgY2VwYZIBF2VkdWNhdGlvbmFsX2luc3RpdHV0aW9u4AEA!16s%2Fg%2F11sfx2kyrx?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Oficina de Atención al Inmigrante (OPEI)</p><p><a href="https://www.google.es/maps/@35.2906303,-2.9366344,3a,75y,96.02h,82.31t/data=!3m7!1e1!3m5!1skkPGmR65W8EGlNEDbNVLtQ!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D7.685243220365777%26panoid%3DkkPGmR65W8EGlNEDbNVLtQ%26yaw%3D96.01836844049775!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Talleres de Empleo Melilla</p><p><a href="https://www.google.es/maps/place/Inserta+Empleo+Melilla/@35.2931647,-2.9420136,3a,75y,10.54h,63.45t/data=!3m7!1e1!3m5!1s1BK22Yn29hIlHb5W7sWoDw!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D26.553758457887568%26panoid%3D1BK22Yn29hIlHb5W7sWoDw%26yaw%3D10.541185268784687!7i16384!8i8192!4m13!1m2!2m1!1sTalleres+de+Empleo+Melilla!3m9!1s0xd7705d0d0b127b9:0x5c588353599d63f1!8m2!3d35.2932259!4d-2.9415355!10e5!14m1!1BCgIgARICCAI!15sChpUYWxsZXJlcyBkZSBFbXBsZW8gTWVsaWxsYVocIhp0YWxsZXJlcyBkZSBlbXBsZW8gbWVsaWxsYZIBEWVtcGxveW1lbnRfYWdlbmN54AEA!16s%2Fg%2F11s_shg67d?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro Especial de Empleo (CEE) Melilla Integra</p><p><a href="https://www.google.es/maps/@35.2889851,-2.9400685,3a,75y,82.4h,90t/data=!3m7!1e1!3m5!1sCqb1VseOvFsZczpwDkKAkA!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3DCqb1VseOvFsZczpwDkKAkA%26yaw%3D82.40248!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Programa de Garantía Juvenil</p><p><a href="https://www.google.es/maps/place/C.+Pablo+Vallesc%C3%A1,+12,+52001+Melilla,+NULL/@35.293722,-2.9408037,17z/data=!3m1!4b1!4m6!3m5!1s0xd77058a11e01391:0x832029e5f7241eb0!8m2!3d35.2937176!4d-2.9382288!16s%2Fg%2F11cscv98f2?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Asociación Mujeres Progresistas de Melilla – Programa de Inserción Laboral</p><p><a href="https://www.google.es/maps/place/C.+la+Legi%C3%B3n,+3,+52006+Melilla,+NULL/@35.2770677,-2.9417731,17z/data=!3m1!4b1!4m6!3m5!1s0xd7705f8395c62e1:0x3bca25bc9ae7ea92!8m2!3d35.2770633!4d-2.9391982!16s%2Fg%2F11c2621d9l?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Programa de Inclusión Social “Melilla Integra”</p><p><a href="https://www.google.es/maps/@35.2721594,-2.9422301,3a,75y,136.58h,85.58t/data=!3m7!1e1!3m5!1sBuUqE_fFvqPmbpG0NaQe3g!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D4.4163815856912265%26panoid%3DBuUqE_fFvqPmbpG0NaQe3g%26yaw%3D136.57986593248222!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro de Formación para el Empleo (CFE)</p><p><a href="https://www.google.es/maps/place/Av.+Juan+Carlos+I,+Rey,+52001+Melilla/@35.2937936,-2.9403411,3a,75y,90t/data=!3m8!1e2!3m6!1sAF1QipMTGjWGgT9AZhkQMqTvgWCIaaxHiaxZOTPOW4aS!2e10!3e12!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipMTGjWGgT9AZhkQMqTvgWCIaaxHiaxZOTPOW4aS%3Dw86-h114-k-no!7i3472!8i4624!4m7!3m6!1s0xd77058bcdc9ea93:0x96569d76517e763c!8m2!3d35.2937796!4d-2.9403429!10e5!16s%2Fg%2F11f08hdjzs?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Fundación Secretariado Gitano – Programa Acceder</p><p><a href="https://www.google.es/maps/place/C.+Garc%C3%ADa+Cabrelles,+12,+52002+Melilla,+NULL/@35.2952944,-2.9459959,17z/data=!3m1!4b1!4m6!3m5!1s0xd77058ebb1c1b53:0x627a328b32aea7e7!8m2!3d35.29529!4d-2.943421!16s%2Fg%2F11csjkx1sl?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro de Innovación y Desarrollo Empresarial (CIDE Melilla)</p><p><a href="https://www.google.es/maps/place/Direcci%C3%B3n+Provincial+de+Educaci%C3%B3n+y+Ciencia+de+Melilla/@35.2936069,-2.9388642,3a,75y,337.77h,90.72t/data=!3m7!1e1!3m5!1scz-o_-DEMePT9k4WodHIWw!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-0.7232217005922621%26panoid%3Dcz-o_-DEMePT9k4WodHIWw%26yaw%3D337.7673907572794!7i16384!8i8192!4m13!1m2!2m1!1scide+melilla!3m9!1s0xd77058a15fd3d81:0xb2c10ca8de6b8c10!8m2!3d35.2935324!4d-2.9387329!10e5!14m1!1BCgIgARICCAI!15sCgxjaWRlIG1lbGlsbGGSARpkaXN0cmljdF9nb3Zlcm5tZW50X29mZmljZeABAA!16s%2Fg%2F12qg_4scw?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Escuela de Hostelería Melilla</p><p><a href="https://www.google.es/maps/@35.293631,-2.9344269,3a,75y,343.83h,96t/data=!3m7!1e1!3m5!1swx2UUgZUpDBrx8VYJbH1MA!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D-6.004428720737721%26panoid%3Dwx2UUgZUpDBrx8VYJbH1MA%26yaw%3D343.8254835029242!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro de Iniciativas Empresariales (CIE)</p><p><a href="https://www.google.es/maps/@35.2855882,-2.9403909,3a,75y,49.87h,90t/data=!3m7!1e1!3m5!1sf9aZOUCncIT_Jjb-is9bBg!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3Df9aZOUCncIT_Jjb-is9bBg%26yaw%3D49.865566!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Asociación Síndrome de Down Melilla – Programa de Formación e Inserción</p><p><a href="https://www.google.es/maps/@35.2762754,-2.9488784,3a,75y,276.74h,88.77t/data=!3m7!1e1!3m5!1sl9VWrTx9isFKUGc-QFDeDA!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D1.2273250696115383%26panoid%3Dl9VWrTx9isFKUGc-QFDeDA%26yaw%3D276.7426158499458!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
    <div class="image-item">
        <p>Centro de Atención al Recluso – Programa de Reinserción Sociolaboral</p><p><a href="https://www.google.es/maps/@35.3004287,-2.9443127,3a,75y,96.85h,90t/data=!3m7!1e1!3m5!1s0Ihz7YyTOP8j7zlXEo_gEQ!2e0!6shttps:%2F%2Fstreetviewpixels-pa.googleapis.com%2Fv1%2Fthumbnail%3Fcb_client%3Dmaps_sv.tactile%26w%3D900%26h%3D600%26pitch%3D0%26panoid%3D0Ihz7YyTOP8j7zlXEo_gEQ%26yaw%3D96.85392!7i16384!8i8192?hl=es&entry=ttu&g_ep=EgoyMDI0MTExOS4yIKXMDSoASAFQAw%3D%3D">Donde se encuentra</a></p>
    </div>
</div>
</section>


    

    <!-- Pie de página -->
    <footer id="contacto">
        <p>© 2024 Catálogo de Recursos Melilla | Todos los derechos reservados</p>
    </footer>

    <script>
        function filterResources(type) {
            const resources = document.querySelectorAll('.resource');
            resources.forEach(resource => {
                resource.style.display = type === '' || resource.dataset.type === type ? 'block' : 'none';
            });
        }

        function searchResources() {
            const query = document.getElementById('search').value.toLowerCase();
            const resources = document.querySelectorAll('.resource');
            resources.forEach(resource => {
                const text = resource.textContent.toLowerCase();
                resource.style.display = text.includes(query) ? 'block' : 'none';
            });
        }
        function filterResources(type) {
    const resources = document.querySelectorAll('.resource');
    resources.forEach(resource => {
        resource.style.display = type === '' || resource.dataset.type === type ? 'block' : 'none';
    });
}

function searchResources() {
    const query = document.getElementById('search').value.toLowerCase();
    const resources = document.querySelectorAll('.resource');
    resources.forEach(resource => {
        const text = resource.textContent.toLowerCase();
        resource.style.display = text.includes(query) ? 'block' : 'none';
    });
}

    </script>
</body>
</html>

