# Ejercicio 2.

## 1. ¿Qué es un servidor HTTP?

    Es un software que forma parte del servidor y tiene como misión principal devolver información (páginas) cuando recibe peticiones por parte de los usuarios.

## 2. ¿Qué son los verbos HTTP? Mencionar los más conocidos

    Son el método de petición que define HTTP para indicar la acción a realizar para un recurso determinado. Los más populares son: el método GET que solicita la representacion de un recurso específico y el método POST que envia informacion a un recurso, modificándolo y el método DELETE que sirve para borrar informacion de un recurso.

## 3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?

    HTTP se basa en un modelo solicitud / respuesta, de modo que hay dos tipos de mensajes HTTP: la solicitud(Request) y la respuesta(Response). El navegador abre una conexión a un servidor y realiza una solicitud. El servidor procesa la solicitud del cliente y devuelve una respuesta. Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc.

## 4. ¿Qué es un queryString? (En el contexto de una url)

    Las Query String o cadenas de consultas es un término que se utiliza para hacer referencia a una interacción con una base de datos. Además, es la parte de una URL que contiene los datos que deben pasar a las aplicaciones web.

## 5. ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

    Los códigos de estado HTTP son como notas cortas de un servidor que se insertan en una página web. En realidad no son parte del contenido del sitio. En su lugar, son mensajes del servidor que te permiten saber cómo fueron las cosas cuando recibió la solicitud de ver una determinada página. Los posibles valores devueltos son:

        100s: Códigos informativos que indican que la solicitud iniciada por el navegador continúa.
        200s: Los códigos con éxito regresaron cuando la solicitud del navegador fue recibida, entendida y procesada por el servidor.
        300s: Códigos de redireccionamiento devueltos cuando un nuevo recurso ha sido sustituido por el recurso solicitado.
        400s: Códigos de error del cliente que indican que hubo un problema con la solicitud.
        500s: Códigos de error del servidor que indican que la solicitud fue aceptada, pero que un error en el servidor impidió que se cumpliera.

## 6. ¿Cómo se envía la data en un Get y cómo en un POST?

    La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se pulsa el botón “Enviar”. Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).

## 7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?

    Utiliza el verbo GET y nos devuelve un código de estado, indicando si la petición ha sido exitosa, o no, y debido a que.

## 8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles

    XML (Extensible Markup Language) es uno de los formatos más utilizados para el intercambio de información entre sistemas. El formato de este estándar está basado en texto para representar información estructurada: datos, documentos, configuración, etc.
    Todas las etiquetas se deben cerrar y si existe un error en el XML las herramientas que los procesan darán error.
        Un ejemplo:
                    <pieza tipo="A">
                        <nombre>Tornillo</nombre>
                        <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras
                        </descripcion>
                        <caracateristica>
                            <tipo>metal</tipo>
                            <tamanyo>10</tamanyo>
                        </caracateristica>
                        <vacio></vacio>
                    </pieza>

    JSON (JavaScript Object Notation) está construido por una colección de pares de nombre y valor o por una lista ordenada de valores. En muchos lenguajes de programación tenemos elementos parecidos como pueden ser los objetos, una estructura, un diccionario, un array. Este formato es el que se suele utilizar en el los servicios web REST en la actualidad.
        Un ejemplo:
                    {
                        “pieza”: {
                            “tipo”: “A”
                            “nombre”: “Tornillo”,
                            “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
                            “caracteristica”: {
                                “tipo”: “metal”
                                “tamanyo”: 10
                            },
                            “vacio”: “”
                        }
                    }

## 9. Explicar brevemente el estándar SOAP

    SOAP (originalmente las siglas de Simple Object Access Protocol) es un protocolo estándar que define cómo dos objetos en diferentes procesos pueden comunicarse por medio de intercambio de datos XML. Es esencial para los servicios web, interfaces a través de las cuales un dispositivo puede hacer uso del servicio de un servidor. Los buscadores, las tiendas en línea y otros muchos servicios en Internet funcionan a través de dichos servicios web, y SOAP es uno de los protocolos que lo hacen posible.

