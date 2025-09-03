# Temario-de-Aplicaciones-Web-
Actividad 2  
# <ing>Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.</ing>
<img width="655" height="485" alt="Captura de pantalla 2025-09-02 224820" src="https://github.com/user-attachments/assets/f09c91df-1eec-4336-ad88-27dce6c6c3ed" />

# <ing>1.-Introducción al desarrollo web</ing>    
# <ing>Historia y evolución del desarrollo web</ing>    
La historia y evolución del desarrollo web ha estado marcada por una constante innovación     
tecnológica que ha transformado la manera en que interactuamos con la información y los     
servicios digitales. Desde la creación de la World Wide Web a principios de los años     
noventa por Tim Berners-Lee, el desarrollo web ha pasado de simples páginas estáticas     
basadas en HTML a complejas aplicaciones dinámicas que emplean tecnologías avanzadas como     
JavaScript, CSS y diversos frameworks y bibliotecas. A lo largo de las décadas, la web ha     
evolucionado para ofrecer experiencias más interactivas, accesibles y seguras, impulsando     
la conectividad global y permitiendo el surgimiento de nuevas formas de comunicación,     
comercio y aprendizaje.    

# <ing> Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)    </ing>
<img width="407" height="216" alt="Captura de pantalla 2025-09-02 225140" src="https://github.com/user-attachments/assets/911fe3c5-3749-414a-888a-86f5fa00a74c" />

# <ing> 1. Aplicaciones Web Estáticas  </ing>

# <ing> definicion </ing>
Una aplicación web estática es aquella cuyo contenido se muestra tal cual está almacenado en  
el servidor. No hay interacción con bases de datos ni cambios en el contenido según el usuario o la sesión.  
#Características:
El contenido no cambia salvo que se modifique manualmente el archivo en el servidor.  
Son páginas rápidas de cargar ya que se sirven directamente desde el servidor al navegador.  
No requieren programación de backend.  
Solo usan tecnologías como HTML, CSS y JavaScript básico.  
# <ing> Ventajas:  </ing>
Fácil de desarrollar y mantener.  
Menor coste de hosting.  
Alta velocidad de carga.  
Seguridad elevada, ya que no hay bases de datos ni lógica de servidor expuesta.  
# <ing> Desventajas:  </ing>  
Poco flexibles para cambios frecuentes o interacción con el usuario.  
No permiten personalización del contenido.  
No aptas para sitios con funcionalidades avanzadas.  
# <ing> Ejemplos:  </ing>  
Portafolios personales.  
Sitios institucionales simples.  
Documentación estática.  
# <ing> 2. Aplicaciones Web Dinámicas  </ing>
#<ing>Definición:  </ing>
En una aplicación web dinámica, el contenido puede cambiar en función de la interacción  
del usuario, datos almacenados o procesados en el servidor.  
# <ing> Características: </ing> 
Utilizan un lenguaje de backend (PHP, Python, Node.js, Ruby, etc.) y bases de datos  
(MySQL, MongoDB, etc.).  
El servidor procesa las peticiones y genera contenido personalizado.  
Pueden incluir formularios, cuentas de usuario, carritos de compra, foros, etc.  
# <ing>Ventajas:</ing>  
Permiten interacción avanzada y personalización.  
Adecuadas para sitios que requieren actualización frecuente o gestión de información.  
Pueden conectarse con servicios externos (APIs, pasarelas de pago, etc.).  
# <ing>Desventajas:  </ing>
Más complejas de desarrollar y mantener.  
Pueden tener tiempos de carga mayores si no se optimizan.  
Mayor exposición a vulnerabilidades de seguridad.  
# <ing>Ejemplos:  </ing>
Tiendas en línea (e-commerce).  
Redes sociales.  
Foros y blogs con comentarios de usuarios.  
# <ing>3. SPA (Single Page Application)  </ing>
# <ing>Definición: </ing> 
Una SPA es una aplicación web que carga una única página HTML y utiliza JavaScript  
para actualizar dinámicamente el contenido, sin recargar toda la página.  
# <ing>Características:  </ing>
Navegación interna sin recarga completa de la página.  
Utiliza frameworks modernos como React, Angular, Vue.js, Svelte, etc.  
Maneja rutas y estados del lado del cliente (navegador).  
Consume APIs para obtener o enviar datos.  
# <ing>Ventajas:  </ing>
Experiencia de usuario fluida y rápida.  
Sensación de estar usando una aplicación de escritorio o móvil.  
Menor consumo de ancho de banda tras la carga inicial.  
# <ing>Desventajas:  </ing>
SEO más complejo porque el contenido se genera en el navegador.  
Primer carga puede ser más lenta.  
Puede dificultar el historial de navegación y la compartición de enlaces si no se gestiona bien.  
# <ing>Ejemplos:  </ing>
Gmail.  
Trello.  
Facebook Web.  
Google Maps.  
# <ing>2.Arquitectura de aplicaciones web  </ing>
# <ing>Cliente-Servidor  </ing>
# <ing>Definición:</ing>
Es la base de la mayoría de las aplicaciones web. Divide el sistema en dos partes 
principales: el cliente (navegador web del usuario) y el servidor (donde residen la
lógica de la aplicación y los datos).
# <ing>Cliente: </ing>
Solicita recursos o servicios al servidor. Generalmente, es el navegador del usuario,
que muestra la interfaz gráfica.
# <ing>Servidor: </ing>  
Procesa las solicitudes del cliente, ejecuta la lógica, accede a bases de datos y
devuelve respuestas.
# <ing>Ventajas:</ing>
Separación clara de responsabilidades.
Facilidad para escalar ambos componentes por separado.
# <ing>Arquitectura de tres capas (presentación, lógica, datos)  </ing>
Esta arquitectura divide la aplicación en tres capas independientes:

# <ing>Capa de Presentación (Front-end):</ing>
Es la interfaz que ve el usuario (HTML, CSS, JavaScript).
Se encarga de mostrar la información y recoger los datos del usuario.
# <ing>Capa de Lógica (Back-end o lógica de negocio):</ing>
Procesa la información recibida del usuario.
Contiene las reglas y procesos del sistema.
Suele estar implementada en el servidor (Node.js, Java, Python, etc.).
# <ing>Capa de Datos:</ing>
Gestiona el almacenamiento y recuperación de información.
Normalmente una base de datos (MySQL, PostgreSQL, MongoDB, etc.).
# <ing>Ventajas:</ing>
Facilita el mantenimiento y escalabilidad.
Permite distribuir el desarrollo entre distintos equipos.
Mejora la reutilización y la seguridad
# <ing>REST y API-first design  </ing>
# <ing>REST (Representational State Transfer)</ing>
# <ing>Definición:</ing>
Es un estilo de arquitectura para diseñar servicios web ligeros y escalables.
# <ing>Principios:</ing>
Usa HTTP como protocolo de comunicación.
Opera con recursos (datos), identificados por URLs.
Utiliza métodos HTTP estándar: GET, POST, PUT, DELETE.
Es stateless: cada petición es independiente.
# <ing>Ventajas:</ing>
Simple, flexible y ampliamente adoptado.
Facilita la integración entre sistemas heterogéneos.
# <ing>API-first Design</ing>
# <ing>Definición:</ing>
Estrategia de desarrollo donde la API se diseña y documenta antes de implementar la lógica interna de la aplicación.
# <ing>Ventajas:</ing>
Permite que distintos equipos (frontend, backend, móviles) trabajen en paralelo usando definiciones claras (Swagger/OpenAPI).
Mejora la calidad, coherencia y mantenibilidad de la API.
Facilita la escalabilidad y la integración futura con otros sistemas.


# <ing>3. -Lenguajes y tecnologías fundamentales</ing>  
HTML, CSS, JavaScript, PHP, MySQL
<img width="705" height="285" alt="Captura de pantalla 2025-09-02 225245" src="https://github.com/user-attachments/assets/216a57ee-60d2-4006-8524-3599b44c5a2e" />

# <ing>HTML (HyperText Markup Language)</ing>
# <ing>Función: </ing>
Es el lenguaje principal para estructurar el contenido de las páginas web.
# <ing>Características: </ing>
Define elementos como encabezados, párrafos, enlaces, imágenes, tablas, formularios, etc.
# <ing>Importancia:</ing>
Toda página web necesita HTML; es la base sobre la que se construyen los sitios.
# <ing>CSS (Cascading Style Sheets)</ing>
# <ing>Función:</ing> 
Se utiliza para dar estilo y diseño a las páginas web creadas con HTML.
# <ing>aracterísticas:</ing>
Permite definir colores, fuentes, márgenes, posiciones, diseños responsivos, animaciones, etc.
# <ing>Importancia:<ing>
Hace que las páginas sean visualmente atractivas y adaptables a diferentes dispositivos.
# <ing>JavaScript</ing>
# <ing>Función: <ing>
Es el lenguaje de programación que permite añadir interactividad y dinamismo a las páginas web.
# <ing>Características:</ing>
Permite validar formularios, actualizar contenido sin recargar la página, crear animaciones, manejar eventos y mucho más.
# <ing>Importancia: </ing>
Es fundamental para el desarrollo de aplicaciones web modernas e interactivas (como SPAs).
# <ing>PHP</ing>
#      <ing>Función: </ing>
Lenguaje de programación del lado del servidor, usado para crear páginas web dinámicas.
# <ing>Características:</ing>
Permite procesar formularios, gestionar sesiones, interactuar con bases de datos, generar contenido personalizado.
# <ing>Importancia:</ing>
Muy utilizado en sistemas de gestión de contenido como WordPress, Joomla, etc.
# <ing>MySQL</ing>
# <ing>Función:</ing>
Sistema de gestión de bases de datos relacional.
# <ing>Características:</ing>
Permite almacenar, consultar y gestionar grandes volúmenes de datos estructurados.
# <ing>Importancia:</ing>
Es uno de los motores de bases de datos más populares y se integra fácilmente con PHP para crear aplicaciones web dinámicas.
# <ing>4. Control de versiones </ing>
<img width="583" height="408" alt="Captura de pantalla 2025-09-02 225430" src="https://github.com/user-attachments/assets/cda60efc-b347-4b3c-bb52-b3ee1b4a71aa" />