## 10. Explicar brevemente el estándar REST Full

    Es un servicio que funciona como un estándar para compartir información, en un sistema de doble vía: Consulta y Respuesta (Request => Response).
    Al consultar una API se deben especificar parámetros de consulta para que el servicio sepa lo que queremos consultar, basado en una estructura previamente definida provista por el API por medio de una documentación.
    La arquitectura REST al trabajar sobre el protocolo HTTP, los procedimientos o métodos de comunicación son los mismos que HTTP, siendo los principales: GET, POST, PUT, DELETE. Otros métodos que se utilizan en RESTful API son OPTIONS y HEAD. Este último se emplea para pasar parámetros de validación, autorización y tipo de procesamiento, entre otras funciones.
    Otro componente de un RESTful API es el “HTTP Status Code”, que le informa al cliente o consumidor del API que debe hacer con la respuesta recibida. Estos son una referencia universal de resultado, es decir, al momento de diseñar un RESTful API toma en cuenta utilizar el “Status Code” de forma correcta.

## 11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

    Los headers en un request son los parámetros que se envían en una petición o respuesta HTTP al cliente o al servidor para proporcionar información esencial sobre la transacción en curso. Content-Type es la propiedad de cabecera (header) usada para indicar el media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado.

# Ejercicio 3.

## 1. [![ejercicio-1-get.jpg](https://i.postimg.cc/QC30vY6c/ejercicio-1-get.jpg)](https://postimg.cc/34tXv1Qw)

## 2. [![ejercicio-2-post.jpg](https://i.postimg.cc/rmWfn298/ejercicio-2-post.jpg)](https://postimg.cc/47fvyMMM)

## 3. [![ejercicio-3-post.jpg](https://i.postimg.cc/hGXymdzQ/ejercicio-3-post.jpg)](https://postimg.cc/t1HNQ7z9)

    La diferencia con la primer consulta, es que me trae la base con el nuevo dato que agregue con el metodo POST en el segundo ejercicio.

# Ejercicio 4 : https://trailblazer.me/id/dubocio

# Ejercicio 5.a:

## 1.Lead:

    Un lead es un usuario que, además de interesarse en tu negocio, ha contactado a tu empresa de forma proactiva, dejando alguna forma de contacto, como un número de teléfono celular o e-mail.

## 2.Account y 3.Contact:

    En Salesforce, se almacena la información sobre sus clientes mediante cuentas(account) y contactos(contact). Las cuentas son compañías con las que hace negocios y los contactos son las personas que trabajan para dichas compañías.

## 4.Opportunity:

    Las oportunidades(opportunity) son acuerdos en curso Los registros de oportunidad realizan un seguimiento de detalles acerca de acuerdos, incluyendo para qué cuentas son, quiénes son las personas implicadas y las cantidades de las ventas potenciales.

## 5.Product:

    Productos(Product) son los elementos y servicios que distribuye a clientes. Cada producto puede existir en múltiples listas de precios con precios diferentes.

## 6.PriceBook:

    Un libro de precios(price book) es una lista de productos y sus precios asociados. Cada producto y su precio se denomina entrada del libro de precios.

## 7.Quote:

    Las cotizaciones(quotes) en Salesforce representan los precios propuestos de los productos y servicios de su empresa. Usted crea una cotización a partir de una oportunidad y sus productos. Cada oportunidad puede tener varias cotizaciones asociadas y cualquiera de ellas se puede sincronizar con la cotización.

## 8.Asset:

    Un activo(asset) en Salesforce representa un producto específico adquirido o instalado. Por ejemplo, si vende casas, puede crear un producto Casas en Salesforce, y luego crear múltiples activos representando las casas que vendió.

## 9.Case:

    Un caso es una pregunta, un comentario o un problema de un cliente. Los agentes del servicio de atención al cliente pueden revisar casos para ver cómo pueden ofrecer un mejor servicio. Los representantes de ventas utilizan casos para ver cómo afectan al proceso de ventas.

## 10.Article:

    Su base de Salesforce Knowledge se crea desde artículos de conocimientos, que son documentos de información. Los artículos pueden incluir información sobre procesos, como cómo restablecer su producto a sus valores predeterminados o preguntas más frecuentes como cuánto almacenamiento admite su producto.

# Ejercicio 5.b Relaciones: [![diagrama.jpg](https://i.postimg.cc/tCR0bY3N/diagrama.jpg)](https://postimg.cc/Btz7cZwj)

# Ejercicio 6:

# 1 Soluciones de Salesforce

## 1.A: ¿Qué es Salesforce?

    Salesforce es una solución de gestión de relaciones con clientes que une empresas y clientes.

## 1.B: ¿Qué es Sales Cloud?

    Salesforce Sales Cloud es una plataforma de ventas que da seguimiento al proceso de ventas, desde perfilar prospectos, hacer el contacto inicial hasta el final de la compra.

## 1.C: ¿Qué es Service Cloud?

    Salesforce Service Cloud es la aplicación para atención al cliente número uno del mercado. Implantada directamente en la plataforma de Salesforce CRM, lo que nos permite tener una visión 360 de nuestros clientes.

## 1.D: ¿Qué es Health Cloud?

    Health Cloud permite una conversación personalizada entre el paciente y las entidades sanitarias asociadas. No solo es beneficioso para los equipos de atención médica, sino que también beneficia a los pacientes al establecer comunicaciones digitales con su equipo de atención.

## 1.E: ¿Qué es Marketing Cloud?

    Esta es una plataforma de marketing que contiene múltiples herramientas diseñadas para gestionar de manera eficiente la interacción de la marca con sus clientes (y potenciales) a través de diferentes canales.

# 2 Funcionalidades de Salesforce

## 2.A: ¿Qué es un RecordType?

    los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.

## 2.B: ¿Qué es un ReportType?

    indica el tipo de reporte al que pertenece la plantilla seleccionada previamente por el creador de la misma. Los reportes le proporcionan el acceso a sus datos de Salesforce.

## 2.C: ¿Qué es un Page Layout?

    Puede personalizar muchas cosas en una página de registro de un objeto específico utilizando formatos de página.
    Existen dos maneras de personalizar una página en Lightning Experience. Puede personalizar un formato de página, o personalizar sus contenidos. Esto se hace con herramientas separadas.

## 2.D: ¿Qué es un Compact Layout?

    Los formatos compactos controlan qué campos aparecen en el encabezado. Para cada objeto, puede asignar hasta 10 campos, incluyendo el campo Nombre, para mostrar en ese área.

## 2.E: ¿Qué es un Perfil?

    Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación.

## 2.F: ¿Qué es un Rol?

    Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.

## 2.G: ¿Qué es un Validation Rule?

    Las reglas de validación verifican que los datos que un usuario introduce en un registro cumplen con las normas que especifica antes de que el usuario guarde el registro. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y ofrece un valor “Verdadero” o “Falso”.

## 2.H: ¿Qué diferencia hay entre una relación Master Detail y Lookup?

    La Principal diferencia entre ambas es que las relaciones de búsqueda(lookup) pueden ser de uno a uno o de uno a muchos y las relaciones Master-detail  son de uno (padre) a uno (hijo).

## 2.I: ¿Qué es un Sandbox?

    Un Sandbox es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de su organización de producción de Salesforce.

## 2.J: ¿Qué es un ChangeSet?

    Un conjunto de cambios entrantes es un conjunto de cambios que se ha enviado desde otra organización de Salesforce a la organización en la que ha iniciado sesión. Un conjunto de cambios se debe implementar para que los cambios surtan efecto.

## 2.K: ¿Para qué sirve el import Wizard de Salesforce?

    Se puede utilizar para importar un máximo de 50,000 registros.

## 2.L: ¿Para qué sirve la funcionalidad Web to Lead?

    Web-to-Lead permite diseñar un formulario incluyendo las preguntas más adecuadas para cada tipo de negocio con el objetivo de insertarlo en un blog o una web corporativa, automatizando así la captación de leads y la integración de los datos de los usuarios en el CRM.

## 2.M: ¿Para qué sirve la funcionalidad Web to Case?

    Permita a los clientes enviar solicitudes de asistencia en su sitio web utilizando un formulario personalizable sencillo. Utilizar Casos Web para recopilar consultas de asistencia y convertirlas automáticamente en casos. Casos Web puede ayudar a responder a los clientes con mayor rapidez, lo que supone un aumento de la productividad del equipo de atención al cliente.

## 2.N: ¿Para qué sirve la funcionalidad Omnichannel?

    Omnichannel asigna elementos de trabajo a una cola y luego distribuye los elementos de trabajo a un agente que es un miembro de esa cola. Funciona de forma nativa en Salesforce. Es óptimo para organizaciones de reducido tamaño que admiten un número limitado de productos.

## 2.O: ¿Para qué sirve la funcionalidad Chatter?

    Chatter es una red social empresarial de Salesforce. Diseñada para permitir y mejorar el uso compartido y la colaboración, se puede utilizar para compartir información, proponer ideas, conectar equipos y proporcionar comentarios.

# 3 Conceptos Generales