# <ing>Git y GitHub</ing>
# <ing>Git:</ing> 
Sistema de control de versiones distribuido, permite rastrear cambios en el código, colaborar y mantener historial.
# <ing>GitHub: </ing>
Plataforma basada en Git para alojar repositorios, colaborar, gestionar proyectos y facilitar el trabajo en equipo.
Flujo de trabajo con ramas
# <ing>Branching:</ing>
Crear ramas para desarrollar nuevas características o corregir errores sin afectar la rama principal (main/master).
# <ing>Merge: </ing>
Unir los cambios de una rama a otra (por ejemplo, integrar una feature en main).
# <ing>Pull Requests: </ing>
Solicitar la revisión e integración de cambios; facilita la colaboración y el control de calidad.

# <ing>Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web </ing>
# <ing>1. Diseño e implementación del frontend</ing>
# <ing>Maquetación/Wireframe/Mockup: </ing>
# <ing>Wireframe:</ing>
Esquema visual básico de la interfaz.
# <ing>Mockup:</ing>
Representación visual más detallada y realista.
# <ing>Maquetación: </ing>
Implementación del diseño usando HTML/CSS y frameworks.
# <ing>API: </ing>
Integración del frontend con servicios externos o el backend para obtener o enviar datos.

# <ing>2. Diseño e implementación del backend</ing>
# <ing>Servidor:</ing>
Programa que recibe y procesa peticiones desde el frontend o clientes externos.
# <ing>Manejo de peticiones y respuestas HTTP:</ing>
# <ing>Request:</ing>
Solicitud enviada por el cliente al servidor.
# <ing>Response:</ing>
Respuesta del servidor al cliente.
Conexión a bases de datos:
# <ing>MySQL, PostgreSQL, MongoDB:</ing>
Sistemas de bases de datos relacionales (MySQL, PostgreSQL) y NoSQL (MongoDB).

# <ing>4. Bases de datos</ing>
Modelado de datos y relaciones: Diseño de la estructura de datos, tablas y relaciones entre ellas.
# <ing>ORM (Object Relational Mapping):</ing>
 Herramienta que facilita la interacción entre el backend y la base de datos usando objetos del lenguaje de programación.
CRUD desde el backend: Operaciones básicas (Create, Read, Update, Delete) realizadas mediante el backend sobre la base de datos.
# <ing>6. Seguridad básica en aplicaciones web</ing>
# <ing>Validación de formularios:</ing>
 Comprobación de los datos ingresados por el usuario antes de procesarlos.
# <ing>Autenticación y autorización:</ing>
# <ing>Autenticación:</ing>
Verificar la identidad del usuario.
# <ing>Autorización:</ing>
Controlar el acceso a recursos según el usuario y sus permisos.

# <ing>Propósito de Aprendizaje 3:Implementar y desplegar una aplicación web funcional</ing>
# <ing>1. Integración de frontend y backend</ing>
Interfaz de usuario Frontend: Presentación visual e interacción con el usuario.
# <ing>Manejo de API:</ing>
 Comunicación entre frontend y backend mediante API (REST, GraphQL, etc.).
# <ing>Proceso de Solicitud y Respuesta de Backend:</ing>
 Flujo de envío de datos del frontend al backend y retorno de información.
# <ing>3. Almacenamiento en Servidor</ing>
# <ing>Tipos de servidores:</ing>
Físicos, virtuales, cloud, compartidos, dedicados, VPS, etc.
# <ing>Servidores y servicios de hosting:</ing>
Infraestructura que aloja la aplicación web.
# <ing>Proveedores de Servicios de Almacenamiento:</ing>
Ej. Amazon Web Services, Google Cloud, Microsoft Azure, Heroku, DigitalOcean.
# <ing>5. Optimización y rendimiento</ing>
# Optimización de recursos:</ing>
Minimizar y comprimir imágenes, scripts, hojas de estilo, etc.
# <ing>Despliegue de aplicaciones web:</ing>
Proceso de publicar la aplicación para que los usuarios puedan acceder a ella.
# <ing>CI/CD básico:</ing>
Integración y entrega continua para automatizar pruebas y despliegues.
Documentación del proyecto: Registro claro de la arquitectura, uso e instrucciones para desarrolladores y usuarios.