## 3.A: ¿Qué significa SaaS?

    SaaS, o Software as a Service, es una forma de poner a disposición softwares y soluciones de tecnología por medio de la internet, como un servicio. Con este modelo, tu empresa no necesita instalar, mantener y actualizar hardwares y softwares.

## 3.B: ¿Salesforce es Saas?

    Salesforce es una compañía de PaaS (Plataforma como Servicio), un concepto que nace como resultado de la aplicación al desarrollo de Software del modelo SaaS (Software como Servicio). Este modelo abarca el ciclo completo para desarrollar e implantar aplicaciones desde Internet.

## 3.C: ¿Qué significa que una solución sea Cloud?

    Significa que la solución es una tecnología que permite el acceso remoto a softwares, procesamiento de datos y almacenamiento de archivos a través de Internet. No demanda la instalación de aplicaciones a nivel local, sino que ofrece los servicios a gran escala gracias a la conectividad.

## 3.D: ¿Qué significa que una solución sea On-Premise?

    El término On-Premise, alude a la instalación de una solución informática llevada a cabo dentro de la infraestructura tecnológica de una empresa, es decir, dentro de su hardware y software, por lo tanto, On-Premise implica la instalación de software en el propio servidor de una compañía.

## 3.E: ¿Qué es un pipeline de ventas?

    El pipeline de ventas es, precisamente, el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes.

## 3.F: ¿Qué es un funnel de ventas?

    Un funnel de ventas o embudo de conversión es un sistema diseñado para atraer a desconocidos, convertirlos en leads y transformarlos en clientes. Así de fácil, así de simple. En pocas palabras, el objetivo del funnel es: Conseguir clientes potenciales.

## 3.G: ¿Qué significa Customer Experience?

    La experiencia del cliente (CX) es cómo se relaciona una empresa con sus clientes en todos los aspectos del recorrido de compra, desde el marketing hasta las ventas y el servicio al cliente pasando por cada punto intermedio. En gran parte, es la suma total de todas las interacciones que un cliente tiene con tu marca.

## 3.H: ¿Qué significa omnicanalidad?

    Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.). El uso de los diferentes canales debe hacerse bajo una misma estrategia para llegar al consumidor en el momento indicado.

## 3.I: ¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?

    El B2B (business to business) es el modelo de negocio en el que se realizan transacciones comerciales entre empresas. En cambio, en el modelo B2C (business to consumer) esas transacciones se efectúan entre negocios de cualquier magnitud y los consumidores. KPI son las siglas de Key Performance Indicators, que puede traducirse al castellano como “Indicadores Clave de Desempeño”. Estos indicadores se componen de variables, factores o unidades de medida que sirven para generar estrategias dentro de los departamentos de una empresa.

## 3.J: ¿Qué es una API y en qué se diferencia de una Rest API?

    API o Application Programming Interface, que en español quiere decir Interfaz de Programación de Aplicaciones, es un conjunto de funciones y procedimientos que permite integrar sistemas, permitiendo que sus funcionalidades puedan ser reutilizadas por otras aplicaciones o software. Por lo general, la API sigue el formato de aplicación a aplicación, mientras que REST sigue una estructura diferente: Cliente-Servidor. El cliente y el servidor están evolucionando de forma independiente, proporcionando más flexibilidad en el trabajo.

## 3.K: ¿Qué es un Proceso Batch?

    El procesamiento por lotes, también conocido en inglés como batch processing o simplemente batch, consiste en la ejecución de un programa sin supervisión del usuario. Es decir, que pueden ejecutarse sin necesidad de que el usuario realice ninguna interacción.

## 3.L: ¿Qué es Kanban?

    La metodología Kanban se implementa por medio de tableros Kanban. Se trata de un método visual de gestión de proyectos que permite a los equipos visualizar sus flujos de trabajo y la carga de trabajo. En un tablero Kanban, el trabajo se muestra en un proyecto en forma de tablero organizado por columnas.

## 3.M: ¿Qué es un ERP?

    Enterprise Resource Planning (ERP) es un tipo de software que las organizaciones utilizan para gestionar las actividades empresariales diarias, como la contabilidad, el aprovisionamiento, la gestión de proyectos, la gestión de riesgos, el cumplimiento y las operaciones de la cadena de suministro.

## 3.N: ¿Salesforce es un ERP?

    Si bien Salesforce, tiene similitudes con el sistema ERP, es un CRM ya que busca principalmente incrementar las ventas.
